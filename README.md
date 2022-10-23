# UFO Sightings Analysis

## Background
Dana is a data journalist who has chosen to focus on UFO sightings, for which her hometown is famous. She has data but it had only been accessible in a JavaScript file. In this project, I put together a website with JavaScript that took the data and made it so that it could be shared publicly and so that the data could be filtered more easily by date, city, state, country, and shape of the UFO.

## Using the Website
The website should be fairly straight forward for folks who are familiar with using the internet. For those who arent't a quick guide is below.

Once a user has traveled to the website, they are greeted with a photo from NASA, the title of the page, and some opening remarks. Upon scrolling down the page, a user will see a table of sightings with columns denoting the date of the sighting, city, state, country, duration, shape of the UFO and some comments by the observer. 

This collection is vast, so it doesn't quite make sense to expect a user to pour through each entry to find what they are looking for. Instead, on the left hand side of the screen, users can filter, or select attributes of the sighting(s) they want to see. For example, there are numerous sightings on January 1, 2010. The user may type "1/1/2010" into the date box and press enter to only see sightings from that day. 

<img width="1153" alt="Screen Shot 2022-10-23 at 2 31 42 PM" src="https://user-images.githubusercontent.com/108236450/197409468-5c272136-c2e7-4677-ad1d-e99b96e732c1.png">


Looking through the list, there seem to have been sightings on that day in Arkansas, Kentucky, California, and Oregon. Many, however, in California. A user interested in the sightings from California can enter "ca" in the state box and click enter again.<img width="1150" alt="Screen Shot 2022-10-23 at 2 33 46 PM" src="https://user-images.githubusercontent.com/108236450/197409555-66429bc5-6c55-41f8-957c-a396c1b8fff3.png">

Now the user is only looking at sightings in California on January 1, 2010. The user might notice that there are different shaped UFOs that were seen but many are "light." Looking for any commonalities, to determine if perhaps the observers saw the same UFO, they could filter again by "light" in the shape box.

<img width="1143" alt="Screen Shot 2022-10-23 at 2 35 50 PM" src="https://user-images.githubusercontent.com/108236450/197409651-c0147fb3-9584-4628-b69b-5fcadb8cb9b0.png">

Now it is easy to see that of the 7 sightings in this filtered set, at least 5 observers saw three red lights. 

# Drawbacks and Suggestions

A future iteration of the site might look to plot sightings on a map. For instance, unfamiliar with California's geography, a user might not know how close Fresno, Bakersfield, or Lemon Grove are to eachother. This leads to the question of whether these sightings took place at the same exact time, or did the UFO travel. Additionally, the data lacks a specific time.

Additional suggestions for features might include, the ability to filter by a date range -- I'm not sure if UFOs care about our distinction between 11:59pm and 12:00am. There might be more similarities to be found. Another would be to allow for multiple states to be selected in the state filter.


