# THUYẾT MINH ĐỀ TÀI DỰ ÁN NGHIÊN CỨU KHOA HỌC KỸ THUẬT

## **DESKFLOW – TRẠM HỌC TẬP THÔNG MINH TÍCH HỢP ĐÈN BÀN CÔNG THÁI HỌC IoT VÀ TRỢ LÝ HỌC TẬP AI**

> **Tải xuống bản Word (.docx) chính thức tại đây:**  
> 👉 [**Tải về file Word (.docx) - Thuyet_Minh_Du_An_DeskFlow_Khuong_Huu_Minh_Quan_8A6.docx**](./Thuyet_Minh_Du_An_DeskFlow_Khuong_Huu_Minh_Quan_8A6.docx?raw=true)  
> 👉 [**Link tải nhanh (Dự phòng)**](./DeskFlow_Thuyet_Minh.docx?raw=true)

---

### **THÔNG TIN DỰ ÁN & TÁC GIẢ**
* **Tác giả đề tài:** **Khương Hữu Minh Quân**
* **Lớp:** **8A6**
* **Lĩnh vực nghiên cứu:** Hệ thống nhúng (Embedded Systems) – Phần mềm hệ thống (System Software) & IoT.
* **Địa bàn thực hiện:** Thành phố Hạ Long, Tỉnh Quảng Ninh.
* **Thiết bị chế tạo chính:** Máy in 3D FDM Bambu Lab A1 (Nhựa PLA Trắng / PETG Trắng).
* **Năm thực hiện:** 2025 – 2026.

---

