# House Price Prediction Project

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Filled-orange)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?logo=pandas&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-%23FF4B4B.svg?logo=Streamlit&logoColor=white)

نظام لتوقع سعر المنازل باستخدام تعلم الآلة، استنادًا إلى مسابقة [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) من Kaggle.

## 📸 عرض تفاعلي (Gradio)
تم بناء واجهة تفاعلية باستخدام Gradio.  
(أو: يمكن تشغيل التطبيق محليًا كما هو موضح بالأسفل)

## 🚀 الأداء
| النموذج | RMSE (Validation) | R² |
|--------|-------------------|-----|
| XGBoost (الأفضل) | 0.1315 | ~0.86 |
| LightGBM | 0.1316 | ~0.86 |
| RandomForest | 0.1424 | ~0.85 |

## 🛠️ التقنيات المستخدمة
- Python, Pandas, NumPy
- Scikit-learn (Linear, Ridge, Lasso, Random Forest, XGBoost, LightGBM)
- Pipeline & ColumnTransformer
- OneHotEncoder, StandardScaler
- GridSearchCV for Hyperparameter Tuning
- Gradio for Interactive App

## 📁 هيكل المشروع
```
House_Price_Prediction/
│
├── House_Price_Prediction_Project.ipynb    # الكود الكامل
├── submission.csv                          # ملف التنبؤ للتسليم
├── house_price_model.pkl                   # النموذج المُدرّب
├── README.md                               # هذا الملف
└── PROJECT_DESCRIPTION.txt                 # شرح مفصل بالعربية
```

## ▶️ كيفية التشغيل
1. نزّل جميع الملفات.
2. فعّل البيئة الافتراضية (اختياري):
   ```bash
   python -m venv env
   source env/bin/activate  # Linux/Mac
   env\Scripts\activate     # Windows
   ```
3. ثبّت المكتبات:
   ```bash
   pip install -r requirements.txt
   ```
4. شغّل الكود:
   ```bash
   jupyter notebook House_Price_Prediction_Project.ipynb
   ```

## 🖥️ تشغيل التطبيق التفاعلي
```bash
python app.py
```
أو استخدم Gradio مباشرة في الـ Notebook.

## 📄 متطلبات
- Python 3.7+
- pandas, numpy, scikit-learn, xgboost, lightgbm, gradio

## 🙏 الشكر والتقدير
مشروع تخرج تم تنفيذه بعناية، يدمج بين التنظيف، النمذجة، والتطبيق العملي.

> "التعلم الآلي ليس سحرًا، بل علم دقيق وممنهج." – فريق العمل
