from bs4 import BeautifulSoup
import requests
                   #https://google.com 
req = requests.get("https://google.com")
bs = BeautifulSoup(req.text,"html.parser")
for link in bs.findAll('a'):

    print(link.get("href"))
