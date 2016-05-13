# Zomato-Python
A python Zomato API wrapper.

##### For more information on Zomato API and Zomato API key
Visit : https://developers.zomato.com/api#headline1

##Usage:
```python
from zomato import Zomato
z = Zomato("ZOMATO-API-KEY")
# A call to categories endpoint from zomato API.
z.parse("categories","")
# A call to restaurants endppoint from zomato 
# API with required parameters res_id
z.parse("restaurant","res_id=16774318")
```
