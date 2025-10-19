---
title: "Lớp và đối tượng trong Java"
date: 2025-10-15
description: "Kinh nghiệm học tập"
tags: ["intro", "blog"]
---
 Lớp và đối tượng trong Java
Java là ngôn ngữ lập trình hướng đối tượng, với lớp (class) và đối tượng (object) là nền tảng.
Cách khai báo lớp

```js
public class Nguoi {
  String ten;
  int tuoi;

  public Nguoi(String ten, int tuoi) {
    this.ten = ten;
    this.tuoi = tuoi;
  }

  public void chao() {
    System.out.println("Xin chào, tôi là " + ten);
  }
}
```

Tạo đối tượng

```js
Nguoi nguoi = new Nguoi("Grok", 25);
nguoi.chao(); // In ra: Xin chào, tôi là Grok
```

Đặc điểm

Java hỗ trợ kế thừa, đóng gói, và đa hình.
Mọi chương trình Java đều cần ít nhất một lớp chứa hàm main.
