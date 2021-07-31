# Indian-Startup-Analysis

## Made by - 
## 1. Muskan Chavan
## 2. Shrutika Shinde
## 3. Divyangi Kolhe

This project is based on a in-depth analysis on the Indian Startups Funding Dataset taken from kaggle.com. From this analysis, We intend to answer questions related to the Indian Start-ups such as:-

* What is the Quarterly trend in the number of startups funded in the given duration?
* Which startups got the highest funding? (OR) List the Top 10 startups based on the amount funded to them.
* Which Industry is more favored for funding by investors? Which cities have the most number of startups funded?
* Who are the important investors in the Indian Start-ups?
* What are the most common types of investments made by investors?

# Technologies Used:
* Python
* Pandas
* Matplotlib
* Seaborn

# What Is a Startup?
A startup is a young company founded by one or more entrepreneurs to develop a unique product or service and bring it to market. By its nature, the typical startup tends to be a shoestring operation, with initial funding from the founders or their friends and families.

# Why should a startup need funding ?
Attract the attention of the market and the future investors by having business funding. If your startup is getting funding from venture capital, or another business form, signalizes that you're positioned for the future. Funding increases your visibility and attracts the attention of the market.

# Which year Startups are we looking at ? 
We're going to consider startups from January 2015 to December 2017

# Q1. Top 20 Startups on the basis of funds acquired

| Startup Name	  | Amount In USD|
| --------------- |:------------:|
|	paytm	          | 2340000000   |
|	flipkart        |	2259700000   |
|	ola	            | 1899500000   |
|	snapdeal	      | 700000000    |
|	oyo rooms	      | 375000000    |
|	quikr	          | 230000000    |
|	delhivery	      | 215000000    |
|	foodpanda	      | 210000000    |
| shopclues       |	207700000    |
|	bigbasket       |	207000000    |
|	cartrade	      | 200000000    |
|	makemytrip	    | 180000000    |
|	byju’s          |	175000000    |
|	hike	          | 175000000    |
|	practo          |	175000000    |
|	swiggy          |	170500000    |
|	grofers         |	165000000    |
|	oyorooms        |	162000000    |
|	freecharge      |	137000000    |
|	ecom express    |	137000000    |

![](/images/1top20startups.png)

The above Output shows the top 20 startups funded between January 2015 to December 2017. Paytm and Flipkart are the highest funded startups.

# Q2. Startup(s) which acquired the minimum amount of funds
Minimum funds acquired by a startup:  16000.0
*Yo Grad*, *Hostel Dunia, Plan Your Sport, Enabli*, and *CBS* are the startups who acquired least funding, that is, $16000

# Q3. Which Industry has maximum number of startups?
The top 3 industries having max number of startups are:

![](/images/2.png)
*Consumer, Internet Technology, ECommerce*

# Lets have a look at each industry from a closer point of view
# 1. Consumer Internet

Checking out top 10 sub-categories of industry having highest number of startups
![](/images/3consumerinternetsub-category.png)

*Food Delivery Platform has 8 startups, followed by Online Lending Platform, Online Learning Platform, and Fitness Mobile App having 5,4, and 3 startups listed respectively*
# Top consumer internet startups

| Startup Name  | Amount In USD |
| ------------- |:-------------:|
| ola           | 744500000     |
| oyo rooms     | 250000000     |
| cartrade      | 200000000     |
| makemytrip    | 180000000     |
| hike          | 175000000     |
| swiggy	      | 137000000     |
| byju’s	      | 125000000     |
| oyo	          | 100000000     |
| mobikwik	    | 90000000      |
| bookmyshow	  | 82000000      |

# 2. Technology
# Top Technology based startups on the basis of funds acquired

| StartupName	        | Amount In USD |
| -----------------   |:-------------:|
|	delhivery           |	100000000     |
|	fractal analytics 	| 100000000     |
|	rivigo              |	75000000      |
|	markets and markets |	56000000      |
|	druva               |	51000000      |
|	icertis             |	40000000      |
|	eps                 |	35000000      |
|	amagi media labs    |	35000000      |
|	mswipe              |	31000000      |
|	qubole              |	30000000      |

*Delhivery, Fractal Analytics, Rivigo* are top Technology based startups
# 3. ECommerce
# Top ECommerce based startups on the basis of funds acquired

| Startup Name        | Amount In USD |
| -----------------   |:-------------:|
|	paytm	              | 1660000000    |
|	flipkart            |	1509700000    |
|	snapdeal	          | 200000000     |
|	bigbasket           |	157000000     |
|	shopclues	          | 107700000     |
|	lenskart            |	63500000      |
|	pepperfry	          | 31300000      |
|	1mg	                | 30000000      |
|	bluestone	          | 30000000      |
|	voonik	            | 29000000      |

*Paytm, Flipkart, SnapDeal* are top ECommerce based startups with highest amount funded
![](/images/4top10sub-categoriesinecommerce.png)
There are 6 startups based on Online Pharmacy sub-category, followed by 3 startups in ECommerce Marketplace Sub-Category.

# Q4. Which period had the most number of startups funded.
![](/images/5quarterly%20trend.png)
Now, we can see that 2015, and 2016 saw most number of startups being funded. highest being in Quarter 3 of 2015. Then it started declining in 2017 Q1 to 166 startups and 2017 Q4 down to only 52 startups being funded
# Q5. which City has maximum startups?
![](/images/6.png)
As we see from the graph above, maximum number of startups are based in Banglore (26.72%), followed by Mumbai (18.9%), New Delhi (16.2%), and Gurgaon (10.16%)
72% of the startups funded between January 2015 till December 2017 are based in the above mentioned four cities.

# Q6. Who are the Top Investors by number of startups funded.

| Name	               | Number of Startups Funded   |
| -------------------- |:---------------------------:|
| Sequoia Capital      | 74                          |
| Accel Partners       | 63                          |
| Kalaari Capital      | 51                          |
| Blume Ventures       | 47                          |
| SAIF Partners	       | 45                          |
| Indian Angel Network | 42                          |
| Tiger Global	       | 41                          |
| IDG Ventures	       | 40                          |
| Ratan Tata           | 30                          |
| Mohandas Pai	       | 29                          |

![](/images/7.png)

# Q7. Which are the most common Investment types?
![](/images/8.png)

# Conclusion
So, this was all our analysis, we got to know about the industries favored by investors, common investment types, and many more interesting observations about the Indian Startup Ecosystem. We also got to know that the year 2015 and 2016 were the booming years for Indian startups, with the most number of startups funded, and gradually started declining in 2017. A factor that could contribute to this sharp decline would be the announcement of Demonetization by the Indian Government in November 2016.

To know more about the project click here -
[Indian Startups Analysis](https://github.com/muskanchavan17/Indian-Startup-Analysis)
