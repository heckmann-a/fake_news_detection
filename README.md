# fake_news_detection
<img src="https://github.com/user-attachments/assets/7e604587-edfb-44d5-a541-d9d1187704d6" alt="Bildbeschreibung" width="600"/>

Bild von Hartono Creative Studio auf Unsplash:[link](https://unsplash.com/de/fotos/ein-fake-news-megaphon-mit-dem-wort-fake-news-HQhgbdwHmSM)

## Mein Projekt steht auf GitHub zur Verfügung und lässt sich direkt ansehen: 
[Zum Notebook](https://colab.research.google.com/github/heckmann-a/fake_news_detection/blob/main/Fake_News_Detection.ipynb)

&nbsp;

# Aufgabenstellung:
Es wurden 2 Datensätze (Fake.csv, True.csv) bereitgestellt, die auf realen Daten basieren.\
Die wahrheitsgemäßen Artikel wurden durch Crawlen von Artikeln von Reuters.com gewonnen.\
Die Fakenews-Artikel stammen von unseriösen Webseiten, die von "Politifact" (einer Faktencheck-Organisation in den USA) und Wikipedia gemeldet wurden.

Ziel ist es hierbei, ein Modell zu entwickeln, welches relativ genau unterscheiden kann, ob es sich bei einem Artikel um Fake News handelt oder nicht.

# Datenquellen:
[(Datensätze: Kaggle.com)](https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets/data)\
*Der verwendete Datensatz stammt aus Kaggle und unterliegt der Lizenz 'Unknown'.\
Dieses Projekt dient ausschließlich zu Lern- und Demonstrationszwecken und wird nicht für kommerzielle Nutzung eingesetzt.*

# Technologien & Libraries:
* Python in Jupyter Notebook
* libs: pandas, numpy, seaborn, sklearn, lgb, TfidfVectorizer, CountVectorizer, MultinomialNB

# Beschreibung des Vorgehens:
* Einlesen und Vorverarbeitung der Daten
* Explorative Datenanalyse
* Modellierung
* Ergebnisse der Modelle

# Ergebnisse:
Genauigkeit der Modelle (absteigend):

- LightGBM + TfidfVectorizer -> 99,86 %
- Logistische Regression + TfidfVectorizer -> 99,17 %
- MultinomialNB + CountVectorizer -> 97,61 %
- MultinomialNB + TfidfVectorizer -> 96,22 %

![score](https://github.com/user-attachments/assets/abca233f-37dd-418b-854e-064f9dee9cf0)
