---
layout: post
title: 'The Design of Pocket Linesman'
date: 2014-02-18 08:00
author_gplus: https://plus.google.com/+JohnRyding
---

[Pocket Linesman](https://itunes.apple.com/us/app/pocket-linesman-referee-wallet/id712375993?ls=1&mt=8) is my first iOS app and the culmination of my years learning the trade of software engineering. It was a project I set out to work on for a few reasons:

- I wanted to create a product from the ground up.
- I felt that I learned enough about graphic design to be able to come up with a great looking UI.
- I wanted to learn iOS development.

I believe items two and three were achieved and I wanted to talk about how I approached the design of Pocket Linesman since there are some nuanced details that I think users will really appreciate.

The overarching theme I followed when designing the app was that I never want to engage the user for more than a couple of seconds. I found this to be an interesting challenge since most of the apps you tend to read about are designed to engage the user for long periods of time. To understand the reasoning for this philosophy, it requires an understanding of how referees work.

When you referee soccer games, you are usually the only referee on the field (games with older players use a three-man system). Not only do you have to manage the game and players, you also need to track all of the data for the game so you can report it later. This includes goals scored, who received major offenses, the time, and other details (depending on the league you are in). When these events happen, you usually take out a pencil and paper to write it down. I found these moments of writing down information to be stressful - especially after I handed out a card to a player (which can result in heightened emotions and confrontation). This is due to being trained to never take your eyes off the game - when you don't see an event occur, you can't make the best decision. Being a referee is a lot like driving a car - looking away from the road is the time when a bad event will most likely occur.

To meet these needs, I needed to make sure the most important information was presented to the user in a clear way and that actions could be performed quickly. You can see this in the score board UI. The most important information of the game is emphasized in large, bold text - the time and scores. Secondary information is there, but with less weight - like the "time" title for the clock area. With the team names, I decided to make them secondary information for the user and instead put emphasis on the team's colors. I learned from Dan Roam's book, [The Back of the Napkin](http://www.amazon.com/The-Back-Napkin-Expanded-Edition/dp/1591842697), that humans are able to respond quickly to images. A referee is constantly moving and their attention is focused on the game - at most they only glance away to their watch to track the time. Understanding this, I knew that referees manage the teams mostly by the color of their jersey. This way, when a goal is scored, the referee doesn't have worry about whether a team is "home" or "away", they just need to match the team's color to the score they need to incremement.

<img src="{{site.url}}/img/pocketLinesman-referee-match-board-vert.png" width="273px" height="525px" alt="Pocket Linesman (a free Referee Wallet app for the iPhone) is designed to be distraction free.">

Expanding on score input, performing actions quickly in the app was actually a fairly easy one to design for. [Fitt's Law](http://en.wikipedia.org/wiki/Fitts's_law) is in full effect in Pocket Linesman; I tried to make the buttons as large as possible so that users would feel comfortable to interact with them when moving around. The one difficult aspect of this design element was the red/yellow card input forms. There is a lot of information we need in order to track an offense - player number, team, and offense type. I tried to make this manual input as fast and painless as possible and will continue to improve this in the future. Fortunately, I think Pocket Linesman's flagship feature gets around this issue.

<img src="{{site.url}}/img/pocketLinesman-referee-player-offense-vert.png" width="273px" height="525px" alt="Pocket Linesman (free for the iPhone) is an all-in-one tool to replace your referee wallet.">

Voice notes is the feature that I believe most embraces my design philosophy of Pocket Linesman the most. Where filling out the form for card offenses takes longer than I like, I find it a lot easier to tap twice from the scoreboard and say, "Yellow card for player 5 on the away team for persistent infringement". Combine this with how the user never has to take their eyes off the game while they capture this information, I think this is a great feature that will benefit all referees.

<img src="{{site.url}}/img/pocketLinesman-referee-new-voice-note.png" width="273px" height="525px" alt="Pocket Linesman - Voice Notes">

All in all, I had a lot of fun creating this app and this is only the beginning. I have a lot of great features in mind that will continue to follow this design philosophy of never wanting users to spend a lot of time interacting with Pocket Linesman.

If you're interested in trying out the app, you can [download your copy here](https://itunes.apple.com/us/app/pocket-linesman-referee-wallet/id712375993?mt=8&uo=4).

