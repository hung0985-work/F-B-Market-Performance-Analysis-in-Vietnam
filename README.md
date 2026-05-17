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

## 5. Cấu trúc thư mục

Cấu trúc repo đề xuất:

```text
FNB-Market-Analysis/
│
├── data/
│   ├── raw/                      # Dữ liệu gốc
│   ├── processed/                # Dữ liệu đã làm sạch và xử lý
│   └── external/                 # Dữ liệu hoặc thông tin thị trường bổ sung
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb    # Làm sạch và chuẩn hóa dữ liệu
│   ├── 02_market_overview.ipynb  # Phân tích tổng quan thị trường
│   ├── 03_financial_ratios.ipynb # Tính toán và phân tích chỉ số tài chính
│   ├── 04_impact_drivers.ipynb   # Phân tích tương quan và hồi quy
│   └── 05_recommendation.ipynb   # Tổng hợp insight và đề xuất
│
├── reports/
│   ├── FNB_Market_Analysis_Report.pdf
│   └── presentation.pdf
│
├── visuals/
│   ├── charts/                   # Biểu đồ phân tích
│   └── figures/                  # Hình ảnh sử dụng trong báo cáo
│
├── src/
│   ├── data_preprocessing.py     # Hàm xử lý dữ liệu
│   ├── financial_metrics.py      # Hàm tính chỉ số tài chính
│   └── visualization.py          # Hàm vẽ biểu đồ
│
├── README.md
└── requirements.txt
