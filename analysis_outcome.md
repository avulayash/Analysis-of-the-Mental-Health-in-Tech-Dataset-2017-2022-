## 🤖 Machine Learning Analysis: Mental Health Prediction

This section presents a machine learning analysis using a **Random Forest Classifier** to predict mental health conditions based on workplace and personal factors.

---

### 1. 📊 Feature Importance Analysis (Bar Chart from Random Forest)

![Feature Importance Bar Chart](path/to/your_chart.png) <!-- Replace with your actual image path -->

#### 🔍 Key Observations:

**Top Features**:
- `age`: Most important feature by a significant margin.
- `mh_share`: Willingness to share mental health status strongly influences predictions.
- `country`: Regional and cultural differences seem to play a role.
- `mh_coworker_discussion` and `workplace_resources`: Indicators of a supportive work environment.

**Less Important Features**:
- `medical_coverage`, `tech_company`, and `mh_employer_discussion`: Found to have the least influence on predictions.

#### ✅ Conclusion:
> The model suggests **individual-level factors** (like age and openness to discuss mental health) and a **supportive workplace culture** have more impact than **organizational policies** such as benefits or insurance coverage.

---

### 2. 📈 Model Performance (Classification Report)

```text
Accuracy:       67.87%
Precision (Class 1): ~77%
Recall (Class 1):    ~77%
F1 Score (Class 1):  ~77%
