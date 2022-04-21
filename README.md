# ROC_dataset
This is a dataset composed of news articles from patriarch.ia (02-12-2018 -> 04-09-2021 for English) (05-08-2005 -> 09-10-2021 for Russian)

The structure of this dataset is a simple json file for now built from a pandas df and expected to be imported intosaid dataframe (pickle is not used due to vulnerabilities in the pickle package). Future training datasets are in the works along with a Russian and English religious language model.
```
{"title":
  {"<row index 0>":
    "<title text unicode string>",
  "<row index 1>":
    "<title text unicode string>"},
  ...
}
{"news_text <unicode string>":
  {"<row index 0>":
    "<news text unicode string>",
  "<row index 1>":
    "<news text unicode string>",
  ...
}
{"date_time <string>":
  {"<row index 0>":
    "<date time code>",
  "<row index 1>":
    "<date time code>",
  ...
}
```
