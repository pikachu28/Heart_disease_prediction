# Heart_disease_prediction

### Input required for prediction


**Age**

**Sex**

**Chest pain**

      0: Typical angina: chest pain related decrease blood supply to the heart
      
      1: Atypical angina: chest pain not related to heart
      
      2: Non-anginal pain: typically esophageal spasms (non heart related)
      
      3: Asymptomatic: chest pain not showing signs of disease
      
      
**trestbps** - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern

**chol** - serum cholestoral in mg/dl

      serum = LDL + HDL + .2 * triglycerides
      
      above 200 is cause for concern
      
**fbs** -  (1 = true; 0 = false)

**restecg** - resting electrocardiographic results

      0: Nothing to note
      
      1: ST-T Wave abnormality can range from mild symptoms to severe problems
      
      signals non-normal heart beat
      
      2: Possible or definite left ventricular hypertrophy Enlarged heart's main pumping chamber
      
**thalach** - maximum heart rate achieved

**exang** - exercise induced angina (1 = yes; 0 = no)

**oldpeak** - ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more


## About Heart Disease

The term “heart disease” refers to several types of heart conditions. The most common type of heart disease in the United States is coronary artery disease (CAD), which affects the blood flow to the heart. Decreased blood flow can cause a heart attack.


### What are the symptoms of heart disease?

Sometimes heart disease may be “silent” and not diagnosed until a person experiences signs or symptoms of a heart attack, heart failure, or an arrhythmia. When these events happen, symptoms may include1

      -Heart attack: Chest pain or discomfort, upper back or neck pain, indigestion, heartburn, nausea or vomiting, extreme fatigue, upper body discomfort, dizziness, and shortness of breath.
      -Arrhythmia: Fluttering feelings in the chest (palpitations).
      -Heart failure: Shortness of breath, fatigue, or swelling of the feet, ankles, legs, abdomen, or neck veins.
      
      
### What are the risk factors for heart disease?

High blood pressure, high blood cholesterol, and smoking are key risk factors for heart disease. About half of people in the United States (47%) have at least one of these three risk factors.2 Several other medical conditions and lifestyle choices can also put people at a higher risk for heart disease, including

      -Diabetes
      -Overweight and obesity
      -Unhealthy diet
      -Physical inactivity
      -Excessive alcohol use

Based on above factors we have selected a Cleveland heart disease dataset which has 13 attribbites (mentioned in the input required section).

The "goal" field refers to the presence of heart disease in the patient. It is integer valued from 0 (no presence) to 4.

Therefore, we used Machine Learning to predict the presence of heart disease in the person. We have Machine Learning algorithms like Logistic Regression, K Neighbors Classifier, Support Vector Classifier, Decision Tree Classifier ,Random Forest Classifier, XGBoost Classifer.

**XGBoost Performace:**

      Training Accuracy: 99%
      Testing Accuracy: 85.6%
