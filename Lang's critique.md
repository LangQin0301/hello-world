## 9/12/17
### Lang Qin
### Metrics + Data Visualization I
### Interactive Critique

## INTRODUCTION

For my critique, I chose [hollowdocumentary](http://hollowdocumentary.com/). Hollowdocumentary.com contains six short interactive documentaries, they tell a story of McDowell County located in West Virginia. For the past half century, the small town went through dramatic changes of boom and bust economies, faced many chanllenges like losing job opportunities and twice flood disasters. While a large amount of population had left, many residents still insisted to stay and dedicated to prosper their community and hometown, which represents the people's authentic living situation in rural America and the history of the country.


## ANALYSIS

After reviewing many websites, I chose this interactive because I am interested in history and society, I want to learn what individules experience through the changes of time and environemnt, and how people face the changes beyond their control. This interactive fascinated me both by it's design and content.
I was impressed by the visual effect when I first browsed the website, the form of interactive documentary was a total novelty to me, rather than traditional static display of images and texts, I love the interactive experience which combines video portraits, data visualizations, photography, soundscapes, community-generated content and grassroots mapping to bring these stories to life online. The combination is very rich and varied, which fixed my eyes on it all the way to the end. 

I think the varied forms of expression are very conductive to the content, the background information I found says nearly twenty of the town's residents contributed short films, which range in topic from economic and infrastructure challenges to social and health issues. they are small-business owners, youth groups, coal miners, activists, high school students, fitness instructors and non-profit sector workers, they have different profile, life style and point of view. I think the author found a excellent way to organize these rich resources, the documentaries were made like colorful collages, which represent a vivid and comprehensive image of the whole community.

As the reader scrolls, the content unfolds from different directions, in varied forms, and the sound changes as well. The reader can control the speed of scrolling, move back and forth, so as to have her\his own pace of reading, the author hided more detailed information (including self-introductions, video portraits, credits and links of useful resource) on many pages and left tags as reminders, if the reader click these tags he\she can explore further.

From inspecting element on the site, I can see that it uses UTF-8 character encoding in `<meta charset="utf-8">`

It uses a combination of Javascript, HTML, and CSS as seen in the metatags in the `<style>` tags (primarily CSS): 

`<link href="http://fonts.googleapis.com/css?family=Asul:400,700|Quattrocento+Sans:400,400italic,700,700italic|Libre+Baskerville:400,400italic|Lekton|Anaheim|Cookie" rel="stylesheet" type="text/css">`

From ["built with"](http://builtwith.com/?http%3a%2f%2fwww.nytimes.com%2fprojects%2f2012%2fsnow-fall%2f%23%2f%3fpart%3dtunnel-creek), I can tell that 



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
