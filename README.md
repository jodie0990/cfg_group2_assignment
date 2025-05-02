# cfg_group2_assignment

# How Has Social Media Impacted Teenagers?

In this project, we examine the effect of social media on teenage mental health. Using data from multiple datasets, we analyze whether social media usage impacts mental health and whether that impact is related to specific platforms, usage time, gender, or other factors.

---


## API Reference – NewsAPI

This project uses the **NewsAPI** to fetch articles related to mental health, social media, and teenagers.

### �� Query Parameters

| Parameter   | Type   | Required | Description                                                               |
|-------------|--------|----------|---------------------------------------------------------------------------|
| `q`         | string | Yes      | Keywords or phrases to search in the article title and body              |
| `from`      | string | No       | Start date for the news (e.g., `2024-04-01`)                             |
| `language`  | string | No       | Language code (e.g., `en` for English)                                   |
| `sortBy`    | string | No       | Sort by `publishedAt`, `relevancy`, or `popularity`                      |
| `page`      | int    | No       | Page number of the results to fetch                                      |
| `pageSize`  | int    | No       | Number of results per page (maximum 100)                                 |
| `apiKey`    | string | Yes      | Your personal NewsAPI key                                                |

### API Limits (Free Tier)

| Limit Type              | Value         |
|-------------------------|---------------|
| Max requests per day    | 100           |
| Max articles per request| 100           |
| Max `pageSize` value    | 100           |
| Search date history     | Last 30 days  |

---
## Required Libraries

Ensure the following Python libraries are installed:

```bash
pip install requests pandas numpy textblob matplotlib seaborn
```

Additionally, the project uses the built-in `time` module.

---

## Datasets Used

- **dataset_1.csv** – [Mendeley Data](https://data.mendeley.com/datasets/vftw9cz723/2)  
- **dataset_2.csv** – [Kaggle](https://www.kaggle.com/datasets/aniruddhawankhede/mental-heath-analysis-among-teenagers/data)  
- **dataset_3.csv** – [Kaggle](https://www.kaggle.com/datasets/souvikahmed071/social-media-and-mental-health)
## Authors

- [Antonia Badozi](https://www.github.com/abadozi)
- [Bethany Blakeley](https://www.github.com/BethJB)
- [Jodie Christian](https://www.github.com/jodie0990)
- [Fariha Parvin](https://www.github.com/farihaparvin)
- [Humairaa Patel](https://www.github.com/humiraa)
- [Helena Scotland](https://www.github.com/helenaolivias)
- [Becky Webster](https://www.github.com/bweb85)


## �� Acknowledgements

- Thanks to **Helena Blackmore**, **Chelsi G**, **Stavros Ioannidis**, and **Ibrahim Kamulegeya**  of CFG for their instruction and guidance.
- Thanks to **Mendeley Data** for providing data on Social Media Addiction (dataset 1).
- Thanks to **Aniruddha Wankhede** for providing data on Mental Health in Teenagers (dataset 2).  
- Thanks to **Souvik Ahmed** and **Muhesena Nasiha Syeda** for sharing their data via Kaggle (dataset 3).
Collapse









