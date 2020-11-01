# Applied Data Science Capstone
For Coursera Capstone Project: Applied Data Science Capstone

## Peer-graded Assignment: Capstone Project - The Battle of Neighborhoods (Week 1)

## Introduction/Business Problem
*Clearly define a problem or an idea of your choice, where you would need to leverage the Foursquare location data to solve or execute. Remember that data science problems always target an audience and are meant to help a group of stakeholders solve a problem, so make sure that you explicitly describe your audience and why they would care about your problem.* 
 
  Lehi in Utah is the one of the fastest growing cities in the United State of America. Lehi's nickname, Sillicon Slope, is an attractive place for companies such as Adobe, Microsoft, and Oracle, which have built campuses. Additionally, new startups are growing rapidly in this area. Lehi is close to Salt Lake City International airport and Sundance - where the Sundance film festival is held every winter. Lehi is also famous for it’s beautiful mountains and forest which attracts hikers and outdoor enthusiasts.

  However, these various advantages and the increasing number of business travelers and tourists in Lehi face one challenge. One of the problems in this area is public transportation. Lehi’s rapid growth has highlighted an extreme need for improved public transportation - that is not as readily available as places like New York or San Francisco. A tourist wanting to visit the various sites around Lehi would find it difficult to hail a taxi or find a bus to reach their destination. Luckily, we have car sharing systems like Uber and Lyft, and we can also explore the area by utilizing the information from Google map or FourSquare before traveling. 

  As a travel agency manager, I am going to present this report to one of my clients who is going to visit Lehi for a tech conference in October. This client has never visited Lehi before and plans to stay 3 days. She is participating in the conference on the first day of the trip, and has already booked the hotel - Hyatt Place in Lehi. During her business trip, she wants to go hiking in the mountains or trails to experience the natural fall landscape. She is also planning to go shopping to get souvenirs for her friends and family. I was given the draft planner and charging on completing the planner. In order for her to have a successful business trip, I need to make a plan for the second and third day. 
  

## Data
*Describe the data that you will be using to solve the problem or execute your idea. Remember that you will need to use the Foursquare location data to solve the problem or execute your idea. You can absolutely use other datasets in combination with the Foursquare location data. So make sure that you provide adequate explanation and discussion, with examples, of the data that you will be using, even if it is only Foursquare location data.*

1. I have researched Google to outline my plan, and was able to reach this website: 
https://www.tripadvisor.com/Attractions-g57044-Activities-Lehi_Utah.html
This website provides general information specially top attractions that visitors can do in Lehi. 
 
2.  I am going to add climate data in Lehi which can help her pack her luggage:
https://en.wikipedia.org/wiki/Lehi,_Utah

As per Wikipedia data, I am going to create a climate data in October. This data will provide some tips like what clothes she needs to prepare. 


3. Using FourSquare’s API, I am going to make a map for recommendation restaurant, shopping areas near the Hotels and hiking places: 
https://foursquare.com/explore?mode=url&ne=40.823163%2C-111.197433&q=%EC%9D%8C%EC%8B%9D%EC%A0%90&sw=39.950806%2C-112.569351
https://foursquare.com/explore?mode=url&near=Lehi%2C%20UT%2C%20United%20States&nearGeoId=72057594043705160&q=hiking
https://foursquare.com/explore?mode=url&near=Lehi%2C%20UT%2C%20United%20States&nearGeoId=72057594043705160&q=shopping


4. I am also going to include other placese where the client may consider to go like museums or exhibition:
https://foursquare.com/explore?mode=url&ne=40.436169%2C-111.817088&q=museum&sw=40.381663%2C-111.902833
