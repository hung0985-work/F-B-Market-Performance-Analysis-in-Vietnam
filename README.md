# Phân tích thị trường F&B Việt Nam giai đoạn 2019–2023

## 1. Giới thiệu dự án

Dự án này được thực hiện nhằm phân tích hiệu quả hoạt động và tiềm năng tăng trưởng của các doanh nghiệp trong ngành F&B tại Việt Nam trong giai đoạn 2019–2023. Đây là giai đoạn bao gồm ba bối cảnh quan trọng: trước COVID-19, trong COVID-19 và sau COVID-19.

Mục tiêu của dự án là trả lời các câu hỏi chính:

- Ngành F&B Việt Nam đã thay đổi như thế nào trong giai đoạn 2019–2023?
- COVID-19 ảnh hưởng đến doanh thu, lợi nhuận và dòng tiền của doanh nghiệp F&B ra sao?
- Nhóm doanh nghiệp nào phục hồi tốt sau đại dịch?
- Những yếu tố tài chính nào ảnh hưởng mạnh đến doanh thu thuần?
- Doanh nghiệp nên mở rộng, phục hồi hay tái cấu trúc theo hướng nào?

## 2. Mục tiêu phân tích

Dự án tập trung vào 4 mục tiêu chính:

1. Đánh giá bức tranh tổng quan của ngành F&B trước, trong và sau COVID-19.
2. So sánh hiệu quả hoạt động của doanh nghiệp theo quy mô.
3. Xác định các yếu tố tác động đến kết quả kinh doanh thông qua phân tích tương quan và hồi quy.
4. Đưa ra khuyến nghị chiến lược cho từng nhóm doanh nghiệp dựa trên mức độ phục hồi và tình hình tài chính.

## 3. Dữ liệu sử dụng

Dữ liệu được tổng hợp từ các báo cáo tài chính doanh nghiệp trong ngành F&B, bao gồm:

- Balance Sheet
- Income Statement
- Cash Flow Statement
- Một số thông tin thị trường bổ sung từ nguồn tìm kiếm bên ngoài

Giai đoạn phân tích: 2019–2023.

Các nhóm chỉ tiêu chính được sử dụng:

- Doanh thu thuần bán hàng và cung cấp dịch vụ
- Giá vốn hàng bán
- Lợi nhuận gộp
- Lợi nhuận ròng
- ROA, ROE
- Biên lợi nhuận ròng
- Vốn lưu động
- Quick Ratio
- Inventory Turnover
- Total Asset Turnover
- Debt-to-Asset Ratio
- Debt-to-Equity Ratio
- Interest Coverage Ratio
- Dòng tiền từ hoạt động kinh doanh, đầu tư và tài chính

## 4. Phương pháp phân tích

Dự án sử dụng các phương pháp phân tích sau:

### 4.1. Descriptive Analysis

Phân tích mô tả được sử dụng để đánh giá xu hướng doanh thu, lợi nhuận, dòng tiền và tài sản của ngành F&B qua từng năm.

### 4.2. Financial Ratio Analysis

Các chỉ số tài chính được tính toán để so sánh hiệu quả hoạt động giữa các nhóm doanh nghiệp theo quy mô, bao gồm nhóm siêu nhỏ, nhỏ, vừa và lớn.

### 4.3. Correlation Analysis

Phân tích tương quan được sử dụng để xác định các biến tài chính có mối liên hệ mạnh với doanh thu thuần của doanh nghiệp.

### 4.4. Regression Analysis

Mô hình hồi quy được sử dụng để định lượng mức độ ảnh hưởng của từng yếu tố tài chính đến doanh thu thuần trong các giai đoạn khác nhau.

### 4.5. Recovery Assessment

Đánh giá mức độ phục hồi sau COVID-19 dựa trên doanh thu, lợi nhuận, dòng tiền, khả năng thanh toán và rủi ro tài chính.

## 5. Cấu trúc file dự án

```text
FNB-Market-Analysis/
│
├── BAO_CAO_NGANH_FB_1_.pdf
│   └── Báo cáo tổng hợp về ngành F&B Việt Nam giai đoạn 2019–2023.
│
├── Notebook Clean data.ipynb
│   └── Notebook làm sạch, xử lý và chuẩn hóa dữ liệu tài chính doanh nghiệp.
│
├── Notebook Phân tích thị trường.ipynb
│   └── Notebook phân tích tổng quan thị trường F&B trước, trong và sau COVID-19.
│
├── Notebook Phân tích tình hình kinh doanh.ipynb
│   └── Notebook phân tích hiệu quả hoạt động, chỉ số tài chính, tương quan và hồi quy.
│
└── Report.pdf
    └── Báo cáo trình bày kết quả phân tích cuối cùng của dự án.
```

## 6. Hướng dẫn đọc dự án

- File Report chính gồm nội dung và phân tích ở Report.pdf
- File BAO_CAO_NGANH_FB_1.pdf hỗ trợ cung cấp thông tin về ngành FB được sử dụng trong Report
- Các file Notebook gồm code python được lưu dưới dạng ipynb nhằm tiện theo dõi logic và kết quả

## 7. Kết quả chính

Một số kết luận nổi bật từ dự án:

- Trước COVID-19, ngành F&B Việt Nam tăng trưởng ổn định nhưng có dấu hiệu chậm lại do phụ thuộc nhiều vào mô hình kinh doanh truyền thống.
- COVID-19 khiến doanh thu, lợi nhuận và dòng tiền của nhiều doanh nghiệp suy giảm mạnh, đặc biệt trong giai đoạn 2020–2021.
- Sau COVID-19, ngành F&B phục hồi rõ rệt nhờ sự thích nghi với mô hình online, thanh toán số và tái cấu trúc hoạt động.
- Nhóm doanh nghiệp lớn và vừa có khả năng phục hồi lợi nhuận tốt hơn, trong khi nhóm nhỏ và siêu nhỏ chịu áp lực lớn về vốn chủ sở hữu, khả năng thanh toán và đòn bẩy tài chính.
- Giá vốn hàng bán là một trong những yếu tố có ảnh hưởng mạnh và nhất quán đến doanh thu thuần của doanh nghiệp F&B.
- Quản trị chi phí, dòng tiền và tài sản ngắn hạn là các yếu tố quan trọng quyết định khả năng phục hồi sau đại dịch.

## 8. Công cụ sử dụng

Dự án sử dụng các công cụ và thư viện chính sau:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- PowerPoint / Canva cho phần trình bày báo cáo

## 9. Hạn chế của dự án

Dự án vẫn có một số hạn chế:

- Dữ liệu phụ thuộc vào chất lượng báo cáo tài chính của các doanh nghiệp.
- Một số doanh nghiệp có thể thiếu dữ liệu ở một số năm.
- Phân tích hồi quy chỉ phản ánh mối quan hệ thống kê, không khẳng định quan hệ nhân quả tuyệt đối.
- Một số yếu tố phi tài chính như hành vi khách hàng, mức độ chuyển đổi số hoặc chiến lược thương hiệu chưa được lượng hóa đầy đủ.

## 10. Định hướng phát triển tiếp theo

Trong các phiên bản tiếp theo, dự án có thể được mở rộng theo các hướng:

- Xây dựng mô hình chấm điểm mức độ phục hồi của từng doanh nghiệp.
- Phân cụm doanh nghiệp theo hiệu quả tài chính và rủi ro hoạt động.
- Kết hợp thêm dữ liệu thị trường, hành vi tiêu dùng và dữ liệu địa lý.
- Xây dựng dashboard tương tác để theo dõi sức khỏe tài chính của doanh nghiệp F&B.
