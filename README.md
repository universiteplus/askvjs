# askvjs

askvjs is a videojs plugin that enables asking pop questions in a specific time of a video.


## Features

* *You can create a pop question.* You can create a question by giving a question text, a set of answers, correct answer, and time that the question will be popped. Time can be total seconds or in "mm:ss" format. Questions could be given as an array of json objects to the creator function, and creator function should successfuly initiate the whole process.
* *Questions are asked at the right time.* While playing audio or video on videojs, anytime, if time of a question is come, then video will be paused and a section containing question and possible answers will be shown to the user awaiting her response. Any correct or wrong answer will trigger a specific event, and any function could be delegated to it. A "continue to the video" option should be given to the user at any time.


## Skillsets

Frontend development.


## Tools and Technologies

Javascript, html, and css should be used. Videojs library, which is cross platform and extensible html5 video player, should be the choice of player, and a videojs plugin should be developed.  


## Resources and Links

* [videojs](http://www.videojs.com/), *cross platform, well developed, extendable videoplayer plugin.*
* [Blubbr](https://www.blubbr.tv/), *a trivia that asks users quizzes about movies.* 


## How to Do It

1. Fork this repo.
2. Use git, and commit/push your work in smaller chunks.
3. Make sure that you are not complicating things! Whole challenge should not take more than a man's day. (max 8 hours)
3. When your work is done, fill in the _*Usage*_ section with how to use your plugin/start your application and test it live. If it is needed, provide a test application in the same repo.


## Usage

_Fill this section with the steps to test it live._
