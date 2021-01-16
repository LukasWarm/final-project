## Project Background

With the Olympics fast approaching and the first introduction of climbing, this project set out to analyse competition results and athletes performances. The study focus' on athletes data and results in bouldering and lead climbing discipline. The scope involved top performing athletes in the adult/youth category but limited to IFSC World Championships and World Cup. The Word Championships and World Cup competitions were chosen because they are  most like the upcoming Olympic format. The aim was to explore this data visually and test the hypothesis if climbers perfrom differently in host countries using data visualisation and hypothesis testing.

### Hypothesis

HO: The host country does not affect the performance of climbers.

HA: The host country affects the performance of climbers.

## Data

Data source 1: Kaggle (web scraped IFSC competition results)

https://www.kaggle.com/brkurzawa/ifsc-sport-climbing-competition-results/tasks)

Data source 2: Kaggle (web scraped athlete data)

https://www.kaggle.com/anthonygiorgio/ifsc-climbing-competition-results-1991-2019

# Content

1-Cleaning/concatenating data (Jupyter Notebook)

2-Data exploration (Tableau, twbx file)

3-Original datasets & cleaned athletes data (csv)

3-presentation (presentation slides)

## Workflow

### 1. Cleaning/concatenating data 

- Dropping & getting rid of null values.
- Converting data types. 
- Separating youth and adult results.
- Cleaning and organising key identifier to concatenate athletes data.
- Configure new database with atheletes data combined with athletes results.

### 2. Data exploration

- Separate and compare overall competition results in both disciplines.
- Explore the impact of athlete details alongside performance.
- Exploring data limitations.

### 3. Hypothesis Testing

- For this study, limited to visualizations. 

## Limitations

Due to limitations of data, this study couldn't go under a traditional hypothesis testing format. Both datasets attached were in the end too nuanaced to perform hypothesis testing. This study visually explores the way in which the discpline and host countries could affect athlete behaviour but could not go beyond this stage. Unfortunately the IFSC API does not include full results, only overall ranking so individual performance is something that isn't possible to analyse at this stage. This study would do better following a different approach that I've set out below in the Next Steps section.

## Next Steps

To explore whether the host country has an affect on athlete performance - Explore nationality ranking and world cup performance for the whole World Cup and World Championships. 

## Conclusion 

My project became more of a descriptive study. We can accept “theoretical” null hypothesis but if anything it opens up more questions. Due to the limits of my data I couldn’t go beyond this.
There is a difference in demographics and popularity between both disciplines - The country could still affect performance but we would need more data (e.g funding & rankings of athletes over time). This study did successfully combine atheletes data with athlete results which can still be used for further analysis.



## References & Acknowledgements 

Brett Kurzawa, kaggle: (https://www.kaggle.com/brkurzawa/ifsc-sport-climbing-competition-results/tasks)

Antoine Bourcieu dissertation & Jim Lemmers  web scraping athlete information, kaggle: (https://www.kaggle.com/anthonygiorgio/ifsc-climbing-competition-results-1991-2019
