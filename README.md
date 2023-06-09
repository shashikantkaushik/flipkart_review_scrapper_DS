# Flipkart-Review-Scrapper
A Python based Web Crawler for extracting Product Review and its image, to use it for Sentiment Analysis.

I have used Flask as a micro framework and BeautifulSoup as a parser for HTML. For Running it on local Server, I have used MongoDB dataBase.
With index.html file you will be able to search the item, whereas results.html file will fetch you the records of Data Scrapped from Flipkart.com 


To use this app, simply clone the repository, download MongoDb and Flask if already not Installed.
FlaskApp.py is used for running it on local server and having MongoDB as a database to remove the overhead of scrapping same Product multiple times.

Requirement.txt will help you to import the correct version of libraries used in this project.
howtorun file is added for running it on Heroku Platform. Feel Free to Contribute. For any queries contact me through shashikantkaushik4@gmail.com


<br>

## 🚀 Preview

### Search Page
![alt text](https://github.com/lksh97/Flipkart-Review-Scrapper/blob/main/Flipkart/Screenshot%202021-02-15%20at%206.03.19%20PM.png)

<br>

### Fetched Result
![alt text](https://github.com/lksh97/Flipkart-Review-Scrapper/blob/main/Flipkart/imgonline-com-ua-twotoone-OtX2x8pOdcw.jpg)

<br>

The search page allows you to search for a specific item. The fetched result shows the extracted reviews and their corresponding images.






<br>

## :construction_worker: Installation


***In order to clone the project via HTTPS, run this command:***

```
$>gh repo clone shashikantkaushik/flipkart_review_scrapper_DS
```

SSH URLs provide access to a Git repository via SSH, a secure protocol. If you have a SSH key registered in your Github account, clone the project using this command:

```
$> git@github.com:shashikantkaushik/flipkart_review_scrapper_DS.git
```

## To clone and run this app follow the following step-

```
$ git clone https://github.com/shashikantkaushik/flipkart_review_scrapper_DS.git
```
Install the required libraries by running the following command:

```
$ pip install -r requirements.txt
```
Start the Flask server

```
$ python FlaskApp.py
```

Note: You will also need to have MongoDB installed on your machine in order to clone.

<br>


**Install dependencies**

```
$> flutter install
```

**Start development server**

```
$> flutter run
```

<br>

## How To Use 

Once the server is up and running, you can access the app by visiting http://localhost:5000 in your web browser.

To search for a specific item, simply enter the item name in the search bar and click the "Search" button. The app will then scrape the reviews and images for that item from Flipkart.com and display them on the results page.

<br>

## Why Use Flipkart-Review-Scrapper
Flipkart-Review-Scrapper is a useful tool for anyone who wants to perform sentiment analysis on product reviews from Flipkart.com. By extracting the reviews and their corresponding images, you can gain insights into what customers are saying about a particular product and how they feel about it.

<br>

## :bug: Issues

Feel free to **file a new issue** with a respective title and description on the [Flipkart Review Scrapper](https://github.com/shashikantkaushik/flipkart_review_scrapper_DS/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**! Have a look at our [contribution guidelines](https://github.com/shashikantkaushik/shashikantkaushik/blob/main/CONTRIBUTING.md) to find out about the coding standards.

<br>

## :tada: Contributing

Check out the [contributing](https://github.com/shashikantkaushik/shashikantkaushik/blob/main/CONTRIBUTING.md) page to see the best places to file issues, start discussions and begin contributing.

<br>

## :closed_book: License
This project is open source and available under the MIT License.


<br>

##### Made with love by [Shashi Kant](https://github.com/shashikantkaushik) 💜🚀
