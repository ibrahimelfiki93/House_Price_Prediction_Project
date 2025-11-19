# House Price Prediction Project

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Filled-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-008080?logo=xgboost&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-%23FF4B4B.svg?logo=Gradio&logoColor=white)

نظام متقدم لتوقع أسعار المنازل باستخدام تعلم الآلة، استنادًا إلى مسابقة [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) من Kaggle.

## 🚀 الأداء
| النموذج | RMSE (Validation) | R² |
|--------|-------------------|-----|
| XGBoost (الأفضل) | 0.1315 | ~0.86 |
| LightGBM | 0.1316 | ~0.86 |
| RandomForest | 0.1424 | ~0.85 |

## 🌐 جرب التطبيق التفاعلي
[🚀 افتح التطبيق الآن](https://huggingface.co/spaces/ibrahimelfiki93/house-price-prediction)

## 🛠️ التقنيات المستخدمة
- Python, Pandas, NumPy
- Scikit-learn (Linear, Ridge, Lasso, Random Forest, XGBoost, LightGBM)
- Pipeline & ColumnTransformer مع StandardScaler وOneHotEncoder
- GridSearchCV for Hyperparameter Tuning
- Gradio for Interactive Web App
- Hugging Face Spaces for Deployment

## 📁 هيكل المشروع
```
House_Price_Prediction/
│
├── House_Price_Prediction_Project.ipynb    # الكود الكامل للمشروع
├── submission.csv                          # ملف التنبؤ للتسليم على كاجل
├── house_price_model.pkl                   # النموذج الفائز (XGBoost) بعد التحسين
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

## 🖥️ تشغيل التطبيق التفاعلي محليًا
```bash
python app.py
```

## 📄 المتطلبات
- Python 3.7+
- pandas, numpy, scikit-learn==1.4.2, xgboost, gradio

## 💡 ملاحظة مهمة حول الإصدارات
تم بناء النموذج باستخدام إصدار حديث من `scikit-learn`، لكن تم تعديله ليعمل بإصدار `1.4.2` لضمان التوافق والاستقرار عند النشر. هذا يضمن أن التطبيق يعمل دون أخطاء على أي بيئة.

## 🙏 الشكر والتقدير
مشروع تخرج تم تنفيذه بدقة عالية، يدمج بين التنظيف، النمذجة، والنشر العملي.  
"التعلم الآلة ليس سحرًا، بل علم دقيق وممنهج."

🔗 [رابط GitHub](https://github.com/ibrahimelfiki93/House_Price_Prediction_Project)
