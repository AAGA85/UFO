# UFO

# OVERVIEW

Dana is a data journalist who is at a point in her career where she has the freedom to choose the topics she wants to write about. Then she decided to choose a passionate topic for her…. UFOs. For this assignment she must go on so far is a JavaScript file filled to the brim with sighting information. There are a lot of data to share but she has decided to take advantage of the JavaScript’s visual functionality that allows manipulate the data by adding filters. 

For this challenge we have help Dana to post her article online and put everything together in a tidy HTML page. This page includes:

1.	Her article

2.	The table of data that support her findings

3.	An easy way to use multiple filters to fine tune the results (by city, by state, by country and shape)

# RESULTS

# UFO's site

With the usage of JavaScript ES6+, we were able to deploy the website that Dana was looking for. Let's take a look at every area of the website and highlight the expected deliverables:

## FIRST: Her Article

![the article](https://user-images.githubusercontent.com/106939511/186296049-30cb8bbc-a8b6-43e3-b06d-6b222245cc0a.png)


## SECOND: The table

![the table](https://user-images.githubusercontent.com/106939511/186296076-c712cbe4-ed21-41e7-ba8b-21c280f0d96a.png)


## THIRD: The filters

![the filters](https://user-images.githubusercontent.com/106939511/186296112-57e32fe9-13d0-4aab-842d-0f89c71aa40f.png)


Then let's review the way that the filters work 

By adding just city and state:

![first research](https://user-images.githubusercontent.com/106939511/186297183-802878e2-048d-4746-95c3-f559b518882f.png)


By adding just city and shape: 

![second search](https://user-images.githubusercontent.com/106939511/186297246-13e25594-0330-40b6-877e-9f343089b562.png)


## SUMMARY

Drawback: By typing in the suggested placeholder elements as the filters, the user have to type everything in lower case letters and do not have spaces at the end of the text. Those kind of details are not listed anywhere so the user could fail easily and not find the data.

Recommendations:

1. Fix the disadvantages described before. The easy way could be add a kind of instructions for the user but the professional way could be to add the trim() Function to remove the whitespace characters from the start and the end. Besides that we can include an additonal funtion to convert to lower case or to uppercase.

2. The research data on some filters are not intuitive like Date. For example the data showed in the table is only about the 2010 that kind of limitation is not shared with the user anywhere. So it could be helpful to highlight that in the article and set up a date range instead of a specific date. 
