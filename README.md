# yapay-zeka-final-dev-
# Word2Vec Metin Benzerliği Projesi

Bu projede Word2Vec algoritması kullanılarak metinler arası benzerlik analizi yapılmıştır.

## Proje Amacı
Farklı Word2Vec model yapılandırmalarının (CBOW ve Skip-gram), farklı window size ve vector size değerlerinin metin benzerliği üzerindeki etkisini incelemek.

---

## Kullanılan Veri Setleri
- lemmatized_sentences.csv
- stemmed_sentences.csv

---

## Kullanılan Yöntem
- Word2Vec (CBOW ve Skip-gram)
- Cosine Similarity
- Jaccard Similarity

---

## Model Yapısı
Toplam 16 farklı model eğitilmiştir:

- CBOW / Skip-gram
- window: 2 ve 4
- vector size: 100 ve 300

---

## Çalıştırma

```bash
pip install -r requirements.txt
