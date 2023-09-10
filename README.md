# Potential_Customers_Prediction
Analyze and build an ML model to help identify which leads are more likely to convert to paid customers.

Project Problem Statement - Potential Customers Prediction
Context
The EdTech industry has been surging in the past decade immensely, and according to a forecast, the Online Education market would be worth $286.62bn by 2023, with a compound annual growth rate (CAGR) of 10.26% from 2018 to 2023. The modern era of online education has enforced a lot in its growth and expansion beyond any limit. Due to having many dominant features like ease of information sharing, personalized learning experience, transparency of assessment, etc., it is now preferable to traditional education.

The online education sector has witnessed rapid growth and is attracting a lot of new customers. Due to this rapid growth, many new companies have emerged in this industry. With the availability and ease of use of digital marketing resources, companies can reach out to a wider audience with their offerings. The customers who show interest in these offerings are termed as leads. There are various sources of obtaining leads for Edtech companies, like:

 The customer interacts with the marketing front on social media or other online platforms.
 The customer browses the website/app and downloads the brochure.
 The customer connects through emails for more information.
The company then nurtures these leads and tries to convert them to paid customers. For this, the representative from the organization connects with the lead on call or through email to share further details.

Objective
ExtraaLearn is an initial stage startup that offers programs on cutting-edge technologies to students and professionals to help them upskill/reskill. With a large number of leads being generated on a regular basis, one of the issues faced by ExtraaLearn is to identify which of the leads are more likely to convert so that they can allocate the resources accordingly. You, as a data scientist at ExtraaLearn, have been provided the leads data to:

Analyze and build an ML model to help identify which leads are more likely to convert to paid customers.
Find the factors driving the lead conversion process.
Create a profile of the leads who are likely to convert.
Data Dictionary
The data contains the different attributes of leads and their interaction details with ExtraaLearn. The detailed data dictionary is given below.

 ID: ID of the lead
 age: Age of the lead
 current_occupation: Current occupation of the lead. Values include 'Professional', 'Unemployed', and 'Student'
 first_interaction: How did the lead first interact with ExtraaLearn? Values include 'Website' and 'Mobile App'
 profile_completed: What percentage of the profile has been filled by the lead on the website/mobile app? Values include Low - (0-50%), Medium - (50-75%), High (75-100%)
 website_visits: The number of times a lead has visited the website
 time_spent_on_website: Total time spent on the website
 page_views_per_visit: Average number of pages on the website viewed during the visits
 last_activity: Last interaction between the lead and ExtraaLearn
 Email Activity: Seeking details about the program through email, Representative shared information with a lead like a brochure of the program, etc.
 Phone Activity: Had a phone conversation with a representative, had a conversation over SMS with a representative, etc.
 Website Activity: Interacted on live chat with a representative, updated profile on the website, etc.
print_media_type1: Flag indicating whether the lead had seen the ad of ExtraaLearn in the Newspaper
print_media_type2: Flag indicating whether the lead had seen the ad of ExtraaLearn in the Magazine
digital_media: Flag indicating whether the lead had seen the ad of ExtraaLearn on the digital platforms
educational_channels: Flag indicating whether the lead had heard about ExtraaLearn in the education channels like online forums, discussion threads, educational websites, etc.
referral: Flag indicating whether the lead had heard about ExtraaLearn through reference.
status: Flag indicating whether the lead was converted to a paid customer or not.
