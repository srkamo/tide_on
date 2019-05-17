import requests
import json

http = 'https://tidesandcurrents.noaa.gov/api/datagetter?begin_date=20130808 15:00&end_date=20130808 15:06&station=' \
       '8454000&product=datums&units=english&datum=MTLtime_zone=gmt&application=ports_screen&format=json '

response = requests.get(http)
#print(response.content)
print(json.loads(response.content))