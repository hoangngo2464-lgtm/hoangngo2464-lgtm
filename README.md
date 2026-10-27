# Xin chào, mình là Ngô Hoàng 👋

**IoT | Embedded Systems | TinyML | Arduino/ESP32 | Robotics**

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=00979D&center=true&vCenter=true&width=620&lines=IoT+%26+Embedded+Developer;ESP32+%2F+Arduino+Projects;TinyML+Voice+Recognition;Robotics+%26+Control+Systems;Python+Tools+%26+Automation" alt="Typing SVG" />
</p>

Mình xây dựng các dự án về hệ thống nhúng, IoT, TinyML, robot dò line, điều khiển cảm biến, RTOS và công cụ hỗ trợ bằng Python. Mục tiêu của mình là viết code dễ hiểu, chạy được trên phần cứng thật và có tài liệu đủ rõ để người khác xem là nắm được cách hoạt động.

> Code tốt là code chạy được trên thực tế, dễ hiểu và có thể kiểm chứng.

---

## 🚀 Dự án nổi bật

### 🎙️ [Nhận dạng giọng nói tiếng Việt bằng TinyML trên ESP32](https://github.com/hoangngo2464-lgtm/tinyml-vietnamese-voice-recognition)

Nhận dạng lệnh **bật/tắt đèn bằng tiếng Việt** chạy trực tiếp trên ESP32, không cần Internet và không gửi âm thanh lên máy chủ.

- **Pipeline:** microphone INMP441 → tiền xử lý → trích xuất MFCC → mô hình CNN → điều khiển LED.
- **4 lớp nhận dạng:** `ON_LIGHT`, `OFF_LIGHT`, `UNKNOWN`, `NOISE`.
- **Kết quả đánh giá trên Edge Impulse:** validation accuracy 91,2%, test accuracy 87,2%, suy luận khoảng 110 ms, dùng khoảng 20,8 KB RAM và 38 KB flash.
- **Công nghệ:** ESP32-WROOM-32E, INMP441, Edge Impulse, TensorFlow Lite for Microcontrollers, Arduino IDE.

### 🐠 [BECA – Smart Aquarium IoT System](https://github.com/hoangngo2464-lgtm/IOT--Smart-Aquarium-IoT-System)

Hệ thống giám sát và điều khiển bể cá thông minh, theo dõi chất lượng nước và điều khiển thiết bị từ xa qua web.

- Đọc cảm biến TDS và độ đục, điều khiển máy bơm và đèn, hỗ trợ chế độ tự động/thủ công và lịch bật đèn.
- Đồng bộ dữ liệu bằng Firebase Realtime Database, cập nhật firmware từ xa qua OTA, cấu hình Wi-Fi bằng WiFiManager.
- Giao diện web triển khai trên Vercel, có trợ lý AI (Groq API, Llama 3.3) hỗ trợ phân tích dữ liệu.
- **Demo:** [beca-theta.vercel.app](https://beca-theta.vercel.app)
- **Công nghệ:** ESP32, Arduino IDE, Firebase, HTML/CSS/JavaScript, Vercel.

### 🏎️ [dolineweb](https://github.com/hoangngo2464-lgtm/dolineweb)

Xe dò line kết hợp né vật cản, dùng bộ điều khiển PID và bộ lọc Kalman. Repo có nhiều phiên bản thử nghiệm, tài liệu báo cáo và sơ đồ dây.

**Công nghệ:** Arduino, C++, PID, Kalman Filter.

### ⏱️ [ROTS](https://github.com/hoangngo2464-lgtm/ROTS)

Tìm hiểu hệ điều hành thời gian thực (RTOS) và thực hành 2 bài tập đa nhiệm, có mô phỏng trên Proteus và chạy trên Arduino.

**Công nghệ:** Arduino, C++, RTOS, Proteus.

### 🔐 [mahoaLZW](https://github.com/hoangngo2464-lgtm/mahoaLZW)

Ứng dụng mô phỏng thuật toán nén/mã hóa từ điển LZW, có giao diện trực quan.

**Công nghệ:** Python, Tkinter.

---

## 🧰 Kỹ năng chính

<p align="center">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white" />
  <img src="https://img.shields.io/badge/ESP32-303030?style=for-the-badge&logo=espressif&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Edge%20Impulse-0B2A4A?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Proteus-1D4ED8?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

- Lập trình Arduino/ESP32, đọc cảm biến, điều khiển động cơ và thiết bị chấp hành.
- Triển khai TinyML trên vi điều khiển: thu thập dữ liệu âm thanh, trích xuất MFCC, huấn luyện CNN với Edge Impulse.
- Thiết kế robot dò line, né vật cản; ứng dụng PID và Kalman Filter.
- Làm việc với RTOS (task, delay) và mô phỏng bằng Proteus.
- Kết nối IoT với Firebase, Telegram, web/mobile app; cập nhật firmware OTA.
- Viết ứng dụng Python GUI, thuật toán và công cụ hỗ trợ học tập.

---

## 🔧 Đang hoàn thiện

- Chuẩn hóa README cho từng repo.
- Tổ chức lại thư mục `src/`, `docs/`, `images/`.
- Đưa source code firmware đầy đủ lên GitHub (đặc biệt cho dự án TinyML).
- Thêm hình ảnh, sơ đồ dây và video demo.
- Viết hướng dẫn build, nạp code và kiểm thử phần cứng.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=hoangngo2464-lgtm&show_icons=true&theme=github_dark&hide_border=true" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hoangngo2464-lgtm&layout=compact&theme=github_dark&hide_border=true" alt="Top Languages" />
</p>

---

## 📫 Kết nối

<p align="center">
  <a href="https://github.com/hoangngo2464-lgtm">
    <img src="https://img.shields.io/badge/GitHub-hoangngo2464--lgtm-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <!-- Bỏ comment và thay bằng thông tin thật của bạn:
  <a href="mailto:EMAIL_CUA_BAN">
    <img src="https://img.shields.io/badge/Email-contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="LINK_FACEBOOK_CUA_BAN">
    <img src="https://img.shields.io/badge/Facebook-profile-1877F2?style=for-the-badge&logo=facebook&logoColor=white" />
  </a>
  <a href="LINK_LINKEDIN_CUA_BAN">
    <img src="https://img.shields.io/badge/LinkedIn-profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  -->
</p>

> Mình ưu tiên làm dự án có thể chạy thật, kiểm chứng được và trình bày rõ ràng.
> ⭐ Sẵn sàng học hỏi, xây dựng sản phẩm thực tế và hợp tác trong các dự án IoT/Embedded.
