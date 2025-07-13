# My First OSINT Challenge

## July 11, 2025

I decided to challenge myself with Sophia Santos' OSINT Exercise #002 which can be found here ``https://gralhix.com/list-of-osint-exercises/osint-exercise-002/``

This marks my very first OSINT challenge, and it made for a perfect start.

### Task Briefing

The photo below was shared on social media. It clearly depicts a train station.  
Please answer the following questions:  
  
a) What is the name of the train station seen in the photo?  
b) What is the name and height of the tallest structure seen in the photo?  
  
Click [here](https://gralhix.com/wp-content/uploads/2024/09/osint-exercise-002-big-picture.png) to open the photo on a new page.
<img width="986" height="754" alt="osint-exercise-002-big-picture" src="https://github.com/user-attachments/assets/8b03ba81-7ce8-447c-9782-c9a7de312ddd" />


**Exercise level:**  
For beginners: a) Easy, b) Hard  
For experts: a) Easy, b) Medium

### PART A - Finding the name of the train station seen in the photo
This challenge was a great starting point. I honestly had a bit of an advantage with this one because
as soon as I saw the image, I knew exactly where it was taken because this place took me right back to my days in high school and uni. 
I spent a good part of my teenage years living in this city, and Flinders Street station was part of my daily routine, commuting to and from school and later on, uni.
So this location felt instantly familiar.

The photo shows a train station right in the heart of Melbourne's CBD, Victoria, Australia. So, for the first question, I had the 
answer right off the bat.

That said, OSINT is all about verification, so I still went ahead and broke the image down:
* **Foreground**: A railway platform with a few people waiting
* **Trains**: Blue, silver, and white accents
* **Background**: Some high-rise buildings. I spotted a building with a tall spire (the National Arts Centre) HWT building (third one from the left), an IBM building (fourth on from the left), another blue building with some red text at the top
* **Signage**: You can clearly see multiple signs on the platforms reading "Flinders Street"

We're definitely looking at Flinders Street Station

I still ran a reverse image search via Google Images, which confirmed the location. And just to tie it all together, I dropped Pegman into Google Maps, right at the station.
I ended up in the underpass, walked a little bit through Flinders Walk using the Virtual Tour feature on Google Maps, and ended up with a view almost identical to the image provided in the task. 
You can even spot the same spire peeking through the building to the very left.

<img width="2559" height="1246" alt="Screenshot 2025-07-11 141000" src="https://github.com/user-attachments/assets/a5977b8d-5b78-4c6d-91ed-a23756e76894" />

We can therefore confirm that the name of the train station seen in the photo is Flinders Street Station, Melbourne, VIC, Australia.

### Part B - Identifying the tallest structure

This part took a bit more digging.
There were a few tall buildings visible in the shot, so I opened up Google Earth to get a bird's-eye view and try to match the perspective from the original picture in the task. 

<img width="1279" height="605" alt="google-earth-view-flinders" src="https://github.com/user-attachments/assets/0e6974ee-e8c5-410a-81f2-03b63acd6efe" />

I decided to start from the left and decided to find out the height of the building with the spire, Arts Centre Melbourne.

A quick Google search showeed its spire stands at **162m** tall.

<img width="718" height="461" alt="image" src="https://github.com/user-attachments/assets/422d39cd-6846-4b25-b853-21ed1ecf2a6f" />

Then I looked into the IBM building seen in the image. According to ``SkyscraperCenter``, the IBM Australia building, stands at ``131m`` tall, so not taller than the Arts Centre.
<img width="1948" height="1211" alt="image" src="https://github.com/user-attachments/assets/45ba2750-9d45-4b01-bf4c-3ee3bf77d353" />

At this point, I was fairly convinced that the Arts Centre was the tallest structure.
But something about the tall blue building in the image felt off. I noticed that the blue building when viewed through Google Earth in 3D view looked a lot taller than it did in the photo. 

So I returned to Google Street View, dropped the Pegman on Google Maps again and found a view from September 2022, where that building was still under construction.

<img width="2559" height="1218" alt="image" src="https://github.com/user-attachments/assets/cdb56a2a-1107-48ae-a6fa-900561112c0a" />

Looking closely, I noticed a "Central Equity" sign on the building under construction. A quick Google search confirmed that Central Equity is an Australian apartment developer. 
So, I jumped onto their website to see if I could find a match.

<img width="1182" height="910" alt="image" src="https://github.com/user-attachments/assets/bf023ba5-b6ff-4603-b62b-f2ce5f8d55d4" />

They had 2 fairly recent developments listed on their website. One was Parkhill on Spencer Street completed in July 2023, and the other was Focus Melbourne on City Rd, which was completed in 2022,
matching the timeline of the construction shown in the Google Street View from September 2022.

<img width="1804" height="1121" alt="image" src="https://github.com/user-attachments/assets/00360684-fa74-4629-98c3-bc0ee22d795a" />

Their website for the project ``https://focusmelb.com.au/?utm_source=CE&utm_medium=website&utm_content=homepage``showed an image of the completed building, and it definitely matched the one in the photo.
<img width="2035" height="1230" alt="image" src="https://github.com/user-attachments/assets/4a9578c8-e0a1-43ae-965a-49262749d638" />

A search of the address (81 City Rd, Southbank VIC) confirmed its location.
<img width="667" height="608" alt="image" src="https://github.com/user-attachments/assets/2d0c0279-ef94-4a55-8fca-4e2b9780edbe" />

When I Googled "Focus Apartments Melbourne height", one source showed 166m, but digging deeper led me to "Multiplex Global's official page", which confirmed the final height as **167m**.

<img width="375" height="471" alt="image" src="https://github.com/user-attachments/assets/0ded7a51-ef33-495f-add9-f4e82ea42ac7" />

<img width="2298" height="1152" alt="image" src="https://github.com/user-attachments/assets/901b8526-dd2c-4450-93a9-3850fd4a4eaa" />

So, to answer Part B of the challenge, the tallest structure seen in the image is Focus Apartments Melbourne, standing at 167m tall.


### Tools Used
* Google Maps (Pegman / Street View / Flinders Walk / Virtual Tour feature)
* Google Earth (3D view / Orientation)
* Google Images (Reverse image search)
* Google Search (to find building names and details
  * Developer and construction websites (Central Equity, Multiplex Global)
  * SkyscraperCenter.com (building heights)
    

