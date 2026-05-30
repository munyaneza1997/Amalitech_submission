# Amalitech_submission
## Executive Summary
This project investigated whether negative customer reviews were caused by delivery delays and inaccurate delivery promises.
Several states experienced significantly higher late-delivery rates than the national average.
Late deliveries were strongly associated with lower review scores.
The dashboard enables executives to monitor delivery performance and customer sentiment.

## Project Links
- Notebook: [https://colab.research.google.com/drive/1OgbG2FevMbeMKapIc_SXjNu8Un-Q-jQJ?usp=sharing](https://colab.research.google.com/drive/1OgbG2FevMbeMKapIc_SXjNu8Un-Q-jQJ?usp=sharing)
- Dashboard:https://accessplc-my.sharepoint.com/:u:/g/personal/kwizeraj_accessbankplc_com1/IQAOM7AVaQCCSK1FMjt66rGrAR_YJjNeLCuY0xQyYfXlXgo?e=JIViOl
- Presentation:https://www.canva.com/design/DAHImm_u55Y/4PhHLbsdwDAqVyYGpVfaQg/edit

## Technical Explanation

### Data Cleaning
- Joined Orders, Reviews, Customers datasets.
- Converted date columns to datetime.
- Removed cancelled/unavailable orders.
- Calculated Days_Difference.
- Classified orders as On Time, Late, Super Late.

### Candidate's Choice
Regional Risk Score combining:
- Late Delivery %
- Cancellation %
- Average Review Score

