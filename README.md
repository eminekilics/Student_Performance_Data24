# Student_Performance_Data24
EN-

This project uses the SPD24 Student Performance Dataset to predict students’ performance levels based on demographic, academic, and socioeconomic features.
The main goal is to practice data preprocessing, exploratory data analysis (EDA), and classification models with Python.

Dataset Source: SPD24 dataset (https://www.kaggle.com/datasets/nasirayub2/spd24-student-performance-data-revised-features?)

Target variable: Performance Score (Low / Medium / High)
Features include:
Age, Gender, Grade Level, Attendance Rate, Study Hours, Parental Education & Involvement, Socioeconomic Status, Extracurricular Activities, School Climate, Tutoring Sessions and more (41 columns in total)

Steps
Data Cleaning
Fixed formatting issues (; replaced with . in numerical columns)
Encoded categorical variables using Label Encoding
Exploratory Data Analysis (EDA)
Visualized distributions (Gender, Age, Performance Score)
Checked correlations with a heatmap
Modeling
Applied Logistic Regression to predict performance scores
Evaluated results using Classification Report & Confusion Matrix

Results
Logistic Regression model performed well on the dataset
Provided clear classification between Low / Medium / High performance categories
Confusion matrix and classification report included in results

Visualizations
Gender distribution
Age distribution
Performance Score distribution
Correlation heatmap
Confusion Matrix

Technologies Used
Python
Pandas, NumPy
Seaborn, Matplotlib
scikit-learn

TR-

Bu proje, SPD24 Öğrenci Performansı Veri Seti kullanılarak öğrencilerin demografik, akademik ve sosyoekonomik özelliklerine göre performans seviyelerinin tahmin edilmesini amaçlamaktadır.
Amacım, Python kullanarak veri ön işleme, keşifsel veri analizi (EDA) ve sınıflandırma modelleri üzerine pratik yapmaktır.

Veri Seti
Kaynak SPD24 veriseti (https://www.kaggle.com/datasets/nasirayub2/spd24-student-performance-data-revised-features?)

Hedef değişken: Performance Score (Low / Medium / High)

Özellikler:
Age, Gender, Grade Level, Attendance Rate, Study Hours, Parental Education & Involvement, Socioeconomic Status, Extracurricular Activities, School Climate, Tutoring Sessions ve dahası (toplamda 41 sütun)

Adımlar
Veri Temizleme
Sayısal sütunlarda ; işaretini . ile değiştirip float formatına çevirdim
Kategorik değişkenleri Label Encoding ile sayısal hale getirdim
Keşifsel Veri Analizi (EDA)
Dağılımları görselleştirdim (Cinsiyet, Yaş, Performans)
Korelasyonları ısı haritasıyla inceledim
Modelleme
Lojistik Regresyon ile performans seviyelerini tahmin ettim
Sonuçları Classification Report ve Confusion Matrix ile değerlendirdim

Sonuçlar
Logistic Regression modeli veri setinde tatmin edici sonuçlar verdi
Öğrencilerin düşük / orta / yüksek performans kategorileri arasında ayrım yapabildi
Çıktılarda sınıflandırma raporu ve confusion matrix mevcut

Görselleştirmeler
Cinsiyet dağılımı
Yaş dağılımı
Performans puanı dağılımı
Korelasyon ısı haritası
Confusion Matrix

Kullanılan Teknolojiler
Python
Pandas, NumPy
Seaborn, Matplotlib
scikit-learn

