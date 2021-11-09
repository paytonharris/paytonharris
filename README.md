# Hello!

 I'm Payton Harris, full-stack software engineer with a focus on React and iOS Swift.

# Projects

## Personal Site

<img src="https://github.com/paytonharris/paytonharris/blob/master/images/paytonharris.png?raw=true" alt="payton harris personal site preview" width="400"/>

[paytonharris.com](https://paytonharris.com)

A business card style site with links reach me.

View the [code on GitHub](https://github.com/paytonharris/payton-site). 

It's written in __React__ and hosted using __AWS S3__, __CloudFront__, and __Route 53__.

## Unheard Noise

<img src="https://github.com/paytonharris/paytonharris/blob/master/images/unheardnoise.png?raw=true" alt="unheard noise site preview" width="400"/>

View on [unheardnoise.web.app](https://unheardnoise.web.app).

A __React__ site that plays a random highly-rated album to wake up your senses to something beautiful you've never heard before.

First, I created a __Node.js__ script to scrape highly-rated albums from my favorite critic's site using __cheerio.js__, then placed the results in a __Cloud Firestore__ database. Then I created an API endpoint using __Cloud Functions__ which retrieves a random album from the Firestore database. The website uses this endpoint to get the name of a great album, which it uses to search the __YouTube API__ for the first video result, and then plays the video.

Check out how the background color of the site changes over time. Every 30 seconds, it chooses two new random colors to use as a gradient, then slowly fades to it. This creates lots of colorful combinations over time, and is probably my favorite thing about this project. 

The randomness of the YouTube result adds another sense of adventure to the site. Sometimes you get the full album; other times a review of the album or an interview. 

This idea could also be used for great movie clips, lectures, philosophers, and so much more, simply by adding more entries to the database.

_Secret: Press `h` on the website to hide the video player for added immersion and surprise._

View the [code on GitHub](https://github.com/paytonharris/unheardnoise). 

## Groupgram Chat App

A __React Native__ / __Redux__ app where users can create groups and chat, share pictures, and like posts. Users could take pictures directly from the app, and other users were notified to the new message via push notifications. It uses the __Google Cloud__ for authentication, __Firestore__ for chat data and group metadata (likes, title, members, etc.), and __Cloud Storage__ for images. My family used this app to document building our back deck.

<img src="https://github.com/paytonharris/paytonharris/blob/master/images/gg-signin.jpg?raw=true" alt="groupgram sign-in" width="175"/>
<img src="https://github.com/paytonharris/paytonharris/blob/master/images/gg-home.jpg?raw=true" alt="groupgram home" width="175"/>
<img src="https://github.com/paytonharris/paytonharris/blob/master/images/gg-chat.jpg?raw=true" alt="groupgram chat" width="175"/>
<img src="https://github.com/paytonharris/paytonharris/blob/master/images/gg-done.jpg?raw=true" alt="additional groupgram chat" width="175"/>

## Collector

<img src="https://github.com/paytonharris/paytonharris/blob/master/images/collector.png?raw=true" alt="collector site preview" width="400"/>

A React puzzle game themed around writing programming commands by sifting through memory garbage.

*Notice how the text on the home page becomes scrambled over time, like memory becoming corrupted.*

Hosted on Google Cloud [here](https://collector-188a6.web.app). View [the code on GitHub](https://github.com/paytonharris/Collector). 

## Password Generator

<img src="https://github.com/paytonharris/paytonharris/blob/master/images/passgen.png?raw=true" alt="password generator site preview" width="400"/>

A simple React site that generates passwords based on specific rules. I made this for some friends who reset passwords daily and previously had to make up new temporary passwords manually. This saves time, energy, and increases security since many people would use the same temporary password for everyone to save time.

Hosted on Google Cloud [here](https://beanmaster-passgen.web.app). View [the code on GitHub](https://github.com/paytonharris/PasswordGenerator). 