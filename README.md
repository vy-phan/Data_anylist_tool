# 🌐 Dashboard Integration LLM AI

An interactive Streamlit-based dashboard that provides CSV/Excel data visualization, column analysis, and chart creation. The application integrates with the Gemini API for AI-powered data insights, offering analysis recommendations, chart suggestions, and assistance in understanding visualizations.

## 🚀 Features

### 📂 File Import
- **Supported formats**: CSV, TSV, XLS, XLSX.
- Upload your dataset and instantly view its structure.

### 📊 Column Analysis
- View each column's **unique values**, with additional support for rendering images if applicable.

![Local GIF](./img/2.gif)

### 🖼️ Chart Creation
- Create dynamic charts with customizable `x` and `y` axes:
  - **Bar Chart**
  - **Line Chart**
  - **Scatter Chart**
  - **Area Chart**

  In case of 2 columns:
  ![Local GIF](./img/3.gif)

  In case of 1 column:
  ![Local GIF](./img/4.gif)
  
### ➕ Column Calculation
- Create new columns using basic operations: **addition, subtraction, multiplication, division**.
- Changes are dynamically reflected in the dataset.

![Local GIF](./img/5.gif)

### 🤖 AI-Powered Insights
- Integrate with **Gemini API** by entering your API key.
- AI provides:
  - Analysis of created charts.
  - Suggestions for new charts.
  - Recommendations for additional columns based on your data.

![Local GIF](./img/6.gif)

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/vy-phan/Data_anylist_tool.git
   cd Data_anylist_tool
   ```

2. Set up a virtual environment:
   
  - **Windows:**
    ```bash
    .\venv\Scripts\activate
    ```
  - **MacOS/Linux:**
    ```bash
    source venv/bin/activate
    ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   - **Windows**
     - For Python 3.12 or newer:
       ```bash
       python -m streamlit run main.py
       ```
     - For older Python versions:
       ```bash
       streamlit run main.py
       ```
   - **MacOS/Linux:**
     ```bash
     streamlit run main.py
     ```

5. Access the application:
   ```bash
   http://localhost:8501
   ```

---

# 🌐 Tích hợp Dashboard LLM AI

Một bảng điều khiển dựa trên Streamlit cung cấp trực quan hóa dữ liệu CSV/Excel, phân tích cột và tạo biểu đồ. Ứng dụng tích hợp với Gemini API để cung cấp thông tin chi tiết bằng AI, bao gồm đề xuất phân tích, gợi ý biểu đồ và hỗ trợ hiểu các trực quan hóa dữ liệu.

## 🚀 Tính năng

### 📂 Nhập tệp
- **Định dạng hỗ trợ**: CSV, TSV, XLS, XLSX.
- Tải lên tập dữ liệu của bạn và xem ngay cấu trúc của nó.

### 📊 Phân tích cột
- Xem các **giá trị duy nhất** của từng cột, với hỗ trợ hiển thị hình ảnh nếu có.

![Local GIF](./img/2.gif)

### 🖼️ Tạo biểu đồ
- Tạo biểu đồ động với các trục `x` và `y` tùy chỉnh:
  - **Biểu đồ cột**
  - **Biểu đồ đường**
  - **Biểu đồ phân tán**
  - **Biểu đồ khu vực**

  Trong trường hợp có 2 cột:
  ![Local GIF](./img/3.gif)

  Trong trường hợp có 1 cột:
  ![Local GIF](./img/4.gif)
  
### ➕ Tính toán cột
- Tạo cột mới bằng các phép toán cơ bản: **cộng, trừ, nhân, chia**.
- Các thay đổi được phản ánh động trong tập dữ liệu.

![Local GIF](./img/5.gif)

### 🤖 Thông tin chi tiết từ AI
- Tích hợp với **Gemini API** bằng cách nhập khóa API của bạn.
- AI cung cấp:
  - Phân tích biểu đồ đã tạo.
  - Gợi ý biểu đồ mới.
  - Đề xuất thêm cột mới dựa trên dữ liệu của bạn.

![Local GIF](./img/6.gif)

## 🚀 Hướng dẫn nhanh

1. Sao chép kho lưu trữ:
   ```bash
   git clone https://github.com/vy-phan/Data_anylist_tool.git
   cd Data_anylist_tool
   ```

2. Thiết lập môi trường ảo:
   
  - **Windows:**
    ```bash
    .\venv\Scripts\activate
    ```
  - **MacOS/Linux:**
    ```bash
    source venv/bin/activate
    ```

3. Cài đặt các thư viện cần thiết:
   ```bash
   pip install -r requirements.txt
   ```

4. Chạy ứng dụng:
   - **Windows**
     - Với Python 3.12 trở lên:
       ```bash
       python -m streamlit run main.py
       ```
     - Với phiên bản Python cũ hơn:
       ```bash
       streamlit run main.py
       ```
   - **MacOS/Linux:**
     ```bash
     streamlit run main.py
     ```

5. Truy cập ứng dụng:
   ```bash
   http://localhost:8501
   
