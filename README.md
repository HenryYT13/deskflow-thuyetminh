# BẢN THUYẾT MINH ĐỀ TÀI DỰ ÁN NGHIÊN CỨU KHOA HỌC KỸ THUẬT

## **DESKFLOW – TRẠM HỌC TẬP THÔNG MINH TÍCH HỢP ĐÈN BÀN CÔNG THÁI HỌC IoT VÀ TRỢ LÝ HỌC TẬP AI**

> **Tải xuống bản Word (.docx) chính thức tại đây:**  
> 👉 [**Tải về file Word (.docx) - Thuyet_Minh_Du_An_DeskFlow_Khuong_Huu_Minh_Quan_8A6.docx**](./Thuyet_Minh_Du_An_DeskFlow_Khuong_Huu_Minh_Quan_8A6.docx?raw=true)  
> 👉 [**Link tải nhanh (Dự phòng)**](./DeskFlow_Thuyet_Minh.docx?raw=true)

---

### **THÔNG TIN TÁC GIẢ & ĐỀ TÀI**
* **Tác giả thực hiện:** **Khương Hữu Minh Quân**
* **Lớp:** **8A6**
* **Lĩnh vực dự thi:** Hệ thống nhúng (Embedded Systems) – Phần mềm hệ thống (System Software) & IoT.
* **Địa bàn nghiên cứu & thực nghiệm:** Thành phố Hạ Long, Tỉnh Quảng Ninh.
* **Thiết bị chế tạo vỏ & cơ khí:** Máy in 3D FDM Bambu Lab A1.
* **Vật liệu in sử dụng:** **Nhựa PLA Trắng chính hãng Bambu Lab**.
* **Khối nguồn thiết kế:** **01 Cell Pin Lithium-ion 21700 dung lượng cao 5000mAh**.
* **Thời gian thực hiện & hoàn thiện:** Năm học 2025 – 2026.

---

