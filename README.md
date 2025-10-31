# 📊 Data Science Portfolio in R  
![Made with R](https://img.shields.io/badge/Made%20with-R-blue?logo=r&logoColor=white)

Questo repository raccoglie **5 progetti di analisi dati e modellizzazione statistica in R**,  
che spaziano dal controllo qualità del vino bianco alla previsione dell’indice S&P500.  

Ogni progetto è sviluppato in **RMarkdown (.Rmd)** o **Quarto (.qmd)**, con codice riproducibile, grafici ed interpretazioni.

---

## 📁 Panoramica dei Progetti

| # | Titolo | Obiettivo | Tecniche Principali |
|---|---------|------------|--------------------|
| 1️⃣ | [Controllo Statistico del Vino Bianco]| Analizzare la qualità e la stabilità produttiva | Statistica descrittiva, ANOVA, PCA, Carte di controllo |
| 2️⃣ | [Regressione Logistica su Pazienti Diabetici] | Predire presenza di diabete | Logistic Regression, ROC, Confusion Matrix |
| 3️⃣ | [Regressione Spaziale sulle Case di Boston]| Relazione tra prezzo e posizione geografica | Moran’s I, SAR, SEM |
| 4️⃣ | [Clustering delle Holding Aziendali] | Identificare pattern di concentrazione proprietaria | K-Means, PCA, Silhouette |
| 5️⃣ | [Analisi delle Serie Storiche sull’S&P500] | Analisi e previsione dei mercati | ARIMA, GARCH, Forecast |

---

## 1️⃣ Controllo Statistico del Vino Bianco  

**🎯 Obiettivo:**  
Verificare la qualità del vino bianco analizzando parametri chimici e il controllo del processo produttivo.  

**📦 Pacchetti principali:**
```r
library(tidyverse)
library(ggplot2)
library(factoextra)
library(qcc)
library(car)
