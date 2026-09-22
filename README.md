# Data-science-on-cybersecurity-breach
Data science personal project analyzing on the cybersecurity breach dataset from kaggle. Made with Jupyter notebook 

Data sourced used from kaggle (https://www.kaggle.com/datasets/thedevastator/data-breaches-a-comprehensive-list)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/Data-science-on-cybersecurity-breach.git
cd Data-science-on-cybersecurity-breach
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open and run the notebook:
```bash
jupyter notebook notebooks_Personal_project.ipynb
```
Summary:
- **Size:** 352 records | 8 features
- **Key Variables:** Year, Records Leaked, Breach Method, Organization Type

## Model Results

| Model | Train/Test Split | R² Score | Variance Explained |
|-------|------------------|----------|-------------------|
| Linear Regression | 80/20 | 0.0308 | 3% |
| Random Forest | 80/20 | -0.1543 | Worse than mean |

## Key Observations

1. **Temporal Trends:** Breaches peaked in 2015-2016 with a notable decline in 2017
2. **Most Targeted Medium:** Web-based breaches dominate the dataset
3. **Top Attack Method:** Hacking (SQL injection, credential theft, zero-days)
4. **Recurrent Targets:** Yahoo experienced multiple breaches, especially in 2013

## Future Work

1. Add organizational features (company type, size, industry)
2. Implement classification models (Small/Medium/Large breaches)
3. Build industry-specific predictive models
4. Feature engineering to combine temporal and organizational data
5. Anomaly detection for unusual breach patterns

## Author

Adrien Koe | Data Visualization Major | University of Washington Bothell

## License

This project uses publicly available data. See dataset source for licensing details.

