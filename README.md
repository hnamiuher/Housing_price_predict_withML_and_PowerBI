# **Housing Price Predict in VN**  
### **1. Mục tiêu**  
Trong dự án này, tôi muốn truy cập trang https://i-batdongsan.com/ để thu thập các dữ liệu về nhà đất ở các tỉnh thành trong nước. Sau khi thu thập được dữ liệu, mục tiêu chính của chúng tôi là tiến hành phân tích và dùng các mô hình Machine Learning để dự đoán giá nhà. Đồng thời đưa data đã xử lý vào PowerBI để có cái nhìn trực quan hơn về tình hình giá nhà ở các khu vực với bộ data thu thập được.  
### **2. Các bước thực hiện**  
1. Crawl data từ trang web:  
Tôi sử dụng các thư viện như bs4, selenium để lấy về.  
2. Xử lý dữ liệu:  
![alt text](image.png)
Sau khi qua các bước xử lý dữ liệu tôi thu được 1 bảng data như sau  
3. Trực quan hóa dữ liệu  
Dùng các thư viện Matplotlib để trực quan trước khi đưa vào mô hình machine learning  
4. Huấn luyện các mô hình machine learning cơ bản  
3 mô hình tôi sử dụng ở đây là:  
- Linear Regression  
- xgboost regression  
- GradientBoostingRegressor
5. PowerBI
Phân tích và trực quan dựa trên các plot của PowerBI