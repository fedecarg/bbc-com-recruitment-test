# Web Developer Test - BBC.com
Web Developer recruitment test for roles at BBC.com http://www.bbc.com

Thank you for taking the time to do our technical test. It consists of two parts:

- Create a GitHub repository ([help](https://guides.github.com/activities/hello-world/))
- Develop a web application

Once you're done commit your changes, create a Pull Request and send us link to your repo.

## Task requirements

The task is designed to assess your interest and experience in web development. We want to see your code, your approach and your talent.

Test data is available at [https://gist.githubusercontent.com...](https://gist.githubusercontent.com/fedecarg/5772727ae899890d5bcf758a437e7fe5/raw/d030cd98ad5015707be919523b5f8710cbc6c623/bbc_news_test_data.json), use it to get video information, including image, caption, section and duration.

The task is to create a responsive web application that you can use to see the list of videos and filter by section. The application should display the following information about each video:

* Image: `media.image.href`
* Headline: `advert.shortHeadline`
* Duration: `media.duration`
* Section: `media.section`
* Link: `advert.uri`

Note:

Scale the image appropriately by replacing the `$recipe` placeholder in the `media.image.href` url with your desired size. The available image resolutions are shown here:

https://developer.bbc.co.uk/content/image-recipes

## User Stories

Display a list of videos:
```
  As a user
  When I visit the page
  I want to see a list of videos
  So that I know which videos are available
```

Filter list of videos by section:
```
  As a user
  When I visit the page
  I want to filter videos by section name
  So that I can find videos related to a topic
```

## What you need to build

Feel free to spend as much or as little time on the exercise as you like as long as the following requirements have been met:

* Please complete the user stories
* Your code should compile and run in one step

While solving the problem correctly is important this is an opportunity to show how you would go about structuring a solution to the problem.

You can create the application in any of the following languages: PHP, JavaScript, Java, Ruby or Python. Feel free to use whatever frameworks, libraries and packages you like. 

That's it. We leave the design and user-experience to you.

## What we're looking for

* Completeness of solution - does the app work as per the requirements?
* Quality of code - is your code clean?
* User interface - does the page look ok? is it easy to use?

## Final words

We hope you enjoy building a BBC video application. We're interested in your feedback, so do let us know what you thought of the task.
And most finally, good luck!
