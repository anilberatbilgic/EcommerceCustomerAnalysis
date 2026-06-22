# 🛒 E-commerce Customer Analysis

Behavioral analysis of e-commerce customers — RFM segmentation plus a similarity-based product recommendation.

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg)

**🌐 Language:** English · [Türkçe](#-türkçe)

## 🧭 Overview

This project turns raw e-commerce transactions into actionable insight: it segments customers by value and behavior, and recommends products using item similarity — the two building blocks of personalized retail.

## 📊 Dataset

Online retail transaction records (invoices, products, quantities, prices, dates and customer IDs), loaded in Google Colab.

## 🧠 Approach

1. **Preprocessing** — clean the transactions and engineer **RFM** features (Recency, Frequency, Monetary) using `datetime`.
2. **Segmentation** — cluster customers with **K-Means** to reveal groups such as loyal, at-risk and new customers.
3. **Recommendation** — build an item-item **cosine similarity** matrix to suggest related products ("customers who bought this also bought…").
4. **Visualization** — explore distributions and segments with `matplotlib` and `seaborn`.

## 🛠️ Tech Stack

`Python` · `pandas` · `numpy` · `scikit-learn` (KMeans, cosine_similarity) · `matplotlib` · `seaborn`

## ▶️ How to Run

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook EcommerceCustomerAnalysis.ipynb
```

Set the dataset path, then run the notebook end to end.

---

<a name="-türkçe"></a>
## 🇹🇷 Türkçe

### Genel Bakış
Bu proje ham e-ticaret işlemlerini eyleme dönüştürülebilir içgörüye çevirir: müşterileri değer ve davranışa göre segmentlere ayırır ve ürün benzerliğiyle öneri yapar — kişiselleştirilmiş perakendenin iki temel taşı.

### Veri Seti
Çevrimiçi mağaza işlem kayıtları (faturalar, ürünler, miktarlar, fiyatlar, tarihler ve müşteri kimlikleri), Google Colab'da yüklenir.

### Yaklaşım
1. **Ön işleme** — işlemler temizlenir, `datetime` ile **RFM** öznitelikleri (Recency, Frequency, Monetary) üretilir.
2. **Segmentasyon** — **K-Means** ile müşteriler kümelenir (sadık, riskli, yeni gibi gruplar).
3. **Öneri** — ürün-ürün **cosine similarity** matrisiyle ilgili ürünler önerilir ("bunu alanlar şunu da aldı").
4. **Görselleştirme** — `matplotlib` ve `seaborn` ile dağılımlar ve segmentler incelenir.

### Teknolojiler
`Python` · `pandas` · `numpy` · `scikit-learn` · `matplotlib` · `seaborn`

### Çalıştırma
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook EcommerceCustomerAnalysis.ipynb
```
Veri yolunu ayarla ve notebook'u baştan sona çalıştır.
