# Acid

Advanced content user-interface displayer

##### What is Acid?

Acid is a library built to help mobile developers in displaying complex content in a native way. By complex we mean content rich with links, and social networks embeds.

##### What does Acid mean?

Acid is the abbreviation of Advanced Content user-Interface Displayer. Yes it does what it sounds like.

##### What are we displaying here?

We're gonna be showing the embeds such as:

* [Facebook posts](https://github.com/Vinelab/acid/wiki/Facebook)
* [Twitter tweets](https://github.com/Vinelab/acid/wiki/Twitter)
* [Instagram media](https://github.com/Vinelab/acid/wiki/Instagram)
* [YouTube videos](https://github.com/Vinelab/acid/wiki/Youtube)

Not to mention the in-text hyperlinks and redirection words.

##### Why Acid?

Usually in most mobile solutions displaying complex content, the developers use a native web view. Just like reading a website article, it will look the same. Yet handling the content UI and responsiveness, not to mention the user-experience- will be difficult for the developers. What about a solution to fully customize the content in-app? Acid is here.

##### What is it based on?

Well to be honest, we as mobile developers always nag about not being able to display natively the content for our users in a smooth way. But we couldn't do much about it. We receive some HTML text and we throw it in a web view.
And then came our backend team, with a great solution: [The Laravel Editor](https://github.com/Vinelab/laravel-editor). From what it explains, this will transform the HTML content into a clean JSON response. The response will have the embeds with all the needed data surrounding each one separately. 
Our mission will be to handle those detailed objects and display freely the content.

##### What's missing?

Until now, the social providers (Facebook, Twitter, Instagram) haven't provided us with proper embed views in their SDKs, only YouTube did. This will be explained in details in the next pages. This left us handling everything from scratch. So we're gonna build the UI basis. Anyone can customize the views depending on his product UI. We will always wait for the providers to include those native views in their SDKs in the future. The shift will be smooth for sure.

##### Final thoughts

We all hope this can be the first native solution in parsing and displaying such content. This should be done natively aside from a web view, and we hope to give the community the lead for that purpose.

##### Acid mobile libraries

ACID-Android: https://github.com/Vinelab/acid-android

ACID-iOS: https://github.com/Vinelab/acid-ios
