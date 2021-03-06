# Rossmann Store Salles Prediction
![img_sales](https://user-images.githubusercontent.com/97919969/166930775-427d80e9-5dab-4ce6-9db1-60f30bfa117d.jpeg)
# 1.0.CONTEXT
Rossmann is a company witch operates over three thousand drugs stores, in seven European countries. 
# 2.0. BUSINESS PROBLEM
Buget definition for the refurbishment of stores.

Cause:

The current Sales Prediction displays many divergence;

The Sales Prediction process is based on pass experiences;

All of Sales Prediction has been done manually by 1.115 Rossmann Stores;

The visualisation of Sales is limited by computer;


Solution:

Use Machine Learning to perform the Sales Prediction for all Stores;

The visualization of Salles Prediction can be seen by a Smartphone;

# 3. Solution Development 
# Data Description
<img width="810" alt="Screen Shot 2022-05-05 at 6 28 20 AM" src="https://user-images.githubusercontent.com/97919969/166934049-8d2696e8-2d0e-4d58-975d-887d850e56fb.png">

As we can see bellow, we have 2 data types: int64 and float64. It's important to explain that machine learning algorithms usually build a better learning with numerical data, this is one of the premises that we will assume.

# Descriptive Startistical 

<img width="1163" alt="Screen Shot 2022-05-05 at 6 33 26 AM" src="https://user-images.githubusercontent.com/97919969/166934613-210e6512-5f60-4d12-9869-b5755179ea43.png">

# Mind Map

![mindmap](https://user-images.githubusercontent.com/97919969/166935606-b2b1f351-f1a1-4ab8-9875-6db250e04732.png)

# Hipothesys List 

 1. - Stores with biggest assortment should sell over/more.
 2. - Stores with competitors around should sell less.
 3. - Stores with longer competitors should sell over/more.
 4. - Stores with activate promotion for more time should sell over/more.
 5. - Stores with more promotion days should sell over/more.
 6. - Stores with consecultive promotion should sell over/more.
 7. - Opened stores on Christimas holliday should sall over/more.
 8. - Stores should sell more throughout the year.
 9. - Stores should sell more on the second semestre of the year.
 10. - Stores  should sell more after 10th day of eatch month.
 11. - Stores should sell less on wekeends.
 12. - Stores should sell less on hollidays school.

# Exploratory Data Analisys
# Response variable

<img width="1233" alt="Screen Shot 2022-05-05 at 6 43 57 AM" src="https://user-images.githubusercontent.com/97919969/166936765-82c4188d-66d7-437f-843c-17312381f2f1.png">

# Numerical Variable

<img width="1140" alt="Screen Shot 2022-05-05 at 6 46 38 AM" src="https://user-images.githubusercontent.com/97919969/166937348-0d575df7-4592-416d-9cc0-76a40e0bcc70.png">

# Categorical Variable

<img width="1161" alt="Screen Shot 2022-05-05 at 6 50 03 AM" src="https://user-images.githubusercontent.com/97919969/166937978-a9c6feda-93d5-4000-8ce5-682a72797c9f.png">

# Hypothesys validation

 # H1. - Stores with biggest assortment should sell more.
 FALSE
<img width="1269" alt="Screen Shot 2022-05-05 at 6 53 12 AM" src="https://user-images.githubusercontent.com/97919969/166938645-1ac64f4b-4ba5-4d39-944a-5db9cc4b545b.png">

# H2. - Stores with competitors around should sell less.
FALSE 
<img width="1220" alt="Screen Shot 2022-05-05 at 6 56 32 AM" src="https://user-images.githubusercontent.com/97919969/166939302-ac95033c-561f-496f-bca1-5a5efd915d94.png">

# H3 - Opened stores on Christimas holliday should sall over/more.
FALSE 

<img width="1188" alt="Screen Shot 2022-05-05 at 6 58 49 AM" src="https://user-images.githubusercontent.com/97919969/166939768-1c4f034e-34b5-4a6b-995b-2e5dc6b81048.png">

# H4. - Stores should sell more after 10th day of eatch month.
TRUE
<img width="1145" alt="Screen Shot 2022-05-05 at 7 01 11 AM" src="https://user-images.githubusercontent.com/97919969/166940329-f068d51a-af28-497c-a34a-0b8db799d0ca.png">

# Hipothesys Resume

<img width="432" alt="Screen Shot 2022-05-05 at 7 04 01 AM" src="https://user-images.githubusercontent.com/97919969/166940810-1c6838ae-8656-487d-8259-d761e857b966.png">

# Multivariable Analisys

<img width="1161" alt="Screen Shot 2022-05-05 at 7 07 02 AM" src="https://user-images.githubusercontent.com/97919969/166941493-c453411c-15c8-4216-8165-4ea621cc2990.png">

# Machine Learning Modelling
Compare Model's Performance
<img width="688" alt="Screen Shot 2022-05-05 at 7 09 26 AM" src="https://user-images.githubusercontent.com/97919969/166942120-c740476b-4f28-4540-9bd3-998225d8f30d.png">

# 4. Conclusion and Demostration 
# Error Translater and interpretation

<img width="688" alt="Screen Shot 2022-05-05 at 7 09 26 AM" src="https://user-images.githubusercontent.com/97919969/166942120-c740476b-4f28-4540-9bd3-998225d8f30d.png">

# Business Performance

<img width="1255" alt="Screen Shot 2022-05-05 at 7 15 37 AM" src="https://user-images.githubusercontent.com/97919969/166943359-7207c6a6-d644-4f8c-a3f5-5ba65707085c.png">

# Total Performace

<img width="484" alt="Screen Shot 2022-05-05 at 7 18 04 AM" src="https://user-images.githubusercontent.com/97919969/166943862-99c938c3-3582-4606-a347-98469c8ca966.png">

# Machine Learning Performace

<img width="1154" alt="Screen Shot 2022-05-05 at 7 21 12 AM" src="https://user-images.githubusercontent.com/97919969/166945747-b3998bef-457b-4f43-8da5-9a4eb1182bbe.png">


# Result View

![DCF0651D-09EA-4F90-82C0-A69F479F9CA8](https://user-images.githubusercontent.com/97919969/166949002-f09e86e3-52b4-4878-aba0-5500894bad0f.png)




