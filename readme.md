## Authors José luis Íñigo
## website: Diseñowebensevilla.org
## License mit: MIT License

In this new program you download image with column[0].jpg (from csv with title and sku) name and save url src in csv with sku and title for your easy import in woocommerce

1º We need to have Python3 installed
2º Install selenium y webdrive
```python
py install selenium
py install webdrive
```

For execute 
```python
py google.py
```

#Know how
1º In google.csv you need put csv with column[0]= title ------ in column[1] = sku
2º in output rturns some columns + column[2] with image src in jpg
3º You need programs in wordpress or woocomerce for import these data with id=sku and download image . You can use wp all import

