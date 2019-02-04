# CALEO

<p align="center">
  <img src="preview/demo.gif" alt="demo" width="400"/>
</p>

Welcome to my repository! CALEO is a browser plugin that does the work of scouring through online videos for you. Simply visit a video page, activate the plugin, and see all of the video's highlights displayed visually for you, with nifty timestamps, the ability to easily jump to any of these key points in the video, and a (usually) precise estimate of where you'll find the original video thumbnail. Spend enough time on the video, and your viewing behaviour will update my servers with the intervals of video that you spent your time watching, helping others in the effort to sift through the online junk that just wastes everybody's time.

### Tech
I use the Microsoft Azure platform to run my virtual machine as well as integrate my API smoothly into a Mongo database, which holds all of the relevant info about individual videos in nicely defined documents. Backend code is written entirely in python, and the beautiful user-interface is done in Javascript ([highcharts.js](https://www.highcharts.com)) and makes use of a modified version of stock visualizations, which helps display viewing frequency.

Thumbnail analysis utilizes AI Computer Vision to compare the thumbnail image with frames in the video. It finds the most similar frame and indicates where the thumbnail is most likely to appear in the video.

### What it does
CALEO analyzes YouTube videos to give people a way to summarize YouTube videos, so that they can see the parts that are important to them.

### How I built it
I used a MongoDB database to store my data, as well as a Python back end and a JavaScript front end, all hosted on Microsoft Azure.

### Challenges I ran into
I had difficulties with some of the technologies that I wasnt used to. For example, I was inexperienced with front end JavaScript, so I spent a large amount of time debugging and cleaning it up.

### Accomplishments that I'm proud of
My thumbnail detection is quite accurate and a good example of basic computer vision.

### What I learned
I learned that things are typically more difficult than you think! I learned how to use Microsoft Azure, as well as how to set up a database, server, and frontend on my own. I also learned about some JavaScript and python functionality that I was not previosly aware of.

### What's next for CALEO
More intricate video parsing, for example using the video indexer on Microsoft Azure, could benefit the project as I could use some more complex data in my analysis.
