# Online-Shopping-Prediction
## Introduction
It is happening now: when you open a new web page through your phone or laptop, your information is recorded in cookies. It does help when the website remembers what your preferences are so that you don’t need to input next time. But the main purpose of getting your cookies is to know who you are for commercial use. Information such as what your browsers are, what your regions are, or how much time you spend on a page, etc will be revealed when you agreed with the cookie policy (the annoying window asking for your agreement to collect your information each time when you enter a new website that never been before). So, this project is to really dig into possibility of translating your online traits into some practical use, that is whether you will end up buy something from an online website. Ideally, if this system can be dynamic in real time, it will be perfect. But I am interested to test this concept through my own justification.
## Dataset
[Dataset Link](https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset)

•	Target Features: to predict whether a client will buy in the shopping website, True/False

•	"Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" represent the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories. The values of these features are derived from the URL information of the pages visited by the user and updated in real time when a user takes an action, e.g. moving from one page to another.

•	The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site. The value of "Bounce Rate" feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session. The value of "Exit Rate" feature for a specific web page is calculated as for all pageviews to the page, the percentage that were the last in the session.

•	The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with transaction. The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8. 

•	The dataset also includes operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year.

