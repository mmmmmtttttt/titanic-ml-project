# Titanic Survival Prediction

![Model Performance Banner](./image/confusion_matrix.png)

This project is a machine learning classification model to predict the survival of passengers on the Titanic, based on the well-known Kaggle dataset.

---

## 📁 Project Structure
titanic_project/
├── data/
│ ├── train.csv # Training data - بيانات التدريب
│ └── test.csv # Test data - بيانات الاختبار
├── notebook/
│ ├── titanic.ipynb # Jupyter Notebook with full preprocessing and model training
│ └── submission.csv # Prediction results for submission
└── README.md # Project description - وصف المشروع

---

## 🧠 Model Used

- **Logistic Regression**

This model was chosen after comparing it with other models like Decision Tree. Logistic Regression gave the highest accuracy.

---

## 🔧 Preprocessing Steps

- Filling missing values (`Age`, `Fare`, `Embarked`)
- Dropping unnecessary columns (`Name`, `Cabin`, `Ticket`)
- Extracting titles from names (`Mr`, `Miss`, etc.)
- Encoding categorical variables (`Sex`, `Embarked`, `CabinLetter`, `Title`)
- Ensuring consistent features between training and test sets

---

## 📊 Accuracy

Model Accuracy (validation set): 82.1%

---


---

## 📝 Requirements

- Python 3.10+
- pandas
- scikit-learn
- jupyter or VS Code

Install dependencies:

```bash
pip install pandas scikit-learn notebook

---

🚀 How to Run
1- Open titanic.ipynb in Jupyter or VS Code.
2- Run all cells step by step.
3- submission.csv will be created inside the notebook/ folder.

---

📌 Notes
This is a simple implementation intended for learning and practice.

Future improvements may include:

Better feature engineering

Hyperparameter tuning

Using ensemble models (e.g., Random Forest, XGBoost)

---

✍️ Author
Mohammed Tarig
GitHub: https://github.com/mmmmmtttttt

---
=============================================================================================

🛳️ توقع النجاة في سفينة تايتانيك

![Model Performance Banner](../image/prediction_vs_actual.png)

هذا المشروع عبارة عن نموذج تصنيف باستخدام تعلم الآلة لتوقع من نجا من ركاب سفينة التايتانيك، اعتمادًا على بيانات مشهورة من موقع Kaggle.

---

📁 هيكل المشروع
titanic_project/
├── data/
│   ├── train.csv          # بيانات التدريب
│   └── test.csv           # بيانات الاختبار
├── notebook/
│   ├── titanic.ipynb      # دفتر كود بايثون يحتوي على المعالجة والنموذج
│   └── submission.csv     # النتائج النهائية لتقديمها في كاجل
└── README.md              # وصف المشروع

---

🧠 النموذج المستخدم
الانحدار اللوجستي (Logistic Regression)

تم اختيار هذا النموذج بعد المقارنة مع نموذج شجرة القرار، وقدّم أعلى دقة.

---

🔧 خطوات المعالجة
1- تعبئة القيم المفقودة (مثل Age, Fare, Embarked)

2- حذف الأعمدة غير المفيدة (Name, Cabin, Ticket)

3- استخراج الألقاب من الأسماء (مثل Mr, Miss, ...)

4- ترميز البيانات الفئوية (مثل Sex, Embarked, CabinLetter, Title)

5- التأكد من تطابق الأعمدة بين بيانات التدريب والاختبار

---

📊 الدقة
دقة النموذج (على بيانات التحقق): 82.1%

---

📝 المتطلبات
1- Python 3.10 أو أحدث

2- مكتبة pandas

3- مكتبة scikit-learn

4- Jupyter Notebook أو VS Code

تثبيت المكتبات:

pip install pandas scikit-learn notebook

---

🚀 طريقة التشغيل
1- افتح الملف titanic.ipynb باستخدام Jupyter أو VS Code.

2- شغّل جميع الخلايا خطوة بخطوة.

3- سيتم إنشاء الملف submission.csv داخل مجلد notebook.

---

📌 ملاحظات
هذا المشروع للتعلم والممارسة، وليس الحل النهائي الأفضل.

التحسينات المستقبلية قد تشمل:

هندسة ميزات متقدمة

ضبط معاملات النماذج

استخدام نماذج أقوى مثل Random Forest و XGBoost

---

✍️ المؤلف
محمد طارق
GitHub: https://github.com/mmmmmtttttt
