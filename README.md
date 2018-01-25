# Welcome to GrowAss!

IoT Grow Assistant (GrowAss) is a collection of information to create an automated indoor grow tent for anything from roses to, obviously, cannabis.

GrowAss starts as a collection of items you'd need to grow your plants. You can get most of the items needed from Amazon and you'll be provided a list of links. For the sake of full disclosure, the links are affiliate links, and they help fund this project.

Once you have acquired the parts necessary, you will move on to implementation, where you will hook up and automate all the equipment, source code and diagrams included.

After everything is set up, you will install the public server side of things, which will let you manage your grow tent remotely.
# Motivation
Urban Farming. I believe if we can bring the garden into our house we can solve a huge environmental problem while increasing the quality of the food we consume on daily basis. 
A space as little a 4 sqft can be used to keep fresh staple vegetables year round. It can also generate over 3 pounds of cannabis flower every 3-6 months.
I also like electronics :)

# Benefits

 - Automate most of the work to grow any plant.
 - Monitor environmental factors real time.
 - Monitor your plant through pictures.
 - Create time-lapses of your plant growing.
 - Works for any plant:
	 - Tomatoes
	 - Roses
	 - Lettuce
	 - Cannabis
	 - Watermelons!
 - Works with any technique:
	 - Soil
	 - Hydro
	 - Aero

## Economics
The goal was to build a fully automated system for a 4 sqft space for under $400, starting from 0 and including **everything**.

**Power** was also a concern,  I didn't have an actual expectation, but based on the readings it comes down to about 3kwh per day during vegetative light conditions (18/6), this also includes all electronics involved. That in San Diego, CA, translates to about $1.20/day or $36/month. Presumably, during the flowering stage, it will be 25% cheaper.

**Water**, I use water from the source, not filtered water. I think it has its benefits having the natural minerals in there. It costs about $20 for a whole growth.

**Based on Cannabis**: Your first grow will cost about $600, but if you follow the instructions and get good genetics you can get up to 2 pounds worth $2000. After that, each 4-5 month harvest will cost your about $50/month.

**Based on Vegetables**: Your first grow will cost about $600, you can achieve higher and more frequent yields with vegetables or tomatoes than you do with cannabis, this means you will make up for the price in just a couple of months with the added benefit of knowing exactly what you're putting in your mouth.

## Shopping List
All your files are listed in the file explorer. You can switch from one to another by clicking a file in the list.

| Item |  Quantity | Unit Price | Total Price | Link|
|--|--|--|--|--|
|Smart Plugs|1|26.99|26.99| [Amazon.com](https://www.amazon.com/gp/product/B06XSTJST6/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B06XSTJST6&linkCode=as2&tag=growass-20&linkId=eb3d8085c1a73973ff27f7529c4b512f)|
|Dupont Wire|1|7.86|7.86|[Amazon.com](https://www.amazon.com/gp/product/B01EV70C78/ref=as_li_tl?ie=UTF8&tag=growass-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=B01EV70C78&linkId=a0907a23f89360a27f405cad9c4160af)|
|Temp Sensors|1|7.99|7.99|[Amazon.com](http://amzn.to/2Fb4ayc)|
|Rasp Pi 3|1|36.94|36.94|[Amazon.com](http://amzn.to/2DBYuNf)|
|Irrigation System|1|11.99|11.99|[Amazon.com](http://amzn.to/2DxqNfF)|
|Water Pump|2|29.91|59.82|[Amazon.com](http://amzn.to/2DHv8QF)|
|USB Fans|4|7.09|28.36|[Amazon.com](http://amzn.to/2Dznapy)|
|Trellis Netting|1|6.99|6.99|[Amazon.com](http://amzn.to/2rH4Mtu)|
|Indoor Thermometer|1|9.36|9.36|[Amazon.com](http://amzn.to/2Gh1Jvo)|
|USB&120V Power Strip|1|16.99|16.99|[Amazon.com](http://amzn.to/2Gh67dt)|
|Grow Tent|1|51.99|51.99|[Amazon.com](http://amzn.to/2DBgeII)|
|300W LED|1 |75.99|75.99|[Amazon.com](B00PH1MQV8)|
|USB Switchable Hub|1|16.99|16.99|[Amazon.com](http://amzn.to/2Brm51i)|
|150 LadyBugs|1|4.00|4.00|[Amazon.com](http://amzn.to/2n9nVP6)|
|Extension Cord|1|9.33|9.33|[Amazon.com](http://amzn.to/2E9Syfe)|

Total Hardware Costs: $373.76 
[As of January 25, 2018]

## Putting it together

### Tent
Assemble Tent based on instructions. Make sure to choose a good space. Somewhere cool and dark, maybe a walking closet, a loft, an empty bedroom. If the weather allows, you can bring your tent outside.
Locate your tent close to at least two power outlets.

