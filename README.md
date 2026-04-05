Medical Data Visualizer

This project visualizes and analyzes medical examination data using Python, Pandas, Matplotlib, and Seaborn as part of the freeCodeCamp Data Analysis certification.

📊 Features

* Calculate Body Mass Index (BMI) and determine overweight patients
* Normalize cholesterol and glucose levels
* Create categorical plots showing lifestyle and health indicators
* Generate heatmap to visualize correlations between medical variables
* Clean dataset by removing incorrect or extreme values

🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* NumPy

📁 Project Files

* `medical_data_visualizer.py` → Main analysis and visualization code
* `medical_examination.csv` → Dataset used for analysis

📥 Dataset

Download the dataset from:
https://raw.githubusercontent.com/freeCodeCamp/boilerplate-medical-data-visualizer/main/medical_examination.csv

▶️ How to Run

Run the Python file:

```bash id="med1"
python medical_data_visualizer.py
```

Or run inside Python:

```python id="med2"
from medical_data_visualizer import draw_cat_plot, draw_heat_map

draw_cat_plot()
draw_heat_map()
```

 📈 Output

* Categorical bar plots for health indicators
* Heatmap showing correlation between variables
 ✅ Notes

* Ensure `medical_examination.csv` is in the same folder as the Python file
* This project follows freeCodeCamp requirements
* Data cleaning is important before generating the heatmap

🚀 Author
Keerthana Y
