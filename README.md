# UFOs

## Project Overview
The purpose of this project was to web scrape data from several websites to gather the Mars information and display the results on a customized webpage using Bootstrap, Flask, and MongoDB.<br/>

## Results
<p align="center">
  <img src="https://github.com/stephen-tan/ufos/blob/main/markdown/webpage.png" alt="Webpage"/>
</p>

The webpage has five filter text boxes on the lefthand side, each with placeholders for examples on how to input a search criteria. One thing to note is that not all filters have to be used. Once a filter is input in the text box, the user needs to hit the 'Enter' key on the keyboard to initiate the filter. More than one filter is also able to be entered. </br></br>

In order to reset the filters, the webpage can be refreshed or the filters can be deleted and then the 'Enter' key should be pressed again. </br></br>

In the webpage screenshot above, a filter search was performed for UFO sightings for the criteria below:
- State = "ca"
- Country = "us"
- Shape = "triangle"

## Summary
One drawback of the webpage is that there is no filtering of searches. For example, if a user enters any inputs that are not in the dataset, then the webpage shows a blank table instead of saying that there are no searches found.</br>

For further development of the webpage, it would be great if the dataset was even more comprehensive since it only includes data from the first two weeks of January 2010. I would also update the information formatting to have the cities, states, countries with proper capitalization. Another recommendation would be to show a dropdown of all values present in each column to enhance the user experience.
