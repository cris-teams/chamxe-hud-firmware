# Chăm Xe HUD: phần mềm cập nhật

Bản mới nhất: **1.0.1**

| Loại màn hình (xem ≡ › Thông tin trên HUD) | File |
|---|---|
| 3.5 inch (cyd35) | [chamxe-hud-cyd35-1.0.1.bin](https://github.com/cris-teams/chamxe-hud-firmware/releases/download/v1.0.1/chamxe-hud-cyd35-1.0.1.bin) |
| 2.8 inch (cyd28) | [chamxe-hud-cyd28-1.0.1.bin](https://github.com/cris-teams/chamxe-hud-firmware/releases/download/v1.0.1/chamxe-hud-cyd28-1.0.1.bin) |
| 2.8 inch (cyd28_st7789) | [chamxe-hud-cyd28_st7789-1.0.1.bin](https://github.com/cris-teams/chamxe-hud-firmware/releases/download/v1.0.1/chamxe-hud-cyd28_st7789-1.0.1.bin) |
| 2.4 inch (cyd24) | [chamxe-hud-cyd24-1.0.1.bin](https://github.com/cris-teams/chamxe-hud-firmware/releases/download/v1.0.1/chamxe-hud-cyd24-1.0.1.bin) |

File đã được Chăm Xe ký; HUD từ chối file không chính hãng hoặc sai loại màn hình.
Các bản trước: [Releases](https://github.com/cris-teams/chamxe-hud-firmware/releases).

---

## Cập nhật phần mềm cho Chăm Xe HUD

Có 3 cách, chọn cách nào cũng được. Cài đặt, giao diện và lịch sử chuyến đi của bạn **được giữ nguyên** sau khi cập nhật.

**Trước khi bắt đầu**
- Đỗ xe, để xe đứng yên. HUD không cho cập nhật khi xe đang chạy.
- Giữ HUD cắm điện trong lúc cập nhật (khoảng 1–2 phút).
- Xem phiên bản đang dùng: chạm **≡** (góc phải trên) › **Thông tin**.

---

## Cách 1: Dùng app Chăm Xe (dễ nhất)

1. Mở app **Chăm Xe** trên điện thoại, bật Bluetooth.
2. Trên HUD: **≡ › Thông tin › Cập nhật phần mềm**.
3. Trong app: **Cập nhật HUD**. App tự tìm HUD và gửi bản mới.
4. Chờ HUD báo **"Đã cập nhật"**, HUD tự khởi động lại.

> Cách này có khi app Chăm Xe hỗ trợ "Cập nhật HUD".

## Cách 2: Tự tải qua Wi-Fi nhà (tiện nhất về lâu dài)

**Lần đầu** cần lưu Wi-Fi nhà (hoặc điểm phát Wi-Fi của điện thoại) cho HUD, làm như Cách 3 tới bước 3, rồi ở trang hiện ra chọn mục **"Lần sau tự tải qua Internet"**, chọn tên Wi-Fi và nhập mật khẩu.

**Từ lần sau:**
1. Trên HUD: **≡ › Thông tin › Cập nhật phần mềm**.
2. Chờ vài giây, HUD tự kiểm tra. Có bản mới thì dòng dưới cùng hiện **"Có bản mới …"**.
3. Chạm **Tải …**. Xong thì HUD tự khởi động lại.

> Đỗ xe gần nhà để HUD bắt được Wi-Fi, hoặc bật điểm phát Wi-Fi trên điện thoại.

## Cách 3: Gửi file từ điện thoại (không cần app, không cần Internet trên HUD)

1. Trên điện thoại, tải file phần mềm mới từ trang Chăm Xe. Chọn đúng loại màn hình ghi trong **Thông tin** (ví dụ `chamxe-hud-cyd35-1.1.0.bin` cho màn 3.5 inch).
2. Trên HUD: **≡ › Thông tin › Cập nhật phần mềm**. HUD hiện một mã QR.
3. Dùng camera điện thoại quét mã QR để vào Wi-Fi **ChamXe-HUD-…**. Mã QR trên HUD đổi sang mã thứ hai: quét tiếp (hoặc mở trình duyệt, gõ `192.168.4.1`).
4. Trên trang hiện ra, chọn file vừa tải ở bước 1.
5. Chờ HUD báo **"Đã cập nhật"**, HUD tự khởi động lại. Điện thoại tự quay về Wi-Fi/4G cũ.

---

## Nếu có trục trặc

| HUD báo | Làm gì |
|---|---|
| **File không phải bản chính hãng** | File bị hỏng hoặc không phải của Chăm Xe. Tải lại file từ trang Chăm Xe rồi gửi lại; HUD ở màn cập nhật chờ bạn. |
| **File dành cho màn hình khác** | Chọn file đúng loại màn hình trong **Thông tin**. |
| **Bản … cũ hơn bản đang dùng** | Bạn đang dùng bản mới hơn rồi, không cần làm gì. |
| **Không vào được Internet qua …** | Kiểm tra Wi-Fi nhà / điểm phát, chạm vào dòng đó để thử lại; hoặc dùng Cách 1 hay Cách 3. |
| **Mất điện / rút điện giữa chừng** | Không sao. Cắm lại, HUD tự vào màn cập nhật; gửi lại file là xong. |
| HUD treo, không lên màn hình chính | Rút điện, **giữ ngón tay trên màn hình** rồi cắm điện lại (giữ 3 giây): HUD vào thẳng màn cập nhật. |

Cần giúp: nhắn Zalo OA Chăm Xe kèm ảnh màn hình **Thông tin**.
