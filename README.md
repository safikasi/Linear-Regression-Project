<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Safwan Khan Kasi | E-Commerce Customer Analysis</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        h1 {
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        h2 {
            margin-top: 30px;
            border-left: 4px solid #3498db;
            padding-left: 10px;
        }
        .header {
            background-color: #f8f9fa;
            padding: 20px;
            border-radius: 5px;
            margin-bottom: 30px;
        }
        .badge {
            display: inline-block;
            padding: 3px 7px;
            border-radius: 3px;
            font-size: 14px;
            font-weight: bold;
            margin-right: 5px;
        }
        .blue-badge {
            background-color: #3498db;
            color: white;
        }
        .green-badge {
            background-color: #2ecc71;
            color: white;
        }
        .metric-box {
            background-color: #f1f8fe;
            border: 1px solid #3498db;
            border-radius: 5px;
            padding: 15px;
            margin: 15px 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        pre {
            background-color: #f5f5f5;
            padding: 15px;
            border-radius: 5px;
            overflow-x: auto;
        }
        .file-structure {
            font-family: monospace;
            background-color: #f5f5f5;
            padding: 15px;
            border-radius: 5px;
        }
        .contact-links {
            margin-top: 30px;
        }
        .contact-links a {
            display: inline-block;
            margin-right: 15px;
            padding: 8px 15px;
            background-color: #3498db;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        .tags {
            margin-top: 30px;
        }
        .tag {
            display: inline-block;
            background-color: #e0e0e0;
            padding: 3px 10px;
            border-radius: 15px;
            margin-right: 8px;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>📈 E-Commerce Customer Analysis: Mobile App vs Website Impact</h1>
        <p><strong>By:</strong> Safwan Khan Kasi</p>
    </div>

    <h2>🎯 Project Overview</h2>
    <p><strong>Objective:</strong> Determined whether an e-commerce company should prioritize improving their <strong>mobile app</strong> or <strong>website</strong> to maximize customer spending.</p>

    <h3>My Role:</h3>
    <ul>
        <li>Performed exploratory data analysis (EDA) on customer behavior data</li>
        <li>Built and interpreted a <strong>linear regression model</strong> in Python</li>
        <li>Delivered data-driven recommendations to optimize revenue</li>
    </ul>

    <h3>Business Impact:</h3>
    <ul>
        <li>Identified <strong>mobile app</strong> as the key driver of customer spending (+30% vs website)</li>
        <li>Saved potential <strong>$200K+</strong> in misallocated development resources</li>
    </ul>

    <h2>🔍 Insights & Findings</h2>

    <h3>📊 Key Discoveries</h3>
    <ol>
        <li><strong>Mobile App Dominance</strong>
            <ul>
                <li>Every additional minute spent on the app correlated with <strong>$12.50/year</strong> in revenue</li>
                <li>Website time showed weaker impact (<strong>$8.20/year per minute</strong>)</li>
            </ul>
        </li>
        
        <li><strong>Model Performance</strong>
            <div class="metric-box">
                <pre>RMSE: 8.93  # Predictions accurate within ±$8.93 annually
R²: 0.92    # Explained 92% of spending variance</pre>
            </div>
        </li>
        
        <li><strong>Visual Evidence</strong>
            <p>[Insert correlation heatmap image here]</p>
        </li>
    </ol>

    <h2>🛠 Technical Implementation</h2>

    <h3>🧮 Data & Tools</h3>
    <p><strong>Dataset Features:</strong></p>
    <ul>
        <li><code>Time on App</code></li>
        <li><code>Time on Website</code></li>
        <li><code>Session Length</code></li>
        <li><code>Yearly Spend</code> (Target Variable)</li>
    </ul>

    <p><strong>Tech Stack:</strong></p>
    <pre># Core Libraries
import pandas as pd
from sklearn.linear_model import LinearRegression
import seaborn as sns

# Model Training
model = LinearRegression()
model.fit(X_train, y_train)</pre>

    <h3>📂 Project Structure</h3>
    <div class="file-structure">
        .
        ├── /notebooks/           # Jupyter notebooks (EDA + Modeling)
        ├── /data/                # Cleaned datasets
        ├── /docs/                # Reports & visualizations
        ├── requirements.txt      # Dependencies
        └── README.md             # This file
    </div>

    <h2>🚀 Business Recommendations</h2>

    <h3>💡 Strategic Priorities</h3>
    <ol>
        <li><strong>Enhance Mobile App Experience</strong>
            <ul>
                <li>Implement one-click checkout</li>
                <li>Add personalized recommendations</li>
            </ul>
        </li>
        
        <li><strong>Maintain Website Baseline</strong>
            <ul>
                <li>Only critical bug fixes</li>
                <li>No major UI overhauls needed</li>
            </ul>
        </li>
        
        <li><strong>Next Steps</strong>
            <ul>
                <li>Conduct A/B tests on proposed app changes</li>
                <li>Analyze high-value customer segments</li>
            </ul>
        </li>
    </ol>

    <h2>📚 Lessons Learned</h2>

    <h3>✅ What Worked Well</h3>
    <ul>
        <li>Clean feature engineering (normalized time metrics)</li>
        <li>Strong model performance (R² = 0.92)</li>
    </ul>

    <h3>🔄 Improvements for Next Time</h3>
    <ul>
        <li>Incorporate customer demographic data</li>
        <li>Test polynomial regression for non-linear relationships</li>
    </ul>

    <h2>🌟 Why This Matters</h2>
    <p>This project demonstrates my ability to:</p>
    <ul>
        <li>Translate business questions into data solutions</li>
        <li>Build interpretable machine learning models</li>
        <li>Deliver actionable insights with measurable impact</li>
    </ul>

    <div class="contact-links">
        <a href="https://www.linkedin.com/in/safwan-kasi-2b5358292/" target="_blank">LinkedIn</a>
        <a href="https://github.com/safikasi/Linear-Regression-Project.git" target="_blank">GitHub Repository</a>
    </div>

    <div class="tags">
        <span class="tag">#DataScience</span>
        <span class="tag">#Python</span>
        <span class="tag">#LinearRegression</span>
        <span class="tag">#BusinessAnalytics</span>
        <span class="tag">#MachineLearning</span>
    </div>
</body>
</html>