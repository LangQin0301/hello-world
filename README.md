## 9/9/17
### Aurelia Moser
### Metrics + Data Visualization I
### Interactive Critique

## INTRODUCTION

For my critique, I chose [Snowfall](http://www.nytimes.com/projects/2012/snow-fall/#/?part=tunnel-creek). The interactive is a chapterized narrative about climbing and an avalanche, replete with multimedia interactive pieces that punctuate the text as you scroll. It was written by John Branch on December 26th, 2012 with the help of collaborators.

The topic is detailed in the meta tags in the header of the code when you [view source or inspect element](https://blog.kissmetrics.com/how-to-read-source-code/), as here:

`<meta name="description" content="“Snow Fall: The Avalanche at Tunnel Creek,” by New York Times reporter John Branch, tells the harrowing story of skiers caught in an avalanche.">`

## ANALYSIS
From observation, I can see that the author alters the content display as the reader scrolls, creating an individual experience for all viewers set to the pace of their own reading.

From inspecting element on the site, I can see that it uses UTF-8 character encoding in `<meta charset="utf-8">`, it has many browser support modifcations such as `<!--[if lt IE 7]> <html class="no-js lt-ie9 lt-ie8 lt-ie7"> <![endif]-->`, 

It uses a combination of Javascript, HTML, and CSS as seen in the metatags in the `<header>` and the `<style>` tags (primarily CSS): 
`<link type="text/css" rel="stylesheet" href="http://graphics8.nytimes.com/packages/css/multimedia/bundles/projects/2012/AvalancheDeploy.css">`

From ["built with"](http://builtwith.com/?http%3a%2f%2fwww.nytimes.com%2fprojects%2f2012%2fsnow-fall%2f%23%2f%3fpart%3dtunnel-creek), I can tell that it's uses Wordpress as a CMS, PHP as a framework for the backend, a series of JQuery plugins and Javascript library, embedded Youtube videos and tweets, media queries for mobile compatibility, and HTML5 Boilerplate.

Maybe the most interesting parts were the comments in the code, explaining why certain decisions were made like this one in the css: 

`/* -----------------------------------------------------  footer tweak to avoid extra space below video */
/*this seems to allow you to scroll past the video and cause the entire page to fade to 0 */`

In the Console, I noticed there was an error `Uncaught TypeError: Cannot read property 'createOptions' of undefined`, I googled it and found this [StackOverflow](http://stackoverflow.com/questions/6550795/uncaught-typeerror-cannot-read-property-value-of-undefined) explanation but I am not sure it fully applies to my issue. 

I feel the most compelling aspect of the interactive is how it seemed to move, heave, and swell with the user scroll, I would like to learn how to make that happen in code.

## RESOURCES

* Braven, J., [Snowfall](http://www.nytimes.com/projects/2012/snow-fall/#/?part=tunnel-creek).
* [Built With](http://builtwith.com/).
* [Markdown syntax](http://daringfireball.net/projects/markdown/basics).

## IMAGE

![Snowfall Inspect Element](https://raw.githubusercontent.com/auremoser/web-coding/master/_imgs/snowfall.jpg)

**Source for graphic**: Braven, J., [Snowfall](http://www.nytimes.com/projects/2012/snow-fall/#/?part=tunnel-creek).
