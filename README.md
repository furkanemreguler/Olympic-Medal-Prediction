# Olympic Medal Prediction

A machine-learning project that uses historical Olympic data to predict the number of medals each country will win in future Games.

---

## 📋 Table of Contents

- [Project Overview](#project-overview)  
- [Data](#data)  
- [Requirements](#requirements)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Contributing](#contributing)  
- [License](#license)

---

## 🏅 Project Overview

This notebook (`model.ipynb`) explores and models Olympic participation data (number of athletes, previous medals, demographic features, etc.) to forecast each country’s medal count in upcoming Games.

---

## 📊 Data

- **`teams.csv`**  
  - **team**: 3-letter country code (e.g. `USA`, `CHN`)  
  - **country**: full country name  
  - **year**: Olympic year  
  - **events**: number of events entered  
  - **athletes**: number of athletes sent  
  - **age**, **height**, **weight**: average athlete demographics  
  - **medals**: medals won that year  
  - **prev_medals**, **prev_3_medals**: medal counts in prior Games

--- 

## ⚙️ Requirements

See [requirements.txt](requirements.txt) for the full list of dependencies. Key packages:

```text
pandas
numpy
scikit-learn
seaborn
python-dateutil
pytz
six