### **MỤC LỤC BẢN THUYẾT MINH**
1. [GIỚI THIỆU ĐỀ TÀI & TÍNH CẤP THIẾT](#1-giới-thiệu-đề-tài--tính-cấp-thiết)
2. [MỤC TIÊU VÀ Ý NGHĨA](#2-mục-tiêu-và-ý-nghĩa)
3. [CẤU TẠO TỔNG THỂ HỆ THỐNG](#3-cấu-tạo-tổng-thể-hệ-thống)
4. [THIẾT KẾ CƠ KHÍ & IN 3D TRÊN BAMBU LAB A1](#4-thiết-kế-cơ-khí--in-3d-trên-bambu-lab-a1)
5. [THIẾT KẾ ĐIỆN TỬ & SƠ ĐỒ ĐẤU NỐI MẠCH](#5-thiết-kế-điện-tử--sơ-đồ-đấu-nối-mạch)
6. [NGUYÊN LÝ HOẠT ĐỘNG & CÁC TÍNH NĂNG ĐỘT PHÁ](#6-nguyên-lý-hoạt-động--các-tính-năng-đột-phá)
7. [PHẦN MỀM HỆ THỐNG & GIAO THỨC TRUYỀN THÔNG IoT](#7-phần-mềm-hệ-thống--giao-thức-truyền-thông-iot)
8. [AN TOÀN ĐIỆN NĂNG & BÁO CÁO THỰC TẾ KHỐI PIN](#8-an-toàn-điện-năng--báo-cáo-thực-tế-khối-pin)
9. [QUY TRÌNH CHẾ TẠO VÀ LẮP RÁP](#9-quy-trình-chế-tạo-và-lắp-ráp)
10. [KẾT QUẢ KIỂM THỬ THỰC NGHIỆM](#10-kết-quả-kiểm-thử-thực-nghiệm)
11. [TÍNH MỚI, HẠN CHẾ & HƯỚNG PHÁT TRIỂN](#11-tính-mới-hạn-chế--hướng-phát-triển)
12. [KẾT LUẬN & CAM KẾT TÁC QUYỀN](#12-kết-luận--cam-kết-tác-quyền)

---

### 1. GIỚI THIỆU ĐỀ TÀI & TÍNH CẤP THIẾT
Trong thời đại chuyển đổi số hiện nay, học sinh trung học phải đối mặt với áp lực học tập ngày càng cao cùng vô số yếu tố gây xao nhãng. Góc bàn học của học sinh thường xuất hiện tình trạng bừa bộn do phải bố trí nhiều vật dụng rời rạc: đèn học, đồng hồ báo thức, thời khóa biểu giấy dán tường, điện thoại để bấm giờ học bài (Pomodoro) và máy tính xách tay. Sự phân tán này dẫn đến hai hệ lụy nghiêm trọng: giảm diện tích thao tác học tập và đặc biệt là thói quen sử dụng điện thoại khi đang học, dẫn đến hiện tượng trì hoãn (procrastination) và mất tập trung kéo dài.

Để giải quyết triệt để vấn đề trên, em **Khương Hữu Minh Quân (Lớp 8A6)** đã nghiên cứu, lên ý tưởng và chế tạo sản phẩm **DeskFlow** – Trạm học tập thông minh để bàn tích hợp đèn học công thái học IoT. DeskFlow kết hợp đồng bộ giữa cơ khí in 3D chính xác, mạch điện tử vi điều khiển ESP32, màn hình màu IPS, giao thức mạng IoT MQTT và trợ lý thông minh Discord/App. Sản phẩm đóng vai trò là một trung tâm điều khiển (hub) tập trung mọi tiện ích thiết yếu ngay trước tầm mắt người học.

---

### 2. MỤC TIÊU VÀ Ý NGHĨA
* **Tích hợp công thái học và chiếu sáng thông minh:** Thiết kế vỏ nêm nghiêng 60° và cổ đèn dạng chuỗi khớp cầu xoay 360° bằng máy in 3D Bambu Lab A1; tích hợp vòng LED WS2812B 16.7 triệu màu điều chỉnh độ sáng tuyến tính tức thời (0-100%).
* **Hiển thị thông tin học tập trực quan:** Màn hình IPS ST7789 2.0 inch hiển thị đồng hồ chuẩn Internet NTP, thời khóa biểu hôm nay/ngày mai của lớp 8A6, đồng phục quy định, thời tiết Hạ Long và thông số phần cứng máy tính.
* **Cơ chế rèn luyện kỷ luật học tập:** Xây dựng Chế độ tập trung (Focus Mode) và Báo thức toán học (Math Alarm) buộc người học phải giải câu đố toán ngẫu nhiên mới có thể dập tắt chuông hoặc mở khóa trạm.
* **Hệ sinh thái điều khiển đa nền tảng:** Kết nối tức thời giữa trạm DeskFlow với Bot Discord và ứng dụng chuyên dụng trên Android (Jetpack Compose), Windows (WinUI 3), Linux và macOS.

---

### 3. CẤU TẠO TỔNG THỂ HỆ THỐNG
| Phân hệ | Thành phần linh kiện chính | Chức năng & Vai trò trong hệ thống |
| :--- | :--- | :--- |
| **Xử lý trung tâm** | ESP32 DevKit V1 (Xtensa Dual-core 240MHz, Wi-Fi/BLE) | Xử lý logic, kết nối Wi-Fi, điều phối giao thức MQTT và giao tiếp ngoại vi. |
| **Hiển thị trực quan** | TFT LCD ST7789 2.0 inch (240 × 320 px, IPS) | Hiển thị đồng hồ, giao diện học tập, thời khóa biểu, thông báo và thông số máy tính. |
| **Chiếu sáng bàn học** | Vòng 8 LED WS2812B NeoPixel, chao đèn in 3D | Phát ánh sáng trắng học tập và ánh sáng môi trường (Ambient) 16.7 triệu màu HEX. |
| **Điều khiển vật lý** | 3 nút nhấn Tactile (PREV, PLAY/MODE, NEXT) | Điều hướng giao diện, bật/tắt đèn, dừng phát nhạc, chuyển màn hình trực tiếp. |
| **Cảnh báo âm thanh** | Passive Buzzer (Còi xung PWM) | Phát chuông báo thức giải toán, nhạc Chiptune 8-bit và âm thanh mã Morse. |
| **Khối nguồn điện** | Module TP4056 Type-C, cầu phân áp đo áp ADC | Cấp nguồn hệ thống, theo dõi điện áp và quản lý sạc/xả pin an toàn. |
| **Kết cấu cơ khí** | Thân hộp nêm, khớp cầu ball-socket in 3D | Định vị linh kiện, bảo vệ mạch điện và điều chỉnh hướng chiếu sáng linh hoạt. |

---

### 4. THIẾT KẾ CƠ KHÍ & IN 3D TRÊN BAMBU LAB A1
* **Thân trạm dạng nêm (Wedge Shape):** Mặt trước nghiêng góc 60° công thái học, giúp màn hình ST7789 vuông góc với trục mắt của học sinh khi ngồi học. Mặt đế rộng 120 x 95 mm giúp hạ thấp trọng tâm, đảm bảo máy đứng vững chãi không bị lật khi thao tác bấm phím.
* **Cổ đèn khớp cầu mô-đun (Ball-and-Socket Joints):** Bao gồm chuỗi các đốt khớp nối hình cầu lồng khít vào nhau. Thiết kế này cho phép uốn cong 3D đa hướng, xoay 360° để hắt sáng thẳng vào vở hoặc xoay hắt lên tường tạo ánh sáng gián tiếp chống mỏi mắt.
* **Kỹ thuật in trên máy Bambu Lab A1:** Sử dụng vật liệu PLA Trắng hoặc PETG Trắng. Độ cao lớp in thân máy là 0.20 mm, riêng các đốt khớp cầu in ở độ phân giải 0.12 mm để đảm bảo mặt cầu đạt độ nhẵn hoàn hảo. Khe hở thiết kế (clearance) giữa đầu bi và ngón ôm socket được hiệu chuẩn chính xác ở mức 0.18 mm, tạo độ ma sát tối ưu giúp giữ vững vị trí chao đèn mà không bị gãy chi tiết khi xoay.

---

### 5. THIẾT KẾ ĐIỆN TỬ & SƠ ĐỒ ĐẤU NỐI MẠCH
| Khối chức năng | Chân GPIO ESP32 | Giao thức / Cơ chế | Ghi chú kỹ thuật |
| :--- | :--- | :--- | :--- |
| **Màn hình ST7789** | GPIO 18 (SCK)<br>GPIO 23 (MOSI)<br>GPIO 19 (DC)<br>GPIO 4 (RST)<br>GPIO 21 (CS) | SPI phần cứng (VSPI)<br>Tần số 40 MHz | Góc nhìn 178°, hỗ trợ bảng màu RGB565 65.536 màu. |
| **Đèn LED WS2812B** | GPIO 2 (DIN) | 1-Wire High-Speed (800 kHz) | Nguồn 5V riêng, chung đường GND với vi điều khiển. |
| **Còi báo Buzzer** | GPIO 32 | LEDC PWM Channel | Điều chế xung vuông tần số biến thiên từ 200 Hz đến 4500 Hz. |
| **Phím [PREV]** | GPIO 26 | Digital Input (Pull-up) | Nhấn nút kéo xuống GND, chống rung phần mềm debounce 50ms. |
| **Phím [PLAY/MODE]**| GPIO 14 | Digital Input (Pull-up) | Nhấn nhả: Đổi bài/chế độ; Nhấn giữ 1s: Chuyển màn hình. |
| **Phím [NEXT]** | GPIO 27 | Digital Input (Pull-up) | Nhấn nút kéo xuống GND, chuyển bài hát hoặc chuyển trang. |
| **Đo điện áp nguồn** | GPIO 34 (ADC1) | Analog-to-Digital (12-bit) | Cầu phân áp trở 100kΩ / 100kΩ; dải đo 0 - 3.3V an toàn. |

#### **Giải thuật điều chỉnh độ sáng tuyến tính (Linear Brightness Scaling):**
$$R_{\text{scaled}} = \left\lfloor \frac{R_{\text{gốc}} \times \text{Brightness}}{100} \right\rfloor, \quad G_{\text{scaled}} = \left\lfloor \frac{G_{\text{gốc}} \times \text{Brightness}}{100} \right\rfloor, \quad B_{\text{scaled}} = \left\lfloor \frac{B_{\text{gốc}} \times \text{Brightness}}{100} \right\rfloor$$
Giữ nguyên vẹn mã màu gốc, giúp độ sáng thay đổi mượt mà từ 0% đến 100% theo thời gian thực mà không làm biến dạng sắc độ.

---

### 6. NGUYÊN LÝ HOẠT ĐỘNG & CÁC TÍNH NĂNG ĐỘT PHÁ
1. **Chế độ tập trung (Focus Mode) kết hợp thử thách Toán học:** Khóa màn hình app/desktop, nếu muốn mở trước giờ bắt buộc phải tính nhẩm và nộp kết quả bài toán ngẫu nhiên (VD: $73 \times 8 - 149$).
2. **Báo thức đánh thức phản xạ (Math Alarm):** Còi kêu ngắt quãng cùng đèn nhấp nháy, học sinh phải rời giường giải đúng câu đố toán trên màn hình để tắt chuông.
3. **Giám sát hiệu năng máy tính (PC Telemetry):** Đồng bộ CPU %, RAM % và % Pin laptop về trạm mỗi giây một lần.
4. **Tự động đồng bộ TKB & Quét mưa 06:15 sáng:** Nhắc lịch học và quy định đồng phục của lớp 8A6, tự động kiểm tra thời tiết Hạ Long và hiện cảnh báo mang áo mưa.
5. **Trình phát nhạc Chiptune 8-bit & Phân giải MIDI:** Tích hợp bộ phân giải tệp MIDI với bộ đệm mở rộng 32KB trên ESP32 và công cụ dịch mã Morse.

---

### 7. PHẦN MỀM HỆ THỐNG & GIAO THỨC TRUYỀN THÔNG IoT
* **Backend Server (Python Asyncio):** Chạy trên máy chủ `10th01ssh.duckdns.org` điều phối MQTT Mosquitto, PocketBase và hệ thống xác thực HMAC token bảo mật không mật khẩu.
* **Discord Bot Gateway:** Hỗ trợ các lệnh `/app pair`, `/melody`, `/lamp_color`, `/lamp_dim`, `/alarm`, `/solve`, tự động tạo ảnh mã QR trong tin nhắn Discord.
* **Ứng dụng di động & Desktop:** Ứng dụng Android (Jetpack Compose) vuốt đổi độ sáng đèn theo thời gian thực (Throttle 50ms), ứng dụng Desktop WinUI 3 tự tạo mã QR đăng nhập nội bộ.

---

### 8. AN TOÀN ĐIỆN NĂNG & BÁO CÁO THỰC TẾ KHỐI PIN

> ⚠️ **BÁO CÁO TÌNH HÌNH THỰC TẾ KHỐI NGUỒN PIN DỰ PHÒNG (GHI CHÚ KỸ THUẬT QUAN TRỌNG):**  
> **Hiện tại tới bây giờ em mới thử pin thì mới biết nó hỏng mà không đặt hàng về kịp.**  
> *Cụ thể: Trong quá trình kiểm tra tích hợp toàn diện hệ thống vào những ngày cuối trước khi hoàn thiện đề tài, cell pin Lithium 18650 chuẩn bị sẵn bị lỗi hỏng cell nội trở cao (không giữ được điện áp và sạc không vào điện). Do thời gian gấp rút sát ngày nộp và báo cáo đề tài, em không kịp đặt hàng mua cell pin mới về thay thế.*  
> *Tuy nhiên, toàn bộ mạch sạc bảo vệ TP4056 (IC DW01A + FS8205A) và mạch cầu phân áp đo dung lượng pin (ADC GPIO 34) đã được em hàn nối trên bo mạch và nạp code firmware hoàn thiện 100%. Hiện tại, thiết bị trạm DeskFlow đang được cấp nguồn hoạt động cực kỳ ổn định, liên tục và an toàn bằng nguồn điện trực tiếp 5V qua cổng Type-C (cắm củ sạc điện thoại hoặc cổng USB máy tính). Ngay sau đợt báo cáo này, em sẽ đặt mua cell pin 18650 chất lượng cao mới để lắp bổ sung vào khoang pin có sẵn trong thân máy.*

---

### 9. QUY TRÌNH CHẾ TẠO VÀ LẮP RÁP
* **Bước 1:** Thiết kế mô hình 3D trên phần mềm CAD, tính toán góc nghiêng 60° và dung sai khớp 0.18 mm.
* **Bước 2:** Cắt lớp trên Bambu Studio (4 wall loops, infill 20% Gyroid) và in FDM trên máy Bambu Lab A1.
* **Bước 3:** Xử lý cơ khí, mài nhẵn bavia và ráp thử nghiệm độ khít của chuỗi khớp cầu.
* **Bước 4:** Luồn dây dẫn điện chìm bên trong cổ đèn và cố định vòng LED vào chao đèn.
* **Bước 5:** Hàn nối mạch ngoại vi, bọc co nhiệt cách điện và bố trí linh kiện vào thân hộp.
* **Bước 6:** Nạp firmware, kiểm thử chức năng và hiệu chuẩn hệ số đo ADC.

---

### 10. KẾT QUẢ KIỂM THỬ THỰC NGHIỆM
| Hạng mục kiểm thử | Tiêu chuẩn đánh giá | Kết quả thực nghiệm thực tế | Đánh giá |
| :--- | :--- | :--- | :---: |
| **Độ vững cơ khí** | Đứng vững, không lật khi uốn cổ đèn nghiêng | Trọng tâm thấp, đứng rất vững chãi trên mặt bàn | **ĐẠT (Tốt)** |
| **Cổ đèn khớp cầu** | Xoay đa hướng 360°, giữ nguyên góc chiếu | Khớp ma sát êm ái, định hình chao đèn chuẩn xác | **ĐẠT (Tốt)** |
| **Màn hình ST7789** | Hiển thị sắc nét, không sọc, không giật hình | Giao diện mượt mà qua bus SPI tần số cao 40MHz | **ĐẠT (Tốt)** |
| **Phím bấm vật lý** | Nhận lệnh chính xác, không bị dội phím | Cả 3 nút bấm phản hồi tốt, phân biệt nhấn giữ | **ĐẠT (Tốt)** |
| **Điều chỉnh đèn LED** | Chỉnh màu HEX vô cấp, độ sáng phản hồi tức thời | Vuốt thanh trượt đèn thay đổi ngay (Throttle 50ms) | **ĐẠT (Xuất sắc)** |
| **Còi báo & MIDI** | Phát âm thanh to rõ, phát nốt nhạc đúng cao độ | Phát tốt các bài nhạc 8-bit và âm báo thức | **ĐẠT (Tốt)** |
| **Kết nối IoT & MQTT** | Nhận lệnh từ app/Discord với độ trễ < 200ms | Tự động kết nối lại khi mất mạng, độ trễ ~ 80ms | **ĐẠT (Tốt)** |
| **Khối sạc & Đo pin** | Đo điện áp và tự ngắt sạc khi đầy pin | Mạch TP4056 và ADC hoạt động tốt; (Cell pin hỏng chưa kịp mua thay, đang cắm điện trực tiếp 5V) | **Đang nâng cấp (Chạy 5V)** |
| **Nhiệt độ hoạt động** | Chạy liên tục 12 tiếng không biến dạng nhựa | Nhiệt độ vỏ duy trì $\le 38^\circ\text{C}$, an toàn tuyệt đối | **ĐẠT (An toàn)** |

---

### 11. TÍNH MỚI, HẠN CHẾ & HƯỚNG PHÁT TRIỂN
* **Tính sáng tạo:** Kết hợp tâm lý học hành vi (giải toán chống lười) với công nghệ IoT; điều khiển thanh trượt đèn thời gian thực mượt mà không độ trễ.
* **Hạn chế & Hướng khắc phục:**
  1. Thay thế cell pin Lithium 18650 mới có dung lượng cao (2600-3000 mAh).
  2. Bổ sung cảm biến ánh sáng môi trường tự động cân chỉnh độ rọi bảo vệ mắt.
  3. Bổ sung cảm biến siêu âm phát hiện khoảng cách ngồi học, phát cảnh báo chống ngồi sai tư thế, chống gù lưng và cận thị.

---

### 12. KẾT LUẬN & CAM KẾT TÁC QUYỀN
Đề tài **DeskFlow – Trạm học tập thông minh tích hợp đèn bàn công thái học IoT** là kết quả của quá trình say mê nghiên cứu, tìm tòi và tự tay thực hiện của học sinh **Khương Hữu Minh Quân (Lớp 8A6)**.

Em xin cam đoan đề tài này do chính bản thân em tự nghiên cứu, viết mã nguồn, thiết kế 3D và lắp ráp mạch điện dưới sự hướng dẫn của thầy cô giáo và sự hỗ trợ động viên từ gia đình. Toàn bộ các số liệu và kết quả thử nghiệm trong bản thuyết minh này là hoàn toàn trung thực.

*Hạ Long, ngày 12 tháng 11 năm 2026*  
**Tác giả đề tài**  
*(Ký và ghi rõ họ tên)*  

**Khương Hữu Minh Quân**  
*Học sinh Lớp 8A6*
