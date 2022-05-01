# Project | Web Scrapping

## Introduction:

The scope of this project is to scrap the web_page https://ecuestre.digital/shows/ and retrieve the info within.
There are several levels of scrapping in this page that are going to be explained up next.

## Workflow:

In the main page, are shown the upcoming and previous shows of horse jumping sport in different countries across LATAM and USA. The upcoming shows doesn´t have data in it so the scrapping is focused on the previous shows.
The code is structure by Object-oriented programming (OPP), having the main function of scrapping the main page, with the input as the url main page . The result is a data_table saved on the project folder containing [this](https://github.com/juanmanuelvillacis/Project_2_Data_Web/blob/main/Main_Page_Scrape.csv) information. 
Next is the second function, being an inheritance of the first one, the input are all the links retrieved from the main page and the result is a Dataframe containing [this](https://github.com/juanmanuelvillacis/Project_2_Data_Web/blob/main/Second_Page_Scrape.csv) information saved in the project folder. the rows contains info of each show like the classes practiced and links for the results page.

A [entity relationship diagram](https://github.com/juanmanuelvillacis/Project_2_Data_Web/blob/main/entity%20relationship%20diagram.png) was also ploted using SQL WorkBench. in the image we can find the columns types and keys. Tables in red show future improvements from a deeper scrapping of the web page and relations from the data that is explored ahead

## Future Improvements

Due to of the second_page_table with all the info of the shows, in it there are liks of the results page. A future improvement is continuing the scrape through the second_page links (1324 as total) to retrieve the podium info with the riders and horses profile as well as the puctuation. Whit it,  crossing tables info could bring great results and insights from data processing.

## Deliverables

`Project_2_Web_Scrapping.ipynb`, `README.txt`, 'Main_Page_Scrape.csv', `Second_Page_Scrape.csv`, 'Diagram_Equestre_Digital.mwb'
