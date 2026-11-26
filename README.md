# Compact Circular Polarized Antenna for RFID Reader Application

## 1. Bài toán & Quy chuẩn

- **Tần số trung tâm:** **`925.00 MHz`** (UHF RFID / LPWAN sub-GHz, `λ₀ ≈ 324.1 mm`).
- **Giới hạn thể tích:** **`60.0 × 60.0 × 40.0 mm`**.
- **Mục tiêu hiệu năng:** Đạt **`GainTotal(+Z) ≥ +6.00 dBi`**, phân cực tròn thuần khiết **IEEE RHCP** (`Axial Ratio ≤ 1.5 dB`, `XPD ≥ +20 dB`), **`S11`** tại `925 MHz`.
- **Điều kiện mô phỏng thực tế (Real-World Audit):**
  - **Đơn anten (`NoArray`)**, 1 cổng cấp nguồn đồng trục `50 Ω`.
  - **100% đồng thực** (`copper`), **`0` bề mặt `Perfect E`**.
  - **Tối giản BOM (`Pure-C`):** Chỉ dùng **duy nhất 1 giá trị tụ dán chuẩn E24** ở nhánh phối hợp trở kháng (`RLC` song song đối xứng), loại bỏ toàn bộ cuộn cảm rời và điện trở bổ trợ.
  - Kiểm toán bảo toàn thông lượng cầu xa **`Sphere Mean(D_lin) ∈ [0.985, 1.015]`** và **`ValidateDesign = 1`**.
