# llSPS-INT-163-AI-Powered-News-Search-App-Level-1-
## AI Powered News Search App (Level-1)

#### OVERVIEW :

In this project we are going to build an AI Powered News Search application starting with the basics by creating an IBM account and Node-Red account and designing the UI through the nodes and using the IBM Watson discovery service for extracting the latest news articles. Enriched news data can help our application make dynamic connections across current events faster. The user interacts with the app UI to request the relevant news content. The app sends user requests to Watson Discovery News. The Watson Discovery Service is continually crawling the web to update its Discovery News collection.

The Watson Discovery Service responds to Slack search requests. And in our application users will be able to view the latest news according to the query he/she searched.

<br/>

#### PURPOSE :
The purpose of the report is to improve news fetching methodologies. In this guide to sentiment analysis, we learn how by using node-red application we can fetch news that has a sentimental score or value to it. This node red flow is made such that we get the input as the text of the news, url of main page, author of the website, the sentimental score by using gauge, and bar graphs which show us the sentimental analysis like if the searched news is positive, negative or normal.
<br/>
</br>
The project revolves around:

1. Building a Server Side Application using Node-RED

2. Using the pre-built Watson Discovery News collection

3. Accessing the Watson Discovery Service through the Discovery API

Additionally, we include:

1. Deploy the app on IBM Cloud.

2. Use a Slack interface to query the data

3. Push news alerts out to web notification

We propose the use of IBM Discovery, IBM Watson and IBM Node-RED.
<br/>

<br/>

#### FLOW :

1. The user interacts with the app UI(Built with Node-RED or Cloud or Local) to request relevant news content.

2. The app sends user requests to Watson Discovery News.

3. The Watson Discovery Service is continually crawling the web to update its Discovery News collection.

4. The Watson Discovery Service responds to Slack search requests.

• Code is written in Node.js, with the server-side using the Express framework and the client using ReactJS.

• The pre-built Watson Discovery News collection was used.

• Access the Watson Discovery Service through the Discovery API.

• Use a Slack interface to query the data.

<br/>
<br/>

#### CONCLUSION :

This application uses individual out-of-the-box UI components to extract and visualize the enriched data provided by the Discovery analytics engine. The code pattern includes Watson Discovery series. It gets the customer sentiment insights from product reviews. And this project gave us some basic working knowledge of the Watson Discovery Service and shows how to use Discovery along with JavaScript and Node Red to build your own news mining web application. This project also tells about the integration process of slack with the Watson services to access and create our own bot to query news from the channel.

