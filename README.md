# 🌍 Earthquake Data Analysis - USGS 2025

تحليل شامل لبيانات الزلازل حول العالم بناءً على قاعدة بيانات USGS الرسمية، يغطي أهم الخصائص مثل النوع، العمق، القوة، والموقع الجغرافي.

---

##  محتوى المشروع

## التقنيات المستخدمة :
Python
Pandas
Seaborn
Matplotlib
Jupyter / Google Colab

### 1. قراءة وتجهيز البيانات
- تم تحميل البيانات من [USGS Earthquake Catalog](https://earthquake.usgs.gov/earthquakes/search/).
- تم الاقتصار على الأعمدة الأساسية: `time`, `latitude`, `longitude`, `depth`, `mag`, `place`, `type`.
- إزالة القيم الفارغة وتنظيف البيانات.

### 2. تحليل حسب نوع الزلزال (`type`)
- استخدمنا Boxplot لمقارنة توزع قوة الزلازل باختلاف النوع.
- لوحظ أن بعض الأنواع تمتاز بمتوسط قوة أعلى.

### 3. العلاقة بين العمق والقوة
- استخدمنا scatterplot لإظهار العلاقة بين عمق الزلزال وقوته، وكانت النتيجة وجود علاقة طردية معتدلة.


### 4. النشاط الزلزالي عبر السنوات
- أكثر سنة نشاطًا كانت **2025** بعدد زلازل: **9366**.

### 5. أكثر المواقع تكرارًا للزلازل
```text
1. 7 km NW of The Geysers, CA     (126 مرة)
2. 7 km WNW of Cobb, CA           (112 مرة)
3. 63 km WNW of Tyonek, Alaska    (100 مرة)
4. 8 km NW of Prague, Oklahoma     (89 مرة)
5. 8 km NNW of The Geysers, CA     (83 مرة)
### 6.الاستنتاجات


الزلازل تتكرر بكثرة في مناطق مثل California وAlaska.

العمق له علاقة متوسطة بقوة الزلزال.

بعض أنواع الزلازل تتسبب بأضرار أكبر بناءً على توزيع القوة.

``` 
git clone https://github.com/AMR-am/earthquake-analysis-2025.git
cd earthquake-analysis-2025

