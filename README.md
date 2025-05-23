# The Stock Market with Machine Learning

## Giới thiệu
Dự án này sử dụng machine learning để dự đoán biến động giá cổ phiếu dựa trên dữ liệu lịch sử.  
Mục tiêu là xây dựng mô hình dự đoán tăng giảm giá cổ phiếu trong ngày tiếp theo dựa trên các chỉ số kỹ thuật và dữ liệu thị trường.

## Tính năng chính
- Thu thập dữ liệu lịch sử cổ phiếu  
- Tiền xử lý và làm sạch dữ liệu  
- Xây dựng mô hình dự báo bằng Random Forest Classifier  
- Đánh giá mô hình với các chỉ số như Precision Score  
- Backtesting mô hình với dữ liệu thực tế
  
## Công nghệ sử dụng
- Python  
- Thư viện: yfinance, pandas, scikit-learn, matplotlib  
- Mô hình: Random Forest Classifier

## Dữ liệu
- Dữ liệu lịch sử cổ phiếu được lấy từ file CSV `apple_stock_data_20y.csv`.  
- Dữ liệu đã được xử lý để tạo các đặc trưng (features) phục vụ cho mô hình.


## Cài đặt thư viện
Trước khi chạy dự án, bạn cần cài đặt các thư viện sau:

```markdown
pip install yfinance pandas scikit-learn matplotlib
