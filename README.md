# metropcs-tradein
import requests\
url = "https://www.metrobyt-mobile.com/api/v1/catalog/trade-in-quotes/devices" \
headers = {"content-type": "application/json"}\
body = {"programType":"METI"}\
r=requests.post(url,headers=headers, json=body).json()
