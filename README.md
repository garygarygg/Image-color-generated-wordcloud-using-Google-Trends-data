# Image-color-generated-wordcloud-using-Google-Trends-data
Two generated wordclouds in Python based on a color image of the US &amp; UK national flags. The words used were sourced from Google's own data using pytrends - a pseudo API that provides a simple interface for automating downloading of reports from Google Trends - in Python.

When using pytrends to generate real time search trends, roughly 90 results are returned; whereas directly visiting Google Trends' website can potentially return a limitless amount of results. However, this would be a manual process and in addition, one would need to click on "LOAD MORE" past result number 10 to keep on loading further information for every 7-8 results generated.
I also explored Google Trends' daily search trends and for most countries, there is a maximum output of roughly 20 results per one day.

Using the above method, we are able to get a rudimentary viewing of trending real time information from a specific country, in the form of key words mapped out in a customizable wordcloud (in this case, a national flag).
