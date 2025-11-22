# BÁO CÁO PHÂN TÍCH CƠ BẢN CHO CÁC DOANH NGHIỆP PHI TÀI CHÍNH

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)](link-neu-co)
[![DAX](https://img.shields.io/badge/DAX-2A3C4F?style=for-the-badge&logo=power-bi&logoColor=white)](link-neu-co)

---
## LƯU Ý
Báo cáo này có thể tái sử dụng và cập nhật khi tải về báo cáo tài chính của các công ty phi tài chính cần phân tích từ trang web SSI (https://iboard.ssi.com.vn/analysis/fundamental-analysis) và lưu theo địa chỉ "D:\Thực hành\Bảng cân đối kế toán" ; "D:\Thực hành\Kết quả hoạt động" ; "D:\Thực hành\Lưu chuyển tiền tệ", sau đó refresh báo cáo, không cần load các file data mới vào PBI.

<img width="600" height="200" alt="image" src="https://github.com/user-attachments/assets/b226e024-63d8-4acf-935a-6bf74e3af11b" />
<img width="600" height="200" alt="image" src="https://github.com/user-attachments/assets/2e49afb7-3159-48a1-8fa0-c4f86418871d" />



## Mục tiêu
Dự án này tập trung vào việc tự động hóa và trực quan hóa các chỉ số tài chính để đánh giá sức khỏe doanh nghiệp và so sánh hiệu suất giữa các công ty.
### 1. Tự động Phân tích Tình hình Tài chính 
**Mục tiêu:** Tự động hóa việc tính toán, trực quan hóa và theo dõi cơ cấu tài sản, nguồn vốn, doanh thu và các chỉ số tài chính quan trọng nhằm đánh giá khả năng thanh toán, hiệu quả sử dụng tài sản và cấu trúc vốn của doanh nghiệp.
#### Các Chỉ số Chính trong Báo cáo
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
## Bộ Công cụ Sử dụng

* **Phân tích & Trực quan:** Microsoft Power BI
* **Ngôn ngữ:** DAX, Power Query (M)
* **Nguồn Dữ liệu:** Dữ liệu Báo cáo Tài chính được tải về từ website SSI 

  <img width="1865" height="702" alt="image" src="https://github.com/user-attachments/assets/346c331b-5059-4130-8130-8088ba560dd2" />

## Tóm tắt Quy trình Xử lý Dữ liệu

1.  **Làm sạch Dữ liệu:**
* Sử dụng Power Query để tạo pipeline làm sạch dữ liệu, xử lý các lỗi nhập liệu, và sửa cấu trúc dữ liệu thô (thường là định dạng báo cáo) thành định dạng phân tích (dạng cột).
* Tạo các bảng Dimension (Dim) và Fact (chứa giá trị tài chính) để tiện cho việc phân tích và mô hình hóa.
2.  **Mô hình hóa Dữ liệu:** Thiết lập các mối quan hệ giữa các bảng.
3.  **Tính toán DAX:** Xây dựng các chỉ số như `CARG`, `Cấu trúc tài sản`, và các tính toán time-intelligence.

## Kết quả 
> Báo cáo này giúp nhà phân tích nhìn nhận rõ ràng về tình hình tài chính của doanh nghiệp, đồng thời cung cấp bộ lọc dựa trên F-Score (Chỉ số Piotroski) để nhanh chóng đánh giá chất lượng tài chính của công ty.
### Trang Tổng Quan & Chi tiết Tình hình tài chính

![Tình hình tài chính](images/images/T%C3%ACnh%20h%C3%ACnh%20t%C3%A0i%20ch%C3%ADnh%20-%20T%E1%BB%95ng%20quan.png)
![Tình hình tài chính](images/images/T%C3%ACnh%20h%C3%ACnh%20t%C3%A0i%20ch%C3%ADnh%20-%20Chi%20ti%E1%BA%BFt.png)

### Trang Tổng Quan & Chi tiết Kết quả hoạt động
![Kết quả hoạt động](images/images/K%E1%BA%BFt%20qu%E1%BA%A3%20ho%E1%BA%A1t%20%C4%91%E1%BB%99ng%20-%20T%E1%BB%95ng%20quan.png)
![Kết quả hoạt động](images/images/K%E1%BA%BFt%20qu%E1%BA%A3%20ho%E1%BA%A1t%20%C4%91%E1%BB%99ng%20-%20Chi%20ti%E1%BA%BFt.png)

### Trang Tổng Quan & Chi tiết Lưu chuyển tiền tệ

![Lưu chuyển tiền tệ](images/images/L%C6%B0u%20chuy%E1%BB%83n%20ti%E1%BB%81n%20t%E1%BB%87%20-%20T%E1%BB%95ng%20quan.png)
![Lưu chuyển tiền tệ](images/images/L%C6%B0u%20chuy%E1%BB%83n%20ti%E1%BB%81n%20t%E1%BB%87%20-%20Chi%20ti%E1%BA%BFt.png)

### Trang Bộ lọc công ty dựa trên F-Score

![Bộ lọc công ty](images/images/B%E1%BB%99%20l%E1%BB%8Dc%20c%C3%B4ng%20ty.png)



