# Data Lineage: Where 'It Depends' Finally Gets an Answer

Talk I gave at PyData Kaunas about data lineage and how I've seen this problem being solved in different companies.

[Slides](https://www.canva.com/design/DAGW8Dns8IY/4LNNO5PGoXDXFKlSbDUmLA/edit?utm_content=DAGW8Dns8IY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

Code is quite raw in some places to show case some examples.

Two cells have almost identical code, idea there was to showcase how qualify works and how we can get information by expanding * in code.

difference in code basically is
```python
ast = qualify(parse_one(sql), expand_stars=True)
```

Code also was kind of built on spot and designed just for quick exploration.