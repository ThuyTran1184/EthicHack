---
title: "Biến và kiểu dữ liệu trong JavaScript"
date: 2025-10-15
description: "Kinh nghiệm học tập"
tags: ["intro", "blog"]
---

 Biến và kiểu dữ liệu trong JavaScript
JavaScript là ngôn ngữ lập trình động, hỗ trợ nhiều kiểu dữ liệu khác nhau.
Các kiểu dữ liệu

Nguyên thủy (Primitive): Number, String, Boolean, Undefined, Null, Symbol, BigInt.
Đối tượng (Object): Array, Object, Function.

Khai báo biến
JavaScript sử dụng ba từ khóa để khai báo biến:

var: Phạm vi toàn cục hoặc hàm, ít được sử dụng hiện nay.
let: Phạm vi khối, có thể gán lại giá trị.
const: Phạm vi khối, không thể gán lại giá trị.

Ví dụ:

```js
let ten = "Giang";
const tuoi = 25;
console.log(ten, tuoi); // In ra: Giang 25
```
