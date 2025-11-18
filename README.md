# BÁO CÁO PHÂN TÍCH CƠ BẢN CHO CÁC DOANH NGHIỆP PHI TÀI CHÍNH

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)](link-neu-co)
[![DAX](https://img.shields.io/badge/DAX-2A3C4F?style=for-the-badge&logo=power-bi&logoColor=white)](link-neu-co)

---

## Mục tiêu
Dự án này tập trung vào việc tự động hóa và trực quan hóa các chỉ số tài chính để đánh giá sức khỏe doanh nghiệp và so sánh hiệu suất giữa các công ty.
### 1. Tự động Phân tích Tình hình Tài chính 
**Mục tiêu:** Tự động hóa việc tính toán, trực quan hóa và theo dõi cơ cấu tài sản, nguồn vốn, doanh thu và các chỉ số tài chính quan trọng nhằm đánh giá khả năng thanh toán, hiệu quả sử dụng tài sản và cấu trúc vốn của doanh nghiệp.
#### 📈 Các Chỉ số Chính trong Báo cáo
* **Khả năng Thanh toán (Liquidity):**
    * Tỷ lệ Thanh toán Hiện hành (Current Ratio)
    * Tỷ lệ Thanh toán Nhanh (Quick Ratio / Acid-test Ratio)
* **Hiệu quả Hoạt động (Efficiency):**
    * Các chỉ tiêu sinh lời (ROE,ROA, ROCE)
    * Tỷ suất lợi nhuận gộp, lợi nhuận thuần 
    * Vòng quay Hàng tồn kho (Inventory Turnover)
    * Vòng quay Khoản phải thu (Accounts Receivable Turnover)
* **Cấu trúc Vốn (Leverage):**
    * Tỷ lệ Nợ trên Tổng Tài sản (Debt to Asset Ratio)
    * Tỷ lệ Nợ trên Vốn chủ sở hữu (Debt to Equity Ratio)
## 🛠️ Bộ Công cụ Sử dụng

* **Phân tích & Trực quan:** Microsoft Power BI
* **Ngôn ngữ:** DAX, Power Query (M)
* **Nguồn Dữ liệu:** 

## 🧹 Tóm tắt Quy trình Xử lý Dữ liệu

1.  **Làm sạch Dữ liệu:** Sử dụng Power Query để tạo pipeline làm sạch dữ liệu, sửa cấu trúc dữ liệu. Tạo ra các bảng Dim và Fact để tiện cho việc phân tích.
2.  **Mô hình hóa Dữ liệu:** Thiết lập các mối quan hệ giữa các bảng.
3.  **Tính toán DAX:** Xây dựng các chỉ số như `CARG`, `Cấu trúc tài sản`, và các tính toán time-intelligence.

## 💡 Kết quả & Phân tích Chính

> Báo cáo này giúp nhà phân tích nhìn nhận rõ ràng về tình hình tài chính của doanh nghiệp.

### Trang Tổng Quan (Dashboard Overview)

(images/dashboard_tong_quan.png)

### Các Phát hiện Chủ chốt (Key Findings)
* **Phát hiện 1:** [Ví dụ: Chi phí Marketing không tương xứng với doanh số ở khu vực X].
* **Phát hiện 2:** [Ví dụ: Sản phẩm A có biên lợi nhuận cao nhất nhưng lại bị tồn kho nhiều nhất].

---

## 🔗 Xem Báo Cáo Trực Tiếp (Tùy chọn)

Nếu bạn đã publish lên Power BI Service:
[Xem báo cáo trên Power BI Service](Link_Embed_hoac_Web_cua_ban)
