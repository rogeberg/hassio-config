# Nordpool spot price extractor for Home-assistant

### Disclaimer
Source code/Software provided by Olav André Omdal is for illustrative purposes only which provides
users with programming information regarding the products.
This software is supplied "AS IS" without any warranties and support.

Olav André Omdal assumes no responsibility or liability for the use of the software,
conveys no license or title under any patent, copyright, or mask work right to the product.

Olav André Omdal reserves the right to make changes in the software without notification.
Olav André Omdal also make no representation or warranty that such application will be suitable
for the specified use without further testing or modification.

By downloading this code, you agree to follow Nordpool's terms and conditions regarding
the use of their data.

### Installation:
Put the nordpool.py file in your custom_components/sensor/ folder located in your config folder.

### Add the sensor to your config file:

    sensor:
      - platform: nordpool
        currency: 'NOK'
	    region: 'Kr.sand'
	    name: "Elspot kWh"

### Options:
currency: DKK,EUR,NOK or SEK

region: DK1,DK2,EE,FI,LT,LV,Oslo,Kr.sand,Bergen,Molde,Tr.heim,Tromsø,SE1,SE2,SE3,SE4,SYS

(CaSe seNsITive!)

