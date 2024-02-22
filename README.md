# CSV-Analyzer
### CSV Analyzer using Lyzr AI

This is a CSV Analyzer web application built using Streamlit and Lyzr AI. It allows users to upload a CSV file, select columns for analysis, input analysis queries, and get insights, visualizations, dataset descriptions, recommended analysis queries, analysis recommendations, strategic recommendations, and tasks for analysis using the Lyzr AI capabilities.

### How to Use

1. Upload CSV File: Click on "Upload CSV file" and select a CSV file from your local machine.

2. Select Columns for Analysis: You can choose to select all columns by checking the "Select all columns" checkbox, or manually select columns for analysis using the multiselect dropdown.

3. Enter Analysis Query: Input your analysis query in the text box provided.

4. Predict: Click the "Predict" button to initiate the analysis process.

5. Analysis Insights: After clicking "Predict", the app will display analysis insights based on your query.

6. Visualizing: The app will also generate visualizations based on the analysis query. You can view these visualizations by scrolling down.

7. Dataset Description: Below the visualizations, you will find a section displaying the dataset description, providing an overview of the uploaded data.

8. Recommended Analysis Queries: The app suggests recommended analysis queries based on the dataset. These can provide additional insights into the data.

9. Analysis Recommendations: Next, you'll see analysis recommendations based on the dataset and your analysis query. These recommendations guide further exploration and understanding.

10. Strategic Recommendations: Strategic recommendations are provided based on the analysis insights. These recommendations suggest actionable steps based on the analysis.

11. Tasks for Analysis: Finally, the app presents tasks for analysis, breaking down high-level objectives into actionable tasks for a more focused approach.

### Requirements

- Python 3.7+
- Streamlit
- Pandas
- Lyzr

### Installation

You can install the required packages using pip:

```bash
pip install streamlit pandas lyzr
```

### How to Run
1. Run the Streamlit app:

```bash
streamlit run app.py
```
2. Access the app in your browser at [http://localhost:8501](http://localhost:8501)

### Acknowledgements

- [Streamlit](https://www.streamlit.io/)
- [Pandas](https://pandas.pydata.org/)
- [Lyzr AI](https://lyzr.ai/)

Thank you for using our CSV Analyzer app powered by Lyzr AI! 🚀
