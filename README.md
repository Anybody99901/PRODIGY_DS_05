# 🚗 Prodigy Infotech Internship - Task 5

## Project: UK Road Traffic Accident Analysis

As part of my internship with **Prodigy Infotech**, I worked on analyzing real-world road accident data to uncover patterns based on **weather**, **road conditions**, and **time of day**. The goal was to spot potential accident hotspots and understand the key contributing factors.

---

## Dataset Used

I used the **UK Road Safety Data**, available on Kaggle, which contains thousands of accident records across the UK.

- Key features: `Date`, `Time`, `Latitude`, `Longitude`, `Weather_Conditions`, `Road_Surface_Conditions`, `Light_Conditions`, `Accident_Severity`, and more.
- You can find the dataset here: [UK Road Safety Dataset - Kaggle](https://www.kaggle.com/datasets/salmaneunus/uk-road-safety-data)

---

## Tools & Libraries

- Python (Google Colab)
- pandas, matplotlib, seaborn (for data cleaning and visualization)
- folium (for mapping accident locations)

---

## What I Did

Here’s a quick breakdown of the steps I followed:

1. **Loaded and cleaned the data**  
   - Checked for null values and handled them
   - Converted time and date into proper formats

2. **Time-based analysis**  
   - Extracted accident trends by **hour** and **day of the week**
   - Identified when accidents are more likely to happen

3. **Weather & road condition insights**  
   - Compared accident severity and frequency under different weather and road conditions

4. **Mapped accident hotspots**  
   - Used **Folium** to generate an interactive heatmap of accident-prone locations

---

## Key Takeaways

- Most accidents occurred during the **evening rush hours**
- **Fridays** and **weekends** had more accident cases than other weekdays
- While many accidents happened in good weather, **slippery roads** and **rainy conditions** increased severity
- Major cities like **London**, **Manchester**, and **Birmingham** showed dense clusters of incidents

---

## Visual Highlights

I’ve included some key visualizations:

- Accident frequency by hour and weekday
- Road and weather condition breakdown
- Heatmap of high-risk zones across the UK

---

## How to Run the Project

### Option 1: Run on Google Colab  
Just open the notebook here:  
[**Open in Colab**](https://colab.research.google.com/drive/1Wa6QKkr_tbR2a_dDs5jL5QLjsT2wNToG#scrollTo=yR521CDHU9be)

### Option 2: Run Locally  
Install the required libraries and run the script:

```bash
pip install pandas seaborn matplotlib folium
python uk_accident_analysis.py
