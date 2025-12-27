---
title: "Cấu trúc chương trình Java cơ bản"
date: 2025-07-17
tags: ["java", "backend"]
categories: ["Programming"]
draft: false
---
## Khi OOP không còn đáng sợ

Thời gian đầu, mình rất sợ:

Class là gì?

Object là gì?

Kế thừa dùng khi nào?

Mọi thứ đều trừu tượng cho đến khi mình tự viết một chương trình quản lý sinh viên.

Khi đó mình nhận ra:

Class giống như bản thiết kế

Object là sản phẩm tạo ra từ bản thiết kế đó

OOP giúp code gọn hơn, dễ bảo trì hơn

Từ lúc hiểu OOP, mình bắt đầu thấy Java rất logic và rõ ràng, không còn “mơ hồ” như lúc đầu.
## 📘 BÀI 3 – Lập trình hướng đối tượng trong Java

```markdown
---
title: "Lập trình hướng đối tượng trong Java"
date: 2025-07-17
draft: false
---

## OOP là gì?
OOP giúp tổ chức chương trình rõ ràng hơn thông qua:

- Đóng gói
- Kế thừa
- Đa hình
- Trừu tượng

## Ví dụ
```java
class Student {
    String name;
    void study() {
        System.out.println("Studying...");
    }
}
