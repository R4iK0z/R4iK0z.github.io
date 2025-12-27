---
title: "Cấu trúc chương trình Java cơ bản"
date: 2025-07-17
tags: ["java", "backend"]
categories: ["Programming"]
draft: false
---
## Những dòng code Java đầu tiên
Ngày đầu học Java, mình chỉ biết mở IDE và gõ theo thầy.
public static void main(String[] args) nhìn dài và khó hiểu, nhưng lúc chương trình in ra dòng "Hello World" đầu tiên, mình đã thấy rất “đã”.

Java lúc đó giống như một mê cung: class, object, method, biến, kiểu dữ liệu…
Sai một dấu ; là lỗi cả chương trình.

Nhưng càng học, mình càng hiểu rằng Java không khó, chỉ cần kiên nhẫn.
Mỗi lỗi compile là một bài học. Mỗi bug sửa được là một lần mình hiểu rõ hơn cách máy tính suy nghĩ.

## Cấu trúc cơ bản
Một chương trình Java gồm:
- Package
- Class
- Hàm main()

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello Java");
    }
}
