# Hello!

 I'm Payton Harris, full stack software engineer with a focus on React Native and iOS Swift!

# Projects

## Personal Site

<img src="https://github.com/paytonharris/paytonharris/blob/master/images/paytonharris.png?raw=true" alt="payton harris personal site preview" width="400"/>

paytonharris.com

A business card style site with links reach me.

View the [code for it on GitHub](https://github.com/paytonharris/payton-site). 

It's written in React and hosted using AWS S3, CloudFront, and Route 53.

## Unheard Noise

<img src="https://github.com/paytonharris/paytonharris/blob/master/images/unheardnoise.png?raw=true" alt="unheard noise site preview" width="400"/>

View on [unheardnoise.web.app](https://unheardnoise.web.app).

A React site that plays a random highly-rated album to wake up your senses to something beautiful you've never heard before.

This project had several facets. First, I created a __Node.js__ script to scrape highly-rated albums from my favorite critic's site using __cheerio.js__, then placed the results in a __Cloud Firestore__ database. Then I created an API endpoint using __Cloud Functions__ which retrieves a random album from the Firestore database. The website uses this endpoint to get the name of a great album, which it uses to search the __YouTube API__ for the first video result, and then plays the video.

Check out how the background color of the site changes over time. Every 30 seconds, it chooses two new random colors to use as a gradient, then slowly fades to it. This creates lots of colorful combinations over time, and is probably my favorite thing about this project. 

The randomness of the YouTube result adds another sense of adventure to the site. Sometimes you get the full album, other times a review of the album or an interview. 

This idea could also be used for great movie clips, lectures, philosophers, and so much more, simply by adding more entries to the database.

_Secret: Press `h` on the website to hide the video player for added immersion and surprise._

## Collector

<img src="https://github.com/paytonharris/paytonharris/blob/master/images/collector.png?raw=true" alt="collector site preview" width="400"/>

A React puzzle game themed around writing programming commands by sifting through memory garbage.

*Notice how the text on the home page becomes scrambled over time, like memory becoming corrupted.*

Hosted on Google Cloud [here](https://collector-188a6.web.app). View [the code on GitHub](https://collector-188a6.web.app). 