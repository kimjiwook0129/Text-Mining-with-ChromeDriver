# Text-Mining-with-ChromeDriver [크롬 드라이버를 이용한 텍스트 마이닝]

This is not my original work, I have expanded its usage (Copyright below). [원작자 및 Copyright에 대한 언급은 아래 있습니다.]

1. Using a web crawler, collect data about Wiki's recent changes. https://namu.wiki/RecentChanges
2. Extract keywords from the collected data.
3. Visualize the analyzed kewords via wordcloud.

### Notebooks Order [노트북 순서]

1. [URL Collection](/url_collection.ipynb)
2. [Data(Text) Collection](/data_collection.ipynb)
3. [Keywords Extraction](/extraction.ipynb)
4. [Word Cloud Visualization](/visualization.ipynb)

### ChromeDriver Setup [크롬 드라이버 셋업]

- Download chromedriver from:
  https://sites.google.com/chromium.org/driver/downloads

- Move the chromedriver executable file to the '/usr/local/bin'

### Collect data using a web crawler [웹 크롤러를 이용해서 데이터 수집하기]

### Text Analytics [텍스트 분석]

### Data Visualization [데이터 가시화]

Make sure to move a new font .ttf file (ex. [NanumBarunGothic.ttf](http://hangeul.naver.com/webfont/NanumGothic/NanumGothic.ttf)) to the paths listed below

Mac OS : /{anaconda_path}/envs/{env_name}/lib/python3.8/site-packages/pytagcloud/fonts

Windosw OS : {anaconda_path}\envs{env_name}\Lib\site-packages\pytagcloud\fonts

Append the code block below to the font.json located at the paths listed above

```json
,{
"name": "NanumGothic",
"ttf": "NanumGothic.ttf",
"web": "http://fonts.googleapis.com/css?family=Nanum+Gothic"
}
```

Copyright (c) 2019 [윤기태]

https://github.com/yoonkt200/python-data-analysis
