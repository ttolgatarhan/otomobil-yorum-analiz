# otomobil-yorum-analiz
Bu projede, araç alım rehberine yönelik Türkçe metinler arasında anlam temelli benzerlik analizleri gerçekleştirilmiştir. TF-IDF ve Word2Vec yöntemleriyle giriş cümlesine en yakın içerikler tespit edilip karşılaştırılmıştır.

# Proje Açıklaması
Bu projede, araç alım-satım süreçlerine dair Türkçe metinler arasında anlam temelli benzerlik tespiti yapılmıştır. Giriş cümlesine en yakın metinleri bulmak amacıyla TF-IDF ve Word2Vec yöntemleri karşılaştırmalı olarak uygulanmıştır.

# Kullanılan Teknolojiler ve Kütüphaneler
Python 3.8+
Pandas – veri işleme ve analiz
Scikit-learn – TF-IDF vektörleme, benzerlik hesaplama
Gensim – Word2Vec model eğitimi
NLTK / Simple Turkish Stemmer – metin temizleme ve kök alma
Matplotlib / Seaborn – görselleştirme
Pickle – model kaydetme/yükleme
Openpyxl – Excel işlemleri

# Projeyi Çalıştırma Talimatları
Gereksinimleri yükleyin
pip install -r requirements.txt
Jupyter Notebook'u başlatın
jupyter notebook
Ana dosyayı açın
tolga tarhan otomobil son hali.ipynb dosyasını açın.
Adımları sırayla takip edin
Metin ön işleme
TF-IDF ve Word2Vec modelleme
Benzerlik hesaplama
Puanlama ve değerlendirme
Sonuçları inceleyin
Excel dosyalarında model puanlamaları ve Jaccard benzerlik matrisi mevcuttur.
