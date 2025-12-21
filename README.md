# Online-Shoppers-Intention-UCI-Machine-Learning
## Giới thiệu
- Dự án này tập trung vào việc dự đoán khả năng khách hàng có thực hiện mua hàng hay không dựa trên hành vi duyệt web của họ, sử dụng thuật toán Logistic Regression.

Bài toán thuộc nhóm Supervised Learning – Binary Classification, với nhãn mục tiêu là:

  + Revenue = 1: Khách hàng có mua hàng

  + Revenue = 0: Khách hàng không mua hàng

Dataset được lấy từ Kaggle và thường được sử dụng trong các bài toán Machine Learning thực tế liên quan đến E-commerce Analytics.
## Dataset

Tên dataset: Online Shoppers Purchasing Intention

## Nguồn: Kaggle
http://kaggle.com/datasets/henrysue/online-shoppers-intention

- Một số đặc trưng tiêu biểu:
  
  - Administrative, Informational, ProductRelated
  
  - BounceRates, ExitRates, PageValues
  
  - Month, VisitorType, Weekend
  
  - Revenue (label)
## Mục tiêu

- Phân tích và khám phá dữ liệu (EDA)
  
- Tiền xử lý dữ liệu (encoding, scaling)
  
- Huấn luyện mô hình Logistic Regression
  
- Đánh giá mô hình bằng các chỉ số:

  - Accuracy
    
  - Precision / Recall / F1-score
    
  - ROC – AUC
    
  - Confusion Matrix

## Công nghệ & Thư viện sử dụng

Python

Pandas, NumPy – Xử lý dữ liệu

Matplotlib, Seaborn – Trực quan hóa

Scikit-learn:

StandardScaler

LabelEncoder

LogisticRegression

train_test_split

classification_report

roc_auc_score

confusion_matrix

## Quy trình thực hiện
- Khám phá dữ liệu (EDA)

  - Kiểm tra kiểu dữ liệu, giá trị thiếu
  
  - Thống kê mô tả
  
  - Phân tích phân phối dữ liệu
  
  - Trực quan hóa tương quan giữa các đặc trưng
  
  - Phát hiện outlier
- Tiền xử lý dữ liệu

  - Encoding các biến phân loại (Month, VisitorType, Weekend)
  
  - Chuẩn hóa dữ liệu bằng StandardScaler
  
  - Tách feature (X) và label (y)

- Chia dữ liệu

  - Train: 70%
  
  - Validation: 15%
  
  - Test: 15%
- Huấn luyện mô hình

  - Sử dụng Logistic Regression
  
  - Huấn luyện trên tập train

- Đánh giá mô hình

  - Accuracy
  
  - Classification Report
  
  - ROC Curve & AUC
  
  - Confusion Matrix

 ## Kết quả
