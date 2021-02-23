This repo serves as a way to download about 4000 Pdf containing joint commissions (commissions paritaires) ranging from jan 2018 to febr 2020.

# Why 

# What
this repo is containing
- a json file (jc.json). Each of it's json object contains a route to each pdf (documentLink field)
- venv folder containing the needed virtual envirement if you wish to run the code yourself.
- data folder containing all the pdfs
- jc_dowload_script.py file script to download all the pdfs

the json object looks like this:
![alt text](https://github.com/Cassik6/commissions-paritaires/blob/main/assets/requestjson.jpg?raw=true)

if you want to download your own json you can do so but querying the https://emploi.belgique.be/ API endpoint https://public-search.emploi.belgique.be/website-service/joint-work-convention/search using a POST request containing a json in the body. The request json looks like this:




# How
Note that the pdf files are already downloaded, but the code is still provided so you could do it yourself if need be.

1. Install 




