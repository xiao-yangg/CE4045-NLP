# CE4045-NLP
Twitter Tweets Dataset on Apple Consumer Sentiments

Use *url* to obtain

**Combined Data**: intrepret test dataset as overall dataset for training and testing

**Training Data**: taken from Kaggle (source: https://www.kaggle.com/datasets/yasserh/twitter-tweets-sentiment-dataset)

**Test Data**: scraped tweets using Twitter API with Apple hashtags on ```26 September 2022```

For example:

```
import pandas as pd

url = 'raw_GitHub_link'

df = pd.read_csv(url)
df.head()
```
