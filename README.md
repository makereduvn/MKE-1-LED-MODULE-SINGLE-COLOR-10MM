# Mạch LED đơn MKE-M01 1-LED 10mm RGYBW Module

## Giới thiệu sản phẩm
MKE-M01 1-LED 10mm RGYBW Module là mạch LED đơn sử dụng LED kích thước lớn 10mm, cho độ sáng cao và hiệu ứng thị giác rõ ràng. Sản phẩm rất phù hợp để làm đèn báo trạng thái, mô hình robot, sản phẩm STEM, đồ án học tập và trang trí sáng tạo. Mạch có 5 phiên bản màu sắc gồm: Đỏ, Xanh lá, Vàng, Xanh dương và Trắng, giúp người dùng dễ dàng lựa chọn theo nhu cầu ứng dụng.

Mạch LED đơn MKE-M01 1-LED 10mm RGYBW Module hỗ trợ điện áp điều khiển 3.3/5VDC, cho phép kết nối trực tiếp và an toàn với hầu hết các bo mạch điều khiển phổ biến hiện nay như: Arduino, Raspberry Pi, Jetson Nano, Micro:bit,… Mạch đi kèm cáp kết nối 3P XH2.54–Dupont đảm bảo chắc chắn, ổn định và linh hoạt khi kết nối.

## Thông số kỹ thuật

- Điện áp cấp nguồn: 5VDC
- Chuẩn tín hiệu điều khiển: Digital
- Điện áp giao tiếp: TTL 3.3/5VDC
- Màu sắc LED: Đỏ, Xanh lá, Vàng, Xanh dương, Trắng
- Loại LED: LED đơn sắc đường kính 10mm
- Mạch bảo vệ:
  - Tích hợp transistor giúp giảm dòng tiêu thụ
  - Bảo vệ an toàn cho chân GPIO của vi điều khiển
- Khả năng tương thích:
  - Arduino
  - Raspberry Pi
  - Jetson Nano
  - Micro:bit
  - Và các board điều khiển 3.3/5VDC khác
- Thiết kế mạch:
  - Ổn định, chống nhiễu
  - Phù hợp cho ứng dụng học tập và thực tế
- Đi kèm cáp kết nối: 3P XH2.54–Dupont
## Hình ảnh sản phẩm

## Kích thước sản phẩm

## Các chân tín hiệu
<table><thead>
  <tr>
    <th>MKE-M01</th>
    <th>Ghi chú</th>
  </tr></thead>
<tbody>
  <tr>
    <td>GND</td>
    <td>Chân cấp nguồn âm 0VDC</td>
  </tr>
  <tr>
    <td>5V</td>
    <td>Chân cấp nguồn dương 5VDC</td>
  </tr>
  <tr>
    <td>SIG</td>
    <td>Chân tín hiệu điều khiển DIGITAL IN</td>
  </tr>
</tbody>
</table>

<table><thead>
  <tr>
    <th>SIG (DIGITAL IN)</th>
    <th>Trạng thái</th>
  </tr></thead>
<tbody>
  <tr>
    <td>TTL HIGH</td>
    <td>Hoạt động (On)</td>
  </tr>
  <tr>
    <td>TTL LOW</td>
    <td>Không hoạt động (Off)</td>
  </tr>
</tbody>
</table>

## Hướng dẫn sử dụng
### Hướng dẫn kết nối
- Cấp nguồn 5VDC cho mạch qua hai chân GND và 5V.
- Điều khiển đèn Led sáng, tắt qua chân tín hiệu SIG.
<table><thead>
  <tr>
    <th>SIG (DIGITAL IN)</th>
    <th>Trạng thái</th>
  </tr></thead>
<tbody>
  <tr>
    <td>TTL HIGH (3.3/5VDC)</td>
    <td>Hoạt động (On)</td>
  </tr>
  <tr>
    <td>TTL LOW (0VDC)</td>
    <td>Không hoạt động (Off)</td>
  </tr>
</tbody>
</table>

### Hướng dẫn sử dụng với Arduino Uno / Vietduino Uno

- Trong **Tools / Library Manager**, tìm và cài đặt bộ thư viện tổng hợp **"MKE_ONE" by MakerEdu.vn**
- Mở chương trình mẫu **"MKE_M01_1_LED_Serial_Uno"** tại **File / Examples / MAKEREDU / Module / MKE_M01_1_LED**
- Chọn board là **Arduino Uno**, chọn đúng cổng **COM Port** của mạch và tiến hành nạp chương trình.
- Kết nối 

### Hướng dẫn lập trình với mBlock (kéo thả khối)

[Hướng dẫn cài đặt phần mềm, nạp chương trình, cài đặt Extension mBlock cơ bản.](https://github.com/makerlabvn/mBlock-MakerEdu-Creator)

- Tải và cài đặt phần mềm mBlock 5 ([Windows](https://www.mediafire.com/file/ma55iajd7glwmbo/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Windows.zip/file) / [Mac Intel](https://www.mediafire.com/file/pjfngy6d7ktb55f/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_Intel.zip/file) / [Mac M1M2](https://www.mediafire.com/file/mfdkgpgnpa7uv2s/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_M1M2.zip/file))
- Thêm Device **"MakerEdu Creator"** by MakerEduVN
- Thêm Extension **"Upload Mode Broadcast"** by mBlock Official
- Thêm Extension **"MakerEdu Hardware"** by MakerEduVN
- Mở [chương trình mẫu tại đây](/mBlock5), kết nối MakerEdu Creator với máy tính và nạp chương trình.
- Kết nối **Module LED** vào cổng **[D10]** và **màn hình LCD** vào cổng **[I2C]** trên MakerEdu Creator, **cấp nguồn qua cổng USB** của MakerEdu Creator để thấy chương trình hoạt động.

### Hướng dẫn lập trình với Micro:bit (kéo thả khối)

[Hướng dẫn nạp chương trình, cài đặt Extension Micro:bit cơ bản.](https://github.com/makerlabvn/MakeCode-microbit)

- Khởi động phần mềm MakeCode tại: [https://makecode.microbit.org/](https://makecode.microbit.org/)
- Chọn **My Projects / Import / Import URL** theo đường link của chương trình mẫu:

      https://github.com/devmakerlabvn/makecode-mke-m01-single-led-module

- Kết nối **Micro:bit với máy tính** và **nạp chương trình**.
- Kết nối mạch **Micro:bit với MakerEdu Shield**, kết nối **Module LED tại cổng [P0]** và **màn hình LCD vào cổng [I2C] trên MakerEdu Shield**, **cấp nguồn qua cổng USB của MakerEdu Shield** để thấy chương trình hoạt động.

## Hỗ trợ và liên hệ

- Website: [https://www.makerlab.vn/](https://www.makerlab.vn/)
- Facebook: [https://www.facebook.com/makerlabvn](https://www.facebook.com/makerlabvn)

## Nhà phân phối

- Các bạn có thể mua sản phẩm của MakerLab tại các [Nhà Phân Phối.](https://www.makerlab.vn/distributor/)
