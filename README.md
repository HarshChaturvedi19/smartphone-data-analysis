# 📱 Smartphones Dataset Analysis Project 😎

## 🎯 Project Overview

This project dives into the `smartphones-dataset.csv` to uncover trends, patterns, and insights about smartphones using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.  
From cleaning messy data to generating dynamic insights, we explored **price segments**, **camera specs**, **OS dominance**, and more to help consumers make informed choices! 🚀

- **Dataset**: 100 smartphones with columns like `model`, `price`, `rating`, `sim`, `processor`, `ram`, `battery`, `display`, `camera`, `card`, `os`.
- **Goal**: Clean, analyze, and visualize data to reveal market trends and value-for-money phones.
- **Tools**: Python 🐍, Pandas, NumPy, Matplotlib, Seaborn

---

## 🧹 Data Cleaning Process

We transformed the raw dataset into a clean, analysis-ready format using the following steps:

- **Model**: Stripped spaces, removed null/empty entries 🧼
- **Price**: Removed `₹` and commas, converted to float, dropped nulls 💰
- **Rating**: Imputed missing values with the mean (~78.5) ⭐
- **SIM**: Extracted boolean columns for 5G, NFC, and IR Blaster support 📶
- **Processor**: Categorized into brands (e.g., Snapdragon, Bionic), marked invalid entries as 'Unknown' 🖥️
- **RAM**: Extracted numeric values (e.g., "6 GB" → `6`), dropped nulls 🛠️
- **Battery**: Extracted capacity (e.g., "5000 mAh" → `5000`), removed outliers, added fast charging flag 🔋
- **Display**: Extracted screen size (e.g., "6.59 inches" → `6.59`), dropped nulls 📺
- **Camera**: Parsed rear camera setups and front resolutions, handled multiple lenses 📸
- **Card**: Created boolean column for memory card support, extracted capacity (e.g., "upto 1 TB") 💾
- **OS**: Categorized into Android, iOS, or Other 📱

---

## 🔍 Exploratory Data Analysis (EDA)

We ran 65+ queries and visualizations to derive insights:

- **Price Distribution**: Most phones are budget to mid-range (₹5,000–₹30,000) 📉
- **Rating vs. Price**: Moderate correlation (~0.45); some budget phones scored high 🌟
- **Camera Trends**: Premium phones often exceed 100 MP (e.g., Galaxy S23 Ultra: 200 MP) 🎥
- **OS Market**: Android dominates (~80%), iOS at ~10% 🍎🤖
- **Battery**: Mid-range phones (₹20K–₹50K) average ~4800 mAh 🔌
- **Visualizations**: Histograms, scatter plots, box plots, violin plots, heatmaps, stacked bar charts 📊

---

## 🏆 Key Insights

- **Value for Money**: Budget phones like *Moto G62 5G* and *Poco X4 Pro 5G* rival mid-range models 💸
- **Android Reigns**: ~80% Android market share; iOS users gave slightly higher ratings 🏅
- **Camera Leadership**: Premium phones (>₹50K) often include triple high-res setups 📷
- **Feature Trends**: 5G and fast charging are common in higher segments ⚡
- **Display Standard**: Most phones offer 6.0–6.9" screens for better media experience 🖼️

---

## 📈 Visualizations

To enhance understanding, we created the following plots:

- 📈 **Price Histogram**: Showed right-skewed price distribution  
- 📍 **Rating vs. Camera Scatter Plot**: Highlighted high-rated budget models  
- 📊 **OS Bar Plot**: Visualized Android vs iOS market share  
 
### 🖼️ Sample Charts

#### 1. Price Distribution of Smartphones

![Price Histogram](<price histogram.png>)
#### 2. Rating vs. Primary Rear Camera MP


![Rating VS Price](<ating vs Price.png>)


---

## 🛠️ Project Highlights

- **Dynamic Insights**: Printed real-time highlights like top phones per price range
- **Comprehensive Cleaning**: Parsed complex strings (e.g., “50 MP + 48 MP + 32 MP”)
- **Consumer Focused**: Identified best value-for-money phones for each segment
- **Scalable**: 65+ structured queries for different analysis angles

---

## 📝 Conclusion

This project showcased the diversity of the smartphone market:

- 💪 Budget phones can offer high specs at low cost  
- 🌍 Android dominates in volume; iOS leads in perceived quality  
- 📸 Premium phones push the limits of camera and features  
- ⚖️ Mid-range phones strike the best balance of price and performance  
- 🎉 Consumers today have a wide variety of good options

---

## 🚀 Future Work

- 📊 Brand-specific trend analysis (e.g., Xiaomi vs Samsung)
- 💬 Sentiment analysis from user reviews
- 🧠 Add machine learning for price prediction
- 📈 Build interactive dashboards using Plotly/Dash/Streamlit

