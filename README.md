# Researching External APIs Lab

## Getting Started

1. Fork and clone this repository.

1. Answer the questions below by editing this readme. Leave the questions and prompts, and answer in between them. Take the time to read back the work, and edit what you've written so that your answers are clear and anyone reading it can easily understand what you've written.

1. When it is applicable, please add screenshots, photos, and links.

## Instructions

You will be planning a new application to develop that uses a third-party API. The app should be a simple idea, as the goal is to research and determine if an API is appropriate for your API.

Choose one of the following categories and APIs:

- Music: [Spotify API](https://developer.spotify.com/documentation/web-api)
- Movies: [OMDB API](https://www.omdbapi.com)
- Text Translator: [Rapid Translate](https://rapidapi.com/auth/sign-up?referral=/sibaridev/api/rapid-translate-multi-traduction)
- Sports: [Sports Score](https://rapidapi.com/tipsters/api/sportscore1)
- City Info: [311 Call Aggregator](https://data.cityofnewyork.us/browse?Dataset-Information_Agency=311)
- Art : [Metropolitan Museum of Art ](https://metmuseum.github.io)

Next, describe your application idea. Your application idea should be simple and make use of the data received by the API. It can make use of other data if necessary.

> This application can help people search for art pieces sorted by year

Write 3 - 5 user stories for your application. Include each below.

> 1. As a user I am a tourist in NYC and I would like to know what art I can see from Egypt

> 1. As a user I would like to know which department this piece of art is in

> 1. As a user I would like to see art from a specific artist 

What data is needed to complete your application? Describe the data below and provide a link in the documentation showing where to get this data.

> The data I need for my app is the list of departments, a list of artists and list of art in Egypt, API endpoints referring to what the user is searching for  

Determine the number of free requests you can make to the API. Include a link in the documentation showing where you found this limit, if possible.

> The number of free requests I can make is 80 per second

Would the number of free requests you can make to the API be sufficient for you to develop a basic version of the application within a week? Why or why not?

> Yes it would because I am able to make multiple requests without the worry of a rate limit

Does working with the API require the use of a credit card? If possible, include a link in the documentation showing where you found this requirement.

> No

Write one GET request to your chosen API with Postman. This may involve requesting an API key or other steps. If you requested an API Key, **don't include it.** Instead, replace that part of the URL WITH `<MY API KEY>.`

> https://collectionapi.metmuseum.org/public/collection/v1/search?departmentId=6&q=cat

Include a snippet of the data you received from the above request.

```
{
    "total": 3189,
    "objectIDs": [
        49698,
        49470,
        53222,
        36221,
        60873,
        70541,
        752008,
        43402,
}
```

> **Note**: If you could not get an API key for any reason (like it required a credit card or took too long for an API key to be delivered), just leave a note here and do your best to answer the questions anyway.

What file do you need to store an API key safely?

> .env

Why do you want to place that file within the `.gitignore` file?

> You want it to ignore the files listed
