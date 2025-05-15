# Mobile Programming Application

Lập trình mobile app (ứng dụng di động) được chia thành 3 loại chính. <br>

#### 1. [Native App (Ứng dụng gốc)](https://github.com/DauBv/Mobile-Programming-Application/tree/main/Native-App)

- **Đặc điểm:**
   * Viết riêng biệt cho từng hệ điều hành.
   * Sử dụng ngôn ngữ lập trình gốc:
      * Android: Java/Kotlin
      * iOS: Swift/Objective-C
   * Tận dụng tối đa hiệu suất và khả năng truy cập phần cứng của thiết bị (camera, GPS, v.v.)

- **Ưu điểm:**
   * Hiệu suất cao
   * Trải nghiệm người dùng mượt mà
   * Tối ưu hoá cho từng nền tảng

- **Nhược điểm**
   * Tốn thời gian và chi phí vì phải phát triển riêng cho từng nền tảng.
   * Bảo trì phức tạp.

#### 2. [Cross-Platform App (Ứng dụng đa nền tảng)](https://github.com/DauBv/Mobile-Programming-Application/tree/main/Cross-platform-App)

- **Đặc điểm:**
   * Viết một lần, chạy trên nhiều nền tảng (Android & iOS)
   * Dùng các framework như:
      * React Native (JavaScript)
      * Flutter (Dart)
      * Xamarin (C#)

- **Ưu điểm:**
   * Tiết kiệm thời gian và chi phí
   * Dễ bảo trì do dùng chung mã nguồn

- **Nhược điểm**
   * Hiệu suất có thể không bằng native
   * Một số tính năng phần cứng cần viết code native riêng
#### 3. [Hybrid App (Ứng dụng lai)](https://github.com/DauBv/Mobile-Programming-Application/tree/main/Hybrid-App)

- **Đặc điểm:**
   * Sử dụng công nghệ web (HTML, CSS, JavaScript) để xây dựng giao diện
   * Chạy bên trong một “webview” (trình duyệt nhúng)
   * Dùng các framework như: Ionic, Cordova

- **Ưu điểm:**
   * Phát triển nhanh chóng, tận dụng kỹ năng web

- **Nhược điểm**
   * Hiệu suất kém hơn Native và Cross-platform
   * Trải nghiệm người dùng không mượt mà

#### So sánh nhanh
| Loại App       | Hiệu suất | Chi phí phát triển | Tận dụng phần cứng | Giao diện người dùng | Tái sử dụng mã nguồn |
| -------------- | --------- | ------------------ | ------------------ | -------------------- | -------------------- |
| Native         | Rất cao   | Cao                | Tốt nhất           | Mượt mà nhất         | Không                |
| Cross-platform | Tốt       | Trung bình         | Tốt (có giới hạn)  | Tốt                  | Cao                  |
| Hybrid         | Thấp      | Thấp               | Hạn chế            | Trung bình           | Rất cao              |
