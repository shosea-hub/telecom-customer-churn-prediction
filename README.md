# Telecom Customer Churn Prediction
### AI/ML Capstone Project | Group Tango | Tutor: Dami

## Project Overview
This project applies supervised machine learning to predict whether a 
telecom customer will churn (leave the service provider). 
By identifying at-risk customers early, businesses can take proactive 
retention steps before losing them.

## Dataset
- **Source:** Maven Analytics Telecom Customer Churn (IBM Cognos), via Kaggle
- **Records:** 7,043 customers
- **Features:** 38 columns covering demographics, services, and billing
- **Churn Rate:** 26.5%
- **Licence:** Public Domain

## Models Used
| Model | Test Accuracy | AUC | Recall (Churned) |
|---|---|---|---|
| Random Forest | 81.84% | 0.881 | 0.60 |
| Logistic Regression | 81.84% | 0.884 | 0.68 ✓ |

**Recommended Model: Logistic Regression** . Higher Recall means it 
catches more actual churners, which matters most for retention.

## Key Findings
- Month-to-month contract holders churn at the highest rate
- Most churn happens within the first 12 months of service
- Fibre Optic customers churn most despite paying premium prices
- Higher monthly charges are strongly linked to churn
- Customers who make referrals rarely leave

## Project Structure
| File | Description |
|---|---|
| `telecom_customer_churn.csv` | Dataset used for this project |
| `Group_Tango_Churn_Notebook.ipynb` | Full annotated Colab notebook |
| `Group_Tango_Churn_Report.docx` | Complete written report |
| `Group_Tango_Churn_Presentation_Slides.pptx` | Final presentation slides |

## How to Run the Code
1. Download `telecom_customer_churn.csv` and upload it to your Google Drive
2. Open [Google Colab](https://colab.research.google.com)
3. Upload `Group_Tango_Churn_Notebook.ipynb` directly into Colab
4. Run cells from top to bottom

## Ethics & Governance
This project was developed with responsible AI principles in mind.
The dataset contains no real personal data. Gender and marital status 
were examined for bias but not used as model inputs. 
Findings reflect a California-based telecom context and may not 
directly generalise to Nigerian or African markets.

## Tools & Libraries
Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn | Google Colab

## Group
Group Tango | AI/ML Capstone
