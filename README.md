# Capstone_Project
## INTRODUCTION
People across the globe , are unaware of the fact that it is possible to know the best location where they can reside if they wish to shift their home to a particular location. In my Project I have taken an example of a person shifting to Toronto, Canada . Around 187,950 people migrated from across the world to toronto , Canada between the year 2011 to 2016, which makes it 6.1 % of the total population. Different people of varied culture and background have different needs. Some move in with a family, some are students, some of them want to just start a business and are looking for a better place to start their small businesses but are unaware are less educated as to where should they start their base. Right Place to start a family or a business matters. Having a proper and a perfect location will decide whether a family will have all the things they need is present , and whether a businessman will have a successful business or not.

## TARGET AUDIENCE
The target audience are:

1.The family (having a kid) who needs to migrate to Toronto Borough and are in search of a good place having basic amenities and requirements like a school or a university,malls,restaurants,hopitals,gym and a few more.

2.Small businessman who wants to grow or build their business and wants to know which place has less density or restaurants or gym or malls and also their ratings , likes , etc.

OBJECTIVE
The objective of my project is to make people aware of the places that are suitable to them by providing them details about the places that they wish they had near them. This project also provides the ratings , number of likes and tips of that particular place of the neighborhood of a particular Borough.

In my project I have considered three Borough of Toronto - North York, East Toronto and Central Toronto.

## DATA
To solve this problem I needed some data:

Of all the Borough of Toronto so as to take out the considered Borough for the project.
Latitudes and longitude needed of the respective Borough of Toronto (so as to pass the location to the foursquare API).
Venue details of the places nearby the Borough of toronto.
Ratings , Likes and Tips of the place nearby the Borough of toronto.
Source for the Data:

To get the neighborhoods of toronto, I took help of "https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M" . I wep scrapped this webpage using beautifulSoup .
I got the Latitude and the Longitude of the respective Borough of Toronto through "https://cocl.us/Geospatial_data".
To get the venue details such as name and category of that place and their ratings I took help of Foursquare API via the request library of Python which sent me a json data. Fourquare API has a database of 100+ million places .
