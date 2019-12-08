![ga_logo](https://user-images.githubusercontent.com/38439393/70393846-99b26800-19e6-11ea-82a0-35c1b5738321.png)
# Project 2: News On The Mews

## Overview 

News On The Mews is an online web application that displays news headlines on different topics and in different languages from all over the world.
It was built together with [mElbo-dk](https://github.com/mElbo-dk) over a 2 day period pair-programming hackathon and was the second project during my course at General Assembly.

![page_screenshot](src/assets/readme_screenshots/scr_0.png)

---
## Technologies Used

* HTML5
* CSS3 and Bulma CSS framework
* JavaScript
* React
* Axios
* Public [NewsAPI](https://newsapi.org/)
* Git/GitHub

---
## Deployment

Web version can be found on [Heroku](https://newsonthemews.herokuapp.com/)

---
## Getting Started

Clone the repository and run on your machine. 

Install the packages listed in the package.json file by running the following terminal command:
$ npm i

Run the app on your localhost 8000 with the following command:
$ npm run serve

In order tpo get the content you will need to obtain the API key from [NewsAPI](https://newsapi.org/). Once obtained, create .env file in the project level and paste in your key in the following text 
```
WEBAPI_ACCESS_TOKEN = 'your_API_key_here'

```
---
## Usage

Page loads with general UK News. From there user has below choices:
* Pick news from the different category by clicking on the dedicated category button.
* Search for any keyword-related news in the search-bar.
* Search for news by country and in language selected from the "Country" selector.
* Filter any of the above news content by the news sources from the "Sources" selector.
* Once clicked on one of the generated contents card, user gets navigated to the original source page to read the full article.

---
## Future Improvements

* Make the page more-mobile responsive.
* Store users last country and news type selection in localStorage so that more user-relevant content could be generated on the page load.
* Translate page navigational content to relevant language after user changes to sources from different country in the Coutry selector.






