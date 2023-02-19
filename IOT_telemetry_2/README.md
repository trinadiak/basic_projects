## About this project

Dataset source: https://www.kaggle.com/datasets/garystafford/environmental-sensor-data-132kv <br>
Total rows: 405,184

This project is focused on comparing the performance between KNN and Logistic Regression in predicting the detected light with 2 features: humidity and temperature

### Data Description

| column   | description          | units      |
|----------|----------------------|------------|
| ts       | timestamp of event   | epoch      |
| device   | unique device name   | string     |
| co       | carbon monoxide      | ppm (%)    |
| humidity | humidity             | percentage |
| light    | light detected?      | boolean    |
| lpg      | liquid petroleum gas | ppm (%)    |
| motion   | motion detected?     | boolean    |
| smoke    | smoke                | ppm (%)    |
| temp     | temperature          | Fahrenheit |
