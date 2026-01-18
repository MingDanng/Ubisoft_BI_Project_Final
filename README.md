# 🎮 Ubisoft Business Intelligence: From Data Analysis to Sales Prediction

> **Thực hiện bởi:** **Nguyễn Phúc Minh Đăng (521H0497)**
>
> **Vai trò:** Data Analyst & Machine Learning Engineer

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Machine Learning](https://img.shields.io/badge/Sklearn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

## 📖 Introduction (Giới thiệu)
Dự án **Business Intelligence (BI)** toàn diện về **Ubisoft Entertainment SA**.
Mục tiêu: Xây dựng hệ thống hỗ trợ ra quyết định (DSS) dựa trên dữ liệu lịch sử ngành game, đi từ phân tích khám phá (Descriptive) đến dự báo (Predictive) và đề xuất chiến lược (Prescriptive).

---

## 📍 Phase 1: Descriptive Analysis (Midterm)
Giai đoạn phân tích khám phá dữ liệu (EDA) sử dụng **Python** để làm sạch dữ liệu và tìm ra các xu hướng kinh doanh cốt lõi trong quá khứ.

> **Các biểu đồ phân tích chính:**
>
> | 1. Phân tích Xu hướng (Trend) | 2. Ma trận Tương quan (Correlation) |
> | :---: | :---: |
> | <img src="images/midterm_eda_1.png" width="100%"> | <img src="images/midterm_eda_2.png" width="100%"> |
> | *Biểu đồ thể hiện biến động doanh thu* | *Mức độ ảnh hưởng giữa các chỉ số* |

👉 *[Xem chi tiết Báo cáo Giữa kỳ (PDF)](Phase1_EDA_Analysis/Midterm_Report.pdf)*

---

## 📍 Phase 2: Predictive Modeling & Dashboard (Final)
Xây dựng mô hình Machine Learning dự báo doanh thu và hệ thống Dashboard quản trị chiến lược trên **Power BI**.

### 1. Machine Learning Performance
* **Model:** Gradient Boosting Regressor (Tối ưu nhất trong các mô hình thử nghiệm).
* **Target:** Dự báo doanh thu toàn cầu (`Global_Sales`).
* **Metric:** R² Score ~18.83% (Phản ánh thị trường game chịu ảnh hưởng lớn bởi xu hướng và marketing hơn là chỉ số kỹ thuật).

### 2. Power BI Dashboard System
Hệ thống báo cáo được thiết kế theo luồng kể chuyện (Data Storytelling) với 4 màn hình chuyên sâu:

> **Thư viện Dashboard (Giao diện hệ thống):**
>
> | 1. Market Overview | 2. Ubisoft Product Performance |
> | :---: | :---: |
> | <img src="images/market_overview.png" width="100%"> | <img src="images/product_performance.png" width="100%"> |
> | *Tổng quan thị trường & Đối thủ* | *Hiệu suất các dòng game chủ lực* |
> | **3. Strategic Insights** | **4. Conclusion** |
> | <img src="images/strategic_insights.png" width="100%"> | <img src="images/conclusion.png"> width="10