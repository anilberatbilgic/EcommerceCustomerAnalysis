# 🛒 E-commerce Customer Analysis

Exploring an online retailer's sales by country, then segmenting customers and recommending related products.

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-KMeans-orange.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg)

**🌐 Language:** English · [Türkçe](#-türkçe)

## 🧭 Overview

This project looks at an online store's transactions from a **business angle** — *where* the customers are, *what* sells in each country — and then goes a step further: it **segments customers** and **recommends related products**.

## 📊 Dataset

**Online Retail** (`data.csv`) — transactions from a UK-based online store: `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, `Country`. Rows without a `CustomerID` are dropped.

## 🧠 Approach

1. **Cleaning** — drop missing `CustomerID`s and cast to integer.
2. **Exploratory analysis** — number of customers per country (top markets), and the **best-selling product in each country** (e.g. Australia → *"MINI PAINT SET VINTAGE"*, Canada → *"RETRO COFFEE MUGS ASSORTED"*).
3. **Segmentation** — **K-Means** clustering on customer behavior to group similar buyers.
4. **Recommendation** — an item-item **cosine similarity** matrix suggests related products ("bought together").

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
Bu proje bir çevrimiçi mağazanın işlemlerine **iş gözüyle** bakar — müşteriler *nerede*, her ülkede *ne* satıyor — ve bir adım öteye geçer: **müşterileri segmentlere ayırır** ve **ilgili ürünleri önerir**.

### Veri Seti
**Online Retail** (`data.csv`) — İngiltere merkezli bir çevrimiçi mağazanın işlemleri: `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, `Country`. `CustomerID` olmayan satırlar atılır.

### Yaklaşım
1. **Temizlik** — eksik `CustomerID` satırları atılır, tam sayıya çevrilir.
2. **Keşifsel analiz** — ülke bazında müşteri sayısı (en büyük pazarlar) ve **her ülkenin en çok satan ürünü** (ör. Avustralya → *"MINI PAINT SET VINTAGE"*, Kanada → *"RETRO COFFEE MUGS ASSORTED"*).
3. **Segmentasyon** — benzer alıcıları gruplamak için **K-Means** kümeleme.
4. **Öneri** — ürün-ürün **cosine similarity** matrisiyle ilgili ürünler önerilir ("birlikte alınan").

### Teknolojiler
`Python` · `pandas` · `numpy` · `scikit-learn` · `matplotlib` · `seaborn`

### Çalıştırma
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook EcommerceCustomerAnalysis.ipynb
```
Veri yolunu ayarla ve notebook'u baştan sona çalıştır.
