<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>

  <h1>Data Analytics on School Data</h1>
  <h2>If You Want to Experience this You can Just View/Open The File 23BCE0191.ipynb in github itself</h2>

  <div class="section">
    <h2>Project Overview</h2>
    <p>
      This project analyzes school-level data across multiple years to study trends in student enrollment, expenditure, 
      and academic performance (math scores). The dataset contains school identifiers, financial details, lunch percentages, 
      and standardized test results, allowing us to explore relationships between resources and student outcomes.
    </p>
  </div>

  <div class="section">
    <h2>Dataset Description</h2>
    <ul>
      <li><b>rownames:</b> Row index (identifier for observations)</li>
      <li><b>distid:</b> District ID</li>
      <li><b>schid:</b> School ID</li>
      <li><b>lunch:</b> Percentage of students receiving free/reduced-price lunch (proxy for poverty)</li>
      <li><b>enrol:</b> Enrollment (number of students)</li>
      <li><b>exppp:</b> Expenditure per pupil</li>
      <li><b>math4:</b> Average math score for 4th grade</li>
      <li><b>year:</b> Year of record</li>
      <li><b>y93–y98:</b> Year indicators (dummy variables for regression models)</li>
      <li><b>rexpp:</b> Real expenditure per pupil</li>
      <li><b>found:</b> Funding amount</li>
      <li><b>lenrol:</b> Log of enrollment</li>
      <li><b>lrexpp:</b> Log of real expenditure per pupil</li>
      <li><b>lavgrexpp:</b> Lag of average real expenditure per pupil</li>
    </ul>
  </div>

  <div class="section">
    <h2>Objectives</h2>
    <ul>
      <li>Analyze the relationship between school spending and student performance.</li>
      <li>Examine how poverty (lunch percentage) affects math outcomes.</li>
      <li>Explore enrollment trends over time.</li>
      <li>Use statistical techniques (e.g., regression) for deeper insights.</li>
    </ul>
  </div>

  <div class="section">
    <h2>Tools and Technologies</h2>
    <ul>
      <li>Python (Pandas, NumPy, Matplotlib, Seaborn, Statsmodels)</li>
      <li>R (dplyr, ggplot2, plm for panel data analysis)</li>
      <li>Jupyter Notebook / RStudio</li>
    </ul>
  </div>

  <div class="section">
    <h2>Methodology</h2>
    <ol>
      <li>Data Cleaning – Handle missing values and standardize data types.</li>
      <li>Exploratory Data Analysis – Visualize distributions of math scores, lunch percentage, enrollment, and expenditure.</li>
      <li>Correlation and Regression – Test relationships between resources, poverty, and scores.</li>
      <li>Visualization – Create heatmaps, scatter plots, and trend lines across years.</li>
      <li>Insights and Recommendations – Identify patterns to support school policies.</li>
    </ol>
  </div>

  <div class="section">
    <h2>Expected Outcomes</h2>
    <ul>
      <li>Understand whether higher expenditure per pupil leads to better math scores.</li>
      <li>Examine how poverty levels (lunch percentage) impact student performance.</li>
      <li>Track long-term funding and performance trends.</li>
      <li>Provide evidence-based insights for school resource allocation.</li>
    </ul>
  </div>

  <div class="section">
    <h2>How to Run the Project</h2>
    <pre>
1. Clone the repository:
   git clone https://github.com/yourusername/school-data-analytics.git
   cd school-data-analytics

2. Install required dependencies:
   pip install -r requirements.txt

3. Run Jupyter Notebook:
   jupyter notebook

4. Load the dataset and run the analysis scripts.
    </pre>
  </div>

  <div class="section">
    <h2>Future Enhancements To Be Worked On</h2>
    <ul>
      <li>Use panel data regression for robust results.</li>
      <li>Apply clustering to group similar schools.</li>
      <li>Build an interactive dashboard for visual reporting.</li>
    </ul>
  </div>

  <div class="footer">
    <p><b>Author:</b> Puneeth (23BCE0191) <br>
    Skills: Python, R, Data Analytics</p>
  </div>

</body>
</html>
