# myfitnesspal food database search

Send a query to myfitnesspal using requests and BeautifulSoup and receive nutritional information for up to 20 matching products

Usage:

```
>>> import myfitnesspal
>>> results = myfitnesspal.search('Kangaroo Sausages')
>>> results
[{'name': 'Sausages', 'brand': 'Kangaroo', 'Serving Size': '1 sausage', 'Calories': '77', 'Fat': '1.6g', 'Carbs': '5.2g', 'Protein': '9.6g'}, ...]
```

Uses [soupselect](https://github.com/simonw/soupselect) for HTML selectors
