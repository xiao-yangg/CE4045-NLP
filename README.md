# CE4045-NLP
Twitter Tweets Dataset on Apple Consumer Sentiments

Update ```commit``` for tweets dataset every Fri till submission of Natural Language Processing project due on 6 Nov - Week 12 Sunday)

Use *url* to obtain

**Combined Data**: https://raw.githubusercontent.com/X-Yang98/CE4045-NLP/main/combined_dataset.csv?token=GHSAT0AAAAAABW62M762KTO2ARR6YZFBOAUYZ4DURA

**Training Data**: https://raw.githubusercontent.com/X-Yang98/CE4045-NLP/main/training_dataset.csv?token=GHSAT0AAAAAABW62M76ITOBEBWV4U7ZUXR6YZ4DW3Q

**Test Data**: https://raw.githubusercontent.com/X-Yang98/CE4045-NLP/main/test_dataset.csv?token=GHSAT0AAAAAABW62M76SS2ZH4BKUBIF352EYZ4DXQQ

For example:

```
import pandas as pd

url = 'raw_GitHub_link'

df = pd.read_csv(url)
df.head()
```
