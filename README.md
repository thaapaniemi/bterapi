#bterapi
Python class for Bter api.

##Usage example
	from decimal import *
	from bterapi import bterapi

	api = bterapi(key,secret)

	api.GetInfo()
	api.PlaceOrder("xpm_btc","BUY",Decimal("0.001"),Decimal("1.0"))
	api.PlaceOrder("xpm_btc","SELL",Decimal("0.1"),Decimal("1.0"))


##Credits
thaapaniemi ( https://github.com/thaapaniemi/bterapi )
t0pep0 ( https://github.com/t0pep0/btc-e.api.python )

##License
GNU GENERAL PUBLIC LICENSE v3
