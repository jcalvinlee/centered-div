# CenteredDiv

### Problem Formulation: [9th Sep, 23:55]

### 1. Is the problem relevant a year/2-years/5-years/10-years from now?

#### Problem statement: Food nutrition labels and their comparability

  Grocery shopping is relevant to most, if not all of us. As consumers, we often take into account pricings and our unique personal preferences when we are shopping for groceries. Increasingly, many of us are becoming health-conscious in our lifestyle and specifically diet plans. However, it is often tedious for consumers like us to compare nutrition values for products of different brands.

  For instance, if one would like to find the 3 in 1 coffee with the lowest sugar content available in Singapore, he/she would have to manually compare the nutrition values of the product of different brands by searching for the product on the website/mobile applications of grocery stores and scrutinize the product screenshots (refer to screenshot below). Existing groceries websites or mobile applications do not allow searching for products by nutrition values.
    <p align="center">
     <i>Screenshots from Redmart and FairPrice</i>
    </p>	
    <p align="center">
    <img src="https://iili.io/6BFSp4.md.png"  border="0"  width="400">
    <img src="https://iili.io/6BKuFn.md.png"  border="0"  width="400">
   </p>
  Additionally, there is no consistent format in the presentation of nutrition values by different brands. Referring to the same screenshots above, the information on Sodium content is available for Old Town coffee but not Nescafe. This further adds on to the complexity and tediousness of comparison.

  We do perceive the problem statement will likely remain relevant in the long term as more consumers become health conscious in their lifestyle.

### 2. What is the challenging aspect of the problem? Have others not thought of the problem or is the solution difficult to come up with?

  The main challenge of this problem is the difficulty in digitizing the data for efficient comparison. Currently, there is no database available that stores the nutritional data of products in Singapore/South East Asia. In addition, the nutritional data of these products are mostly available in the form of physical labels, pictured below, or in the form of images where the data cannot be easily tabulated.

  <p align="center">
   <i>Screenshot of physical nutritional label on granola box</i>
   </p>
  <p align="center">
  <img src="https://onecms-res.cloudinary.com/image/upload/s--BB0aXEcW--/c_fill%2Cg_auto%2Ch_676%2Cw_1200/f_auto%2Cq_auto/v1/tdy-migration/eglabels1_0.jpeg?itok=4t7gRPDE" alt="drawing" width="400"/>
  <p align="center">
	  
  Most nutritional data found online are based on generic food items, e.g. bananas, oats, chicken. They do not represent the true nutritional value of the off the shelf products that we buy, due to the addition of other ingredients or preservatives. As such, the most reliable information would be obtained directly from the label on the product itself.

  Although similar applications do exist in other locations such as in the US, these apps are not accustomed to residents of Singapore/SEA as the products available in these applications are different. This solution aims to cater specifically to Singapore/SEA, by focusing on the off the shelf products available in the region. 


### 3. What is your approach to solving it? What is novel about the solution?
   #### Our solution
   The proposed solution is a web application that allows users to browse through off the shelf products in the database and compare the associated food nutrition values with similar products across different brands (e.g. Nestle yogurt against Marigold yogurt), or with other different products (e.g. Nestle yogurt against Meiji milk), in a consistent format.

   The web application provides a front-end display/user interface to query the database and compare off the shelf products, as well as features to enter new or updated nutrition values to the database from users.
   #### Look up and compare
   We plan to implement a search system that allows users to 
      - Search for products by category, e.g. milk, bread, canned goods and rank by nutrition values and
      - Sort products by certain selected criteria, e.g. high protein or sugar content per 100mg.
   #### Enter new or updated nutrition values
   The initial set of nutritional data will be manually inserted with gathered data and subsequently allow users to upload through the platform. Users will be able to input data and verify information accuracy. The information with the most positive verifications will be the default data presented when a product information is requested (verification system works similar to a voting system).
   #### Ideas of enhancement
   Looking forward down the development pipeline, we envision to introduce other quality of life features such as:
Capability to identify products through screenshots (Optical Character Recognition), and instantly provide the user with the nutritional data
Function that allows users to take a picture of the nutritional label and convert it into tabulated data (Optical Character Recognition)
To launch mobile applications (IOS, Android) on top of web application
   #### Novelty
   We came across several websites and mobile applications that provide generic nutrition values without zooming in to specific off the shelf food and beverage products. There are also a couple of existing apps having similar ideas but they do not cater to the Singapore market. Hence, our solution would be novel to Singapore/South East Asia and specifically catering to the off the shelf food and beverage products in these markets. 

### 4. How will you prevent people from copying your solution? (which you patent it?)

   #### Information Security
   The main asset of the project which, is the database of digitized nutritional labels, will be kept private by authenticating API endpoints and rate limiting to prevent web-scrapers. 

   #### Technology Security
   The web application will make use of a private repository (Gitlab, Github, etc) to protect the source code.

   #### Innovation
   Constant improvement in technology with innovative ideas to stay ahead of the market. Providing better user experience will help retain users on the platform.

   #### Network Effect
   Invest in market share and build a user base through network effect, allowing us to have better product market fit. With no such product in Singapore, this also provides a first mover advantage

   #### Collaboration with other stakeholders
   Collaborate with merchants and Consumers Association of Singapore (CASE) to obtain other information that is relevant to consumers.
	
