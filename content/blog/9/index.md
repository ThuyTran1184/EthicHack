---
title: " Quản lý bộ nhớ trong Java"
date: 2025-10-15
description: "Kinh nghiệm học tập"
tags: ["intro", "blog"]
---

 Quản lý bộ nhớ trong Java
Java sử dụng cơ chế quản lý bộ nhớ tự động thông qua Garbage Collector (GC).
Cách hoạt động

Java cấp phát bộ nhớ cho các đối tượng trên Heap.
Garbage Collector tự động thu hồi bộ nhớ từ các đối tượng không còn được tham chiếu.
Các khu vực bộ nhớ chính: Young Generation, Old Generation, và Permanent Generation (trước Java 8).

Ví dụ

```js
public class ViDu {
  public static void main(String[] args) {
    String str = new String("Grok"); // Tạo đối tượng
    str = null; // Đối tượng không còn tham chiếu, GC sẽ thu hồi
  }
}
```

Lợi ích

Giảm nguy cơ rò rỉ bộ nhớ.
Đơn giản hóa việc quản lý tài nguyên cho lập trình viên.
