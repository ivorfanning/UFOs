# UFOs

# Project Overviews

This projects is to build a UFO webpage and create a table to organize UFO data that is stored as a JavaScript array. The table could filter the UFO data by user's input. To deploy the functions, we use HTML, CSS, JavaScript and Bootstrap to build the web and table, that are easy to read and use.

# Results

To help Dana to build the webpage, we decide to make a storyboard first, which should include the following sections:

1. A navigation bar
2. An outstanding header / title
3. An article about UFO findings
4. A functional filter and UFO dataset

![storyboard](https://github.com/ivorfanning/UFOs/blob/main/pics/storyboard.png)

After building the HTML code, the webpage looks like the following: 

![web](https://github.com/ivorfanning/UFOs/blob/main/pics/webpage%20open.png)

we implemented all the sections we designed, and it looks cool. However the coolest function is the filter located on the left bottom corner, it could filter the data which is on its right side by input the texts in the filter sections.

If no search critiria were entered, the filter shows the default input reminder, and all of the data were displayed on the right.

![all data](https://github.com/ivorfanning/UFOs/blob/main/pics/webpage%20all%20data.png)

If the users input search critira, such as filter all the UFO events happened in "ca", and press enter, the data will automaticly shows all the data related to "ca".

![filter1](https://github.com/ivorfanning/UFOs/blob/main/pics/webpage%20fitler1.png)

The users could input combined search critira such as filter all the UFO events happened in 1/4/2010 and the shape is "light", the data will show all the results related to "1/4/2010" and "light".

![filter2](https://github.com/ivorfanning/UFOs/blob/main/pics/webpage%20fitler2.png)

# Summary

In spite of the mystery looking of the webpage and fancy filter table we build, it still have a lot rooms to improve its functionality.

There is some drawbacks we can easily see:

1. The search textbox is case sensitive, for example if the user inputs "CA", the filter will not work.
2. The UFO data is limited.
3. The article is simple and unique.

In order to improve our webpage, I have some recommendations against the above drawbacks:

1. we could add dropdown manu on the search textbox for users to easily filter what they want to see, and the dropdown manu will also reduce the case sensitive problems input by the users.
2. we could use API and scraping data technique to connect our data table to a live data update site, so the user could filter the lastest UFO findings.
3. we could add more articles and let the article section roll, it could help users to obtain more information about the UFO findings.