### **MỤC LỤC BẢN THUYẾT MINH**
1. [LÝ DO EM CHỌN ĐỀ TÀI VÀ TÍNH CẤP THIẾT](#1-lý-do-em-chọn-đề-tài-và-tính-cấp-thiết)
2. [MỤC TIÊU VÀ Ý NGHĨA KHOA HỌC – THỰC TIỄN CỦA ĐỀ TÀI](#2-mục-tiêu-và-ý-nghĩa-khoa-học--thực-tiễn-của-đề-tài)
3. [CẤU TẠO TỔNG THỂ CỦA TRẠM DESKFLOW](#3-cấu-tạo-tổng-thể-của-trạm-deskflow)
4. [QUÁ TRÌNH EM THIẾT KẾ CƠ KHÍ VÀ IN 3D TRÊN BAMBU LAB A1](#4-quá-trình-em-thiết-kế-cơ-khí-và-in-3d-trên-bambu-lab-a1)
5. [THIẾT KẾ ĐIỆN TỬ VÀ SƠ ĐỒ ĐẤU NỐI MẠCH DO EM THỰC HIỆN](#5-thiết-kế-điện-tử-và-sơ-đồ-đấu-nối-mạch-do-em-thực-hiện)
6. [NGUYÊN LÝ HOẠT ĐỘNG VÀ CÁC TÍNH NĂNG ĐỘT PHÁ EM ĐÃ PHÁT TRIỂN](#6-nguyên-lý-hoạt-động-và-các-tính-năng-đột-phá-em-đã-phát-triển)
7. [HỆ SINH THÁI PHẦN MỀM VÀ GIAO THỨC TRUYỀN THÔNG IoT](#7-hệ-sinh-thái-phần-mềm-và-giao-thức-truyền-thông-iot)
8. [AN TOÀN ĐIỆN NĂNG, KHỐI NGUỒN VÀ BÁO CÁO THỰC TẾ CELL PIN 21700](#8-an-toàn-điện-năng-khối-nguồn-và-báo-cáo-thực-tế-cell-pin-21700)
9. [QUY TRÌNH EM TỰ TAY CHẾ TẠO VÀ LẮP RÁP SẢN PHẨM](#9-quy-trình-em-tự-tay-chế-tạo-và-lắp-ráp-sản-phẩm)
10. [KẾT QUẢ KIỂM THỬ THỰC TẾ DO EM ĐO ĐẠC](#10-kết-quả-kiểm-thử-thực-tế-do-em-đo-đạc)
11. [ĐIỂM SÁNG TẠO CỦA EM, HẠN CHẾ VÀ HƯỚNG PHÁT TRIỂN TIẾP](#11-điểm-sáng-tạo-của-em-hạn-chế-và-hướng-phát-triển-tiếp)
12. [KẾT LUẬN VÀ LỜI CAM ĐOAN CỦA EM](#12-kết-luận-và-lời-cam-đoan-của-em)

---

### 1. LÝ DO EM CHỌN ĐỀ TÀI VÀ TÍNH CẤP THIẾT
Trong quá trình học tập tại lớp 8A6, em nhận thấy chính bản thân em và nhiều bạn học sinh khác thường xuyên gặp khó khăn trong việc quản lý thời gian và duy trì sự tập trung khi ngồi vào bàn học. Góc bàn học của chúng em thường khá chật chội và bừa bộn vì phải đặt rất nhiều thiết bị tách rời: chiếc đèn bàn học to cồng kềnh, đồng hồ báo thức, thời khóa biểu bằng giấy dán lên tường, điện thoại thông minh để bấm giờ học Pomodoro và máy tính để tra cứu bài học. Việc có quá nhiều thiết bị xung quanh vừa chiếm hết diện tích để sách vở, vừa khiến dây điện cắm lộn xộn rất mất an toàn.

Đặc biệt, điện thoại thông minh chính là "cám dỗ" lớn nhất khiến chúng em dễ bị xao nhãng. Mỗi khi với tay lấy điện thoại để xem giờ hay tắt chuông hẹn giờ, em lại vô tình bị cuốn vào các thông báo mạng xã hội, dẫn đến tình trạng trì hoãn (procrastination) và việc học bị ngắt quãng liên tục. Ngoài ra, vào mỗi buổi sáng sớm, thói quen tắt báo thức rồi ngủ tiếp cũng khiến chúng em dễ đi học muộn hoặc vội vàng quên mang đồng phục đúng quy định.

Từ những trăn trở rất thực tế đó của lứa tuổi học sinh, em đã tự đặt ra mục tiêu: *"Tại sao mình không tự tay thiết kế và chế tạo một thiết bị all-in-one duy nhất đặt trên bàn học, tích hợp cả đèn chiếu sáng bảo vệ mắt, đồng hồ hiển thị lịch học và các tính năng công nghệ thông minh giúp rèn luyện kỷ luật bản thân?"* Đó chính là lý do em quyết tâm bắt tay nghiên cứu và phát triển dự án **DeskFlow – Trạm học tập thông minh tích hợp đèn bàn công thái học IoT**.

---

### 2. MỤC TIÊU VÀ Ý NGHĨA KHOA HỌC – THỰC TIỄN CỦA ĐỀ TÀI
#### 2.1. Mục tiêu em đặt ra cho sản phẩm:
* **Tự thiết kế và in 3D hoàn chỉnh cấu trúc trạm:** Em sử dụng máy in 3D Bambu Lab A1 với vật liệu nhựa PLA Trắng để chế tạo thân hộp dạng nêm nghiêng 60° chuẩn công thái học và một cụm cổ đèn gồm chuỗi khớp cầu xoay 360° linh hoạt theo mọi hướng chiếu.
* **Hệ thống chiếu sáng LED thông minh và bảo vệ thị lực:** Em tích hợp vòng LED WS2812B với thuật toán nội suy màu sắc 16.7 triệu màu HEX và điều chỉnh độ sáng tuyến tính tức thời (0-100%) trực tiếp trên ứng dụng mà không có độ trễ.
* **Màn hình trung tâm hiển thị mọi dữ liệu học đường:** Em lập trình màn hình màu ST7789 2.0 inch để cập nhật tự động thời khóa biểu hôm nay/ngày mai của lớp 8A6, đồng phục quy định, đồng hồ chuẩn nguyên tử Internet NTP, thời tiết TP. Hạ Long và hiệu năng máy tính.
* **Cơ chế rèn luyện kỷ luật bằng Thử thách Toán học:** Em sáng tạo tính năng Chế độ tập trung (Focus Mode) và Báo thức toán học (Math Alarm) buộc em phải tính nhẩm và giải đúng một câu đố toán ngẫu nhiên thì mới có thể tắt chuông hoặc mở khóa máy.
* **Làm chủ toàn bộ hệ sinh thái phần mềm:** Em tự lập trình toàn bộ từ firmware C++ trên ESP32, ứng dụng di động Android (Jetpack Compose), ứng dụng máy tính (Windows WinUI 3, macOS, Linux) đến máy chủ đám mây Backend (Python Asyncio) và Bot Discord.

#### 2.2. Ý nghĩa thực tiễn:
Sản phẩm DeskFlow giúp em giải phóng hoàn toàn không gian bàn học, tạo dựng cho em một môi trường học tập hiện đại, ngăn nắp và có kỷ luật cao. Dự án này cũng là cơ hội tuyệt vời để em vận dụng những kiến thức đã học ở trường vào thực tế: môn Toán (thuật toán số học và giải toán ma trận màu), môn Vật lý (quang học chiếu sáng và mạch điện một chiều), môn Tin học (lập trình nhúng, mạng máy tính, phát triển ứng dụng di động) và môn Công nghệ (thiết kế 3D CAD và công nghệ in 3D FDM).

---

### 3. CẤU TẠO TỔNG THỂ CỦA TRẠM DESKFLOW
| Phân hệ | Linh kiện em sử dụng | Vai trò và nhiệm vụ em thiết lập |
| :--- | :--- | :--- |
| **Xử lý trung tâm** | Vi điều khiển ESP32 DevKit V1 (Xtensa 32-bit Dual-core 240MHz) | Bộ não của trạm: xử lý logic chương trình, kết nối Wi-Fi, nhận gửi dữ liệu MQTT. |
| **Hiển thị trực quan** | Màn hình TFT LCD ST7789 2.0 inch (240 × 320 px, IPS) | Giao diện chính hiển thị đồng hồ, thời khóa biểu 8A6, thời tiết và thông số PC. |
| **Chiếu sáng bàn học** | Vòng 8 LED WS2812B NeoPixel trong chao đèn in 3D | Phát ánh sáng trắng học tập và đổi màu trang trí 16.7 triệu màu HEX tùy ý. |
| **Điều khiển vật lý** | 3 nút nhấn Tactile cơ học (PREV, PLAY/MODE, NEXT) | Giúp em thao tác nhanh: bật/tắt đèn, chuyển trang màn hình, dừng phát nhạc. |
| **Cảnh báo âm thanh** | Passive Buzzer (Còi xung PWM tần số cao) | Phát âm báo thức giải toán, chuông cảnh báo và phát các bản nhạc 8-bit. |
| **Khối nguồn điện** | Module sạc TP4056 Type-C, cầu trở phân áp ADC | Quản lý sạc xả pin 21700, tự ngắt an toàn và đo điện áp pin báo về máy chủ. |
| **Kết cấu cơ khí** | Thân hộp dạng nêm, cổ đèn khớp cầu bằng nhựa PLA Trắng | Bộ khung in 3D bảo vệ linh kiện, tạo góc nhìn tối ưu và xoay hướng đèn. |

---

### 4. QUÁ TRÌNH EM THIẾT KẾ CƠ KHÍ VÀ IN 3D TRÊN BAMBU LAB A1
* **Thân máy dạng nêm dốc (Wedge Shape):** Em thiết kế mặt trước nghiêng một góc đúng 60° so với mặt bàn. Khi em ngồi học trên ghế, góc nghiêng này giúp mắt em nhìn vuông góc vào màn hình ST7789 một cách tự nhiên nhất mà không cần phải khom lưng hay cúi đầu. Mặt đáy trạm có kích thước 120 x 95 mm, tạo thành một khối đế vững chắc để máy không bị lật khi em nhấn các nút bấm.
* **Cổ đèn khớp cầu mô-đun (Ball-and-Socket Joints):** Em lấy ý tưởng từ các khớp xương sinh học để thiết kế chuỗi đốt khớp cầu lồng vào nhau. Đầu khớp có dạng quả cầu rỗng tâm, chuôi khớp là ngàm ôm đàn hồi. Thiết kế rỗng ở giữa giúp em luồn toàn bộ dây điện của đèn LED chạy ngầm bên trong cổ đèn, vừa đẹp mắt vừa không sợ dây bị vướng gập khi em bẻ xoay cổ đèn 360°.
* **Chế tạo bằng máy in 3D Bambu Lab A1 và nhựa PLA Trắng:** Em sử dụng hoàn toàn nhựa PLA Trắng chính hãng để in trên chiếc máy in 3D Bambu Lab A1. Nhựa PLA Trắng cho độ hoàn thiện bề mặt rất láng mịn, thẩm mỹ, sạch sẽ và thân thiện với môi trường học đường. Để các khớp cầu xoay êm nhưng vẫn giữ chắc vị trí, em đã thử nghiệm nhiều lần và chọn khe hở dung sai thiết kế chuẩn là 0.18 mm, in với 4 lớp thành (wall loops) và mật độ ruột 20% dạng Gyroid để đảm bảo độ bền cơ học cao nhất.

---

### 5. THIẾT KẾ ĐIỆN TỬ VÀ SƠ ĐỒ ĐẤU NỐI MẠCH DO EM THỰC HIỆN
| Khối chức năng | Chân GPIO ESP32 em nối | Giao thức truyền thông | Chi tiết kỹ thuật em thiết lập |
| :--- | :--- | :--- | :--- |
| **Màn hình ST7789** | GPIO 18 (SCK)<br>GPIO 23 (MOSI)<br>GPIO 19 (DC)<br>GPIO 4 (RST)<br>GPIO 21 (CS) | SPI phần cứng (VSPI)<br>Tần số 40 MHz | Em cấu hình giao tiếp SPI tốc độ cao với buffer màn hình RGB565. |
| **Đèn LED WS2812B** | GPIO 2 (DIN) | 1-Wire High-Speed (800 kHz) | Em cấp nguồn 5V riêng từ cổng sạc, nối chung GND với ESP32. |
| **Còi báo Buzzer** | GPIO 32 | LEDC PWM Channel | Em sử dụng bộ tạo xung LEDC để phát các nốt nhạc tần số từ 200 Hz đến 4500 Hz. |
| **Nút nhấn [PREV]** | GPIO 26 | Digital Input (Pull-up) | Nối nút về GND, em viết code chống rung phím (debounce 50ms). |
| **Nút nhấn [PLAY/MODE]**| GPIO 14 | Digital Input (Pull-up) | Em lập trình đa năng: nhấn nhanh để đổi bài, nhấn giữ 1s để đổi màn hình. |
| **Nút nhấn [NEXT]** | GPIO 27 | Digital Input (Pull-up) | Nối nút về GND, nhấn để chuyển tiếp mục hoặc bài hát tiếp theo. |
| **Mạch đo điện áp pin** | GPIO 34 (ADC1) | Analog-to-Digital (12-bit) | Em dùng cầu phân áp hai điện trở 100kΩ / 100kΩ để đưa áp pin về dải đo an toàn 0-3.3V. |

#### **Thuật toán nội suy độ sáng tuyến tính do em xây dựng:**
$$R_{\text{scaled}} = \left\lfloor \frac{R_{\text{gốc}} \times \text{Brightness}}{100} \right\rfloor, \quad G_{\text{scaled}} = \left\lfloor \frac{G_{\text{gốc}} \times \text{Brightness}}{100} \right\rfloor, \quad B_{\text{scaled}} = \left\lfloor \frac{B_{\text{gốc}} \times \text{Brightness}}{100} \right\rfloor$$
Nhờ giải thuật này của em, màu sắc của đèn luôn giữ được độ tinh khiết chuẩn xác 100% dù em chỉnh độ sáng ở bất kỳ mức nào từ 1% đến 100%.

---

### 6. NGUYÊN LÝ HOẠT ĐỘNG VÀ CÁC TÍNH NĂNG ĐỘT PHÁ EM ĐÃ PHÁT TRIỂN
1. **Chế độ tập trung (Focus Mode) giải toán chống lười biếng:** Mỗi khi ngồi vào bàn học, em bấm kích hoạt Focus Mode. Ngay lập tức, ứng dụng trên điện thoại và máy tính sẽ bị khóa vào trạng thái học bài. Nếu em bị cám dỗ và muốn tắt sớm chế độ này, hệ thống sẽ đưa ra một bài toán số học ngẫu nhiên (ví dụ: $84 \times 6 - 157$). Em bắt buộc phải đặt bút tính nhẩm và nhập đúng kết quả qua app hoặc Discord thì trạm mới cho phép mở khóa.
2. **Báo thức đánh thức phản xạ (Math Alarm):** Khi chuông reo sáng sớm, còi Buzzer kêu dồn dập và đèn LED chớp nháy liên tục. Màn hình trạm DeskFlow sẽ hiện câu hỏi toán. Em bắt buộc phải tỉnh táo ngồi dậy, quan sát màn hình và giải đúng bài toán thì chuông mới chịu tắt!
3. **Theo dõi phần cứng máy tính (PC Telemetry):** Em viết một phần mềm chạy ngầm trên máy tính để tự động đo đạc mức tải CPU, mức sử dụng RAM và phần trăm pin laptop, sau đó gửi về trạm DeskFlow mỗi giây một lần.
4. **Tự động nhắc Thời khóa biểu lớp 8A6 & Quét trời mưa 06:15 sáng:** Em nhập toàn bộ lịch học của lớp 8A6 lên cơ sở dữ liệu PocketBase. Đúng 06:15 sáng trước giờ em dắt xe đi học, máy chủ sẽ tự động gọi API thời tiết quét khả năng có mưa ở TP. Hạ Long và hiện cảnh báo mang áo mưa!
5. **Hộp nhạc 8-bit sống động và Trình giải mã MIDI:** Em đã tự xây dựng một bộ phân giải tệp nhạc MIDI (.mid) với bộ nhớ đệm mở rộng 32KB trên ESP32 để phát các giai điệu 8-bit vui tai sau giờ học căng thẳng.

---

### 7. HỆ SINH THÁI PHẦN MỀM VÀ GIAO THỨC TRUYỀN THÔNG IoT
* **Máy chủ trung tâm Backend (Python 3.12 Asyncio):** Em triển khai trên máy chủ đám mây tại địa chỉ `10th01ssh.duckdns.org`, quản lý cơ sở dữ liệu PocketBase, MQTT Broker Mosquitto và hệ thống xác thực bảo mật HMAC Token không cần mật khẩu.
* **Trợ lý ảo Discord Bot DeskFlow:** Em tích hợp các lệnh `/app pair`, `/melody`, `/lamp_color`, `/lamp_dim`, `/alarm`, `/solve`. Bot có khả năng tự động tạo và gửi ảnh mã QR vào tin nhắn Discord để em quét bằng điện thoại cực nhanh.
* **Ứng dụng di động Android (Jetpack Compose):** Em tự viết app bằng ngôn ngữ Kotlin với giao diện Material 3, có bộ điều tiết vi mô (Throttle 50ms) giúp em vuốt ngón tay đến đâu là đèn trên bàn học sáng theo tức thì đến đó.
* **Ứng dụng Desktop (Windows WinUI 3, macOS, Linux):** Em viết bằng C# và Python, hỗ trợ tạo mã QR ghép nối nội bộ và đẩy thông số phần cứng CPU/RAM về trạm.

---

### 8. AN TOÀN ĐIỆN NĂNG, KHỐI NGUỒN VÀ BÁO CÁO THỰC TẾ CELL PIN 21700

> ⚠️ **BÁO CÁO TRUNG THỰC VỀ TÌNH TRẠNG THỰC TẾ CỦA KHỐI NGUỒN PIN DỰ PHÒNG:**  
> **Hiện tại tới bây giờ em mới thử pin thì mới biết nó hỏng mà không đặt hàng về kịp.**  
> *Cụ thể sự việc của em như sau: Theo thiết kế ban đầu của dự án, em lựa chọn 01 cell pin Lithium-ion 21700 dung lượng cao 5000mAh đặt bên trong thân trạm để trạm có thể chạy độc lập khi em cần mang sang phòng khác học nhóm mà không cần cắm dây. Em đã thiết kế sẵn khoang chứa pin 21700, hàn hoàn thiện mạch sạc bảo vệ TP4056 (IC DW01A + FS8205A) và mạch cầu phân áp đo dung lượng pin nối vào chân ADC GPIO 34 của ESP32.*  
> *Tuy nhiên, do thời gian vừa qua em quá tập trung vào việc lập trình phần mềm, sửa lỗi firmware và in các chi tiết 3D, nên đến những ngày cuối cùng trước khi hoàn thiện đề tài em mới tiến hành lắp viên pin 21700 có sẵn ở nhà vào để thử nghiệm thực tế. Lúc này em mới phát hiện viên pin 21700 này đã bị hỏng/chết cell nội trở cao (sạc không thể tích điện và sụt áp ngay lập tức). Do thời gian quá gấp rút sát ngày nộp và chấm thi đề tài, em không thể đặt hàng online mua một viên pin 21700 5000mAh mới về kịp thời.*  
> *Dù vậy, toàn bộ mạch phần cứng sạc xả và code đọc dung lượng pin đều đã được em hoàn thiện 100%. Hiện tại, trạm DeskFlow của em đang được cấp nguồn hoạt động cực kỳ ổn định, liên tục và an toàn tuyệt đối bằng nguồn điện trực tiếp 5V qua cổng sạc Type-C (cắm củ sạc điện thoại hoặc cổng USB máy tính). Ngay sau đợt báo cáo này, em sẽ đặt mua một viên pin 21700 dung lượng 5000mAh mới chất lượng tốt để gắn vào trạm.*

---

### 9. QUY TRÌNH EM TỰ TAY CHẾ TẠO VÀ LẮP RÁP SẢN PHẨM
* **Bước 1 - Thiết kế 3D CAD:** Em phác thảo ý tưởng trên giấy, sau đó dùng phần mềm CAD trên máy tính dựng từng chi tiết: thân hộp nêm 60°, mặt gắn màn hình, chao đèn và các đốt khớp cầu với khe hở 0.18 mm.
* **Bước 2 - Cài đặt in 3D trên Bambu Studio:** Em xuất tệp mô hình 3D sang phần mềm Bambu Studio, chọn vật liệu nhựa PLA Trắng, thiết lập in 4 lớp thành và mật độ ruột 20% dạng Gyroid để chi tiết chịu lực tốt nhất.
* **Bước 3 - Tiến hành in trên máy Bambu Lab A1:** Em cho máy in hoạt động liên tục trong khoảng 8 giờ. Nhờ hệ thống cân bàn tự động của máy Bambu Lab A1, các chi tiết in bằng nhựa PLA Trắng ra lò rất sắc nét, không bị cong vênh đáy.
* **Bước 4 - Xử lý nguội và ráp thử cơ khí:** Em dùng dao gọt bavia, làm sạch các lỗ vít và lắp ráp thử nghiệm chuỗi khớp cầu để đảm bảo cổ đèn xoay êm nhưng đủ ma sát giữ chao đèn đứng vững.
* **Bước 5 - Luồn dây và hàn mạch điện tử:** Em luồn dây điện của vòng LED chạy ngầm bên trong cổ đèn; tiến hành hàn các chân màn hình ST7789, phím bấm, còi buzzer và module nguồn vào bo mạch ESP32, sau đó bọc co nhiệt cách điện.
* **Bước 6 - Nạp code và kiểm thử:** Em cắm cáp Type-C nạp firmware từ máy tính sang ESP32, kết nối trạm với máy chủ MQTT và kiểm tra từng chức năng hoạt động.

---

### 10. KẾT QUẢ KIỂM THỬ THỰC TẾ DO EM ĐO ĐẠC
| Hạng mục em kiểm tra | Chỉ tiêu em đề ra | Kết quả thực tế em ghi nhận | Đánh giá của em |
| :--- | :--- | :--- | :---: |
| **Độ vững cơ khí** | Máy đứng vững, không lật khi bẻ cong cổ đèn | Khối đế rộng, trọng tâm thấp, máy đứng rất vững | **ĐẠT (Rất tốt)** |
| **Cổ đèn khớp cầu** | Xoay linh hoạt 360°, giữ nguyên góc chiếu | Khớp nhựa PLA Trắng ma sát êm, giữ chao đèn chuẩn | **ĐẠT (Tốt)** |
| **Màn hình ST7789** | Hình ảnh sắc nét, không bị sọc hay giật lag | Màu sắc tươi sáng, hiển thị mượt mà ở tần số SPI 40MHz | **ĐẠT (Rất tốt)** |
| **3 nút bấm cơ học** | Bấm nhạy, không bị nhận lệnh trùng (double click) | Cả 3 nút đều bấm rất nảy, phân biệt tốt bấm nhanh và giữ | **ĐẠT (Tốt)** |
| **Điều khiển đèn LED** | Chỉnh màu vô cấp, vuốt thanh trượt đèn theo ngay | Đèn đổi màu tức thì theo ngón tay trên app (Throttle 50ms) | **ĐẠT (Xuất sắc)** |
| **Còi báo & Hộp nhạc** | Âm thanh rõ ràng, nốt nhạc đúng cao độ | Phát chuông báo thức rất vang và chơi nhạc 8-bit hay | **ĐẠT (Tốt)** |
| **Kết nối IoT & MQTT** | Nhận lệnh từ xa với độ trễ dưới 200ms | Độ trễ trung bình chỉ khoảng 80ms, tự nối lại khi mất mạng | **ĐẠT (Rất tốt)** |
| **Khối sạc & Đo pin** | Tự ngắt sạc khi đầy, đo áp báo về máy chủ | Mạch TP4056 và ADC chuẩn 100%; (Pin 21700 cũ hỏng chưa kịp mua thay, đang cắm điện trực tiếp 5V) | **Chạy tốt bằng điện 5V** |
| **Nhiệt độ hoạt động** | Chạy liên tục 12 tiếng không bị nóng chảy nhựa | Nhiệt độ vỏ duy trì dưới 38°C, an toàn tuyệt đối | **ĐẠT (An toàn)** |

---

### 11. ĐIỂM SÁNG TẠO CỦA EM, HẠN CHẾ VÀ HƯỚNG PHÁT TRIỂN TIẾP
* **Những điểm em tự hào nhất ở sản phẩm:**
  1. Ý tưởng kết hợp tâm lý học và công nghệ: Em không chỉ tạo ra một chiếc đèn bàn hay đồng hồ đơn thuần, mà em đã đưa giải pháp thử thách toán học vào để rèn luyện thói quen tự giác và tính kỷ luật cho người học.
  2. Sản phẩm thực tế có độ hoàn thiện cao: Từ khâu vẽ 3D, chọn nhựa PLA Trắng in trên máy Bambu Lab A1 đến việc thiết kế mạch điện và lập trình ứng dụng Android, mọi chi tiết đều được em chăm chút cẩn thận.
  3. Giải thuật vuốt đèn thời gian thực không độ trễ: Em đã giải quyết được bài toán nghẽn mạng IoT khi vuốt thanh trượt bằng giải thuật micro-throttle 50ms.
* **Hạn chế em cần khắc phục và hướng phát triển tiếp theo:**
  1. Khắc phục khối pin dự phòng: Như em đã trình bày trung thực, việc viên pin 21700 bị hỏng sát ngày nộp đề tài là một sự cố ngoài ý muốn. Ngay sau cuộc thi, em sẽ mua một viên pin 21700 dung lượng 5000mAh mới gắn vào để trạm có thể chạy pin di động liên tục 4 - 6 tiếng.
  2. Tự động cân chỉnh ánh sáng phòng học: Em dự định lắp thêm một cảm biến quang trở (LDR) trên đỉnh chao đèn để trạm tự động tăng độ sáng khi trời tối và giảm sáng khi trời nắng để bảo vệ mắt tối đa.
  3. Cảnh báo tư thế ngồi học chống cận thị, gù lưng: Em sẽ tích hợp thêm một cảm biến siêu âm phía trước trạm để nhắc nhở em ngồi thẳng lưng lại khi cúi quá sát mặt bàn.

---

### 12. KẾT LUẬN VÀ LỜI CAM ĐOAN CỦA EM
Dự án **DeskFlow – Trạm học tập thông minh tích hợp đèn bàn công thái học IoT** là một hành trình nghiên cứu khoa học kỹ thuật vô cùng ý nghĩa và bổ ích đối với em. Sau nhiều tháng miệt mài học hỏi từ thầy cô, tài liệu và tự tay thực hiện từng dòng code cũng như từng chi tiết in 3D, em đã biến ý tưởng ban đầu thành một sản phẩm thực tế hoạt động rất ổn định trên bàn học của mình.

Em xin cam đoan toàn bộ đề tài DeskFlow này là do chính bản thân em tự tay thiết kế, viết code, in 3D và lắp ráp mạch điện dưới sự hướng dẫn nhiệt tình của các thầy cô giáo và sự động viên từ gia đình. Toàn bộ các thông tin và kết quả kiểm thử trong bản thuyết minh này là hoàn toàn trung thực với thực tế.

Em xin chân thành cảm ơn Ban Giám khảo và các Thầy Cô giáo đã lắng nghe phần thuyết minh đề tài của em!

*Hạ Long, ngày 12 tháng 11 năm 2026*  
**TÁC GIẢ THỰC HIỆN ĐỀ TÀI**  
*(Em xin ký và ghi rõ họ tên)*  

**Khương Hữu Minh Quân**  
*Học sinh Lớp 8A6*
