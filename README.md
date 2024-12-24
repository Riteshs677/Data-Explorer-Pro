# Data-explorer-pro
Interactive data visualization platform

## Overview
The **Data explorer pro** is an interactive web application built using Streamlit, allowing users to effortlessly analyze and visualize datasets. It supports CSV and Excel file uploads, providing a range of features to explore, summarize, and visualize data through a user-friendly interface. The application leverages powerful libraries such as Pandas and Plotly for data processing and visualization.

---

## Features

1. **File Upload**
   - Supports uploading CSV and Excel files.
   - Automatically detects file type and processes the data.

2. **Dataset Summary**
   - Displays the shape of the dataset (number of rows and columns).
   - Provides a statistical summary of numerical data.

3. **Top and Bottom Rows**
   - Allows users to view a specified number of top and bottom rows using sliders.

4. **Data Types and Columns**
   - Displays data types of columns.
   - Lists all column names.

5. **Value Counts**
   - Counts the occurrences of unique values in a selected column.
   - Visualizes value counts using bar, line, and pie charts.

6. **Group By Functionality**
   - Enables grouping data by selected columns with aggregation functions like sum, max, min, mean, median, and count.
   - Visualizes grouped data with customizable charts (line, bar, scatter, pie, and sunburst).

7. **Interactive Visualizations**
   - Utilizes Plotly for dynamic and customizable data visualizations.
   - Offers multiple chart options for grouped data.

---

## Technologies Used

- **Python**
- **Streamlit**: For building the interactive web application.
- **Pandas**: For data manipulation and analysis.
- **Plotly**: For creating dynamic and customizable visualizations.

---

## Getting Started

### Prerequisites
Ensure you have Python 3.8+ installed on your system.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/data-explorer-pro.git
   cd data-explorer-pro
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   # On Windows
   .\env\Scripts\activate
   # On macOS/Linux
   source env/bin/activate
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application
Start the Streamlit application by running:
```bash
streamlit run app.py
```
Open the local URL provided (e.g., `http://localhost:8501`) to access the application in your browser.

---

## Usage

1. Upload a dataset by dragging and dropping a CSV or Excel file.
2. Explore basic information, such as dataset shape and statistical summary.
3. View specific rows (top/bottom) with adjustable sliders.
4. Analyze unique value counts for selected columns with visualizations.
5. Use the Group By feature to summarize data and create advanced visualizations.

---

## Screenshots

![Screenshot 2024-12-23 215643](https://github.com/user-attachments/assets/eb17cb66-69e5-46cd-bd6b-6313c2d38adf)
![Screenshot 2024-12-23 215700](https://github.com/user-attachments/assets/1ae0df73-c585-4b8c-a653-b73637f7e482)
![Screenshot 2024-12-23 215842](https://github.com/user-attachments/assets/d95508f9-6d1b-4e78-b734-454563260a51)

---

## Future Enhancements

- Add support for additional file formats.
- Integrate advanced statistical and machine learning features.
- Implement export functionality for processed data and visualizations.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact
For queries or collaboration, contact: [Riteshsingh1834@gmail.com](Riteshsingh1834@gmail.com)

