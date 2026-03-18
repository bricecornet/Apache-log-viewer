# 🇫🇷 Apache Log Viewer (Local & Simple)

Un lecteur de logs Apache 100% local, simple et puissant, fonctionnant directement dans votre navigateur.

Aucune installation, aucun serveur, aucune dépendance backend : il suffit d’ouvrir le fichier HTML et de charger vos logs.

---

## 🚀 Fonctionnalités

* 📁 Import de fichiers `.log` (drag & drop ou sélection)
* ⚡ Analyse rapide côté navigateur (Web Worker)
* 📊 Tableaux de bord visuels avec Chart.js
* 🤖 Détection avancée des bots :

  * Googlebot, Bingbot, GPTBot, Ahrefs, Semrush, etc.
  * Détection générique des bots inconnus ("Autre bot")
* 🧑 Répartition **Humains vs Bots**
* 📄 Top 20 pages HTML/PHP visitées par les humains
* 📈 Évolution temporelle :

  * J-1, J-7, J-30, J-90, J-360 ou toutes les données
* 🚨 Analyse des erreurs HTTP (4xx / 5xx)
* 📂 Analyse des répertoires les plus sollicités
* 🔍 Exploration complète des logs avec recherche et tri

---

## 🔐 Respect de la vie privée

* ✅ 100% local (aucune donnée envoyée)
* ✅ Aucun tracking
* ✅ Aucun appel serveur

Vos logs restent sur votre machine.

---

## 🛠️ Technologies utilisées

* HTML / CSS / JavaScript
* Chart.js (visualisation)
* Grid.js (table interactive)
* Web Workers (performance)

---

## 📦 Utilisation

1. Télécharger le fichier HTML
2. Ouvrir dans un navigateur (Chrome recommandé)
3. Glisser-déposer votre fichier de log Apache

C’est tout.

---

## 🎯 Cas d’usage

* Audit SEO technique
* Analyse de crawl des moteurs
* Détection de gaspillage serveur
* Analyse du trafic réel vs bots
* Debug serveur web

---

## ⚠️ Limitations

* Fonctionne sur logs Apache classiques (format combiné)
* Très gros fichiers (>100MB) dépendront de votre machine

---

## 💡 Roadmap (idées futures)

* Filtre global Humain / Bot
* Export CSV / Excel
* Analyse par heure
* Détection anomalies SEO
* Dashboard avancé

---

![Apache log viewer](https://raw.githubusercontent.com/bricecornet/Apache-log-viewer/refs/heads/main/apache-log-viewer.png)

---

# 🇬🇧 Apache Log Viewer (Local & Simple)

A simple and powerful **100% local Apache log viewer**, running directly in your browser.

No installation, no server, no backend required — just open the HTML file and load your logs.

---

## 🚀 Features

* 📁 Import `.log` files (drag & drop or file picker)
* ⚡ Fast in-browser processing (Web Worker)
* 📊 Interactive dashboards powered by Chart.js
* 🤖 Advanced bot detection:

  * Googlebot, Bingbot, GPTBot, Ahrefs, Semrush, etc.
  * Generic fallback for unknown bots ("Other bot")
* 🧑 Human vs Bot traffic distribution
* 📄 Top 20 HTML/PHP pages visited by humans
* 📈 Timeline analysis:

  * Last 1, 7, 30, 90, 360 days or full dataset
* 🚨 HTTP error analysis (4xx / 5xx)
* 📂 Top requested folders
* 🔍 Full log exploration with search and sorting

---

## 🔐 Privacy First

* ✅ 100% local processing
* ✅ No data sent anywhere
* ✅ No tracking

Your logs never leave your machine.

---

## 🛠️ Tech Stack

* HTML / CSS / JavaScript
* Chart.js (charts)
* Grid.js (data table)
* Web Workers (performance)

---

## 📦 Usage

1. Download the HTML file
2. Open it in your browser (Chrome recommended)
3. Drag & drop your Apache log file

Done.

---

## 🎯 Use Cases

* Technical SEO audits
* Search engine crawl analysis
* Server waste detection
* Human vs bot traffic insights
* Web server debugging

---

## ⚠️ Limitations

* Works with standard Apache combined logs
* Very large files (>100MB) depend on your device performance

---

## 💡 Roadmap

* Global filter (Human / Bot)
* CSV / Excel export
* Hourly analysis
* SEO anomaly detection
* Advanced dashboard
