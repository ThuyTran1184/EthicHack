---
title: "Xử lý bất đồng bộ trong JavaScript"
date: 2025-10-15
description: "Kinh nghiệm học tập"
tags: ["intro", "blog"]
---

Xử lý bất đồng bộ trong JavaScript
JavaScript hỗ trợ xử lý bất đồng bộ để làm việc với các tác vụ như gọi API hoặc đọc file.
Các cơ chế chính

Callback:

```js
setTimeout(() => console.log("Chào sau 2 giây"), 2000);
```

Promise:

```js
const promise = new Promise((resolve, reject) => {
  setTimeout(() => resolve("Thành công!"), 1000);
});
promise.then(result => console.log(result));
```

Async/Await (ES8):

```js
async function layDuLieu() {
  const result = await new Promise(resolve =>
    setTimeout(() => resolve("Thành công!"), 1000)
  );
  console.log(result);
}
layDuLieu();
```

Ứng dụng

Gọi API từ server.
Xử lý các tác vụ cần thời gian như tải hình ảnh.
