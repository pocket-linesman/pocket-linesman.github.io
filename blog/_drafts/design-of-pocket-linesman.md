---
layout: post
title: 'The Design of Pocket Linesman'
date: 2014-01-16 08:00
author_gplus: https://plus.google.com/+JohnRyding
---

[Pocket Linesman](https://itunes.apple.com/us/app/pocket-linesman-referee-wallet/id712375993?ls=1&mt=8) is my first iOS app and the culmination of my years learning the trade of software engineering. It was a project I set out to work on for a few reasons:

- I wanted to create a product from the ground up.
- I felt that I learned enough about graphic design to be able to come up with a great looking UI.
- I wanted to learn iOS development.

I believe items two and three were achieved and I wanted to talk about how I approached the design of Pocket Linesman since there are some nuanced details that I think users will really appreciate.

The overacrhing theme I followed when designing the app was that I never want to engage the user for more than a couple seconds. I found this to be an interesting challenge since most of the apps you tend to read about are designed to engage the user for longer periods of time. To understand the reasoning for this theme, it requires an understanding of how referees work.

When you referee these games, you are usually the only referee on the field (games with older players use a three-man system). Not only do you have to manage the game and players, you also need to track all of the data for the game so you can report it later. This includes goals scored, who received major offenses, the time, and other details (depending on the league you are in). When these events happen, you usually take out a pencil and paper to write it down. I usually found these moments of writing down information to be stressful - especially after I handed out a card to a player (which can result in heightened emotions). This is due to being trained to never take your eyes off the game - when you don't see an event occur, you can't make the best decision. Reffing is a lot like driving a car - looking away from the road is a likely time that a bad event can occur.

To meet these needs, I needed to make sure the most important information was presented to the user in a clear way and that actions could be performed quickly. You can see this in the score board UI. The most important information of the game is emphasized in large, bold text - the time and scores. Secondary information is there, but with less weight - like the "time" title for the clock area. With the team names, I decided to make them secondary information for the user and instead put emphasis on the team's colors. I learned from Dan Roam's book, ===BLANK===, that humans are able to respond quickly to pictures. A referee is constantly moving and their attention is focused on the game - at most they only glance away to their watch to track the time. Understanding this, I knew that referees manage the teams mostly by the color of their jersey. This way, when a goal is scored, the referee doesn't have worry about whether they team is "home" or "away", they just need to match the team's jersey to the score they need to incremement.

[Scoreboard Picture]()

Expanding on score input, performing actions quickly in the app was actually a fairly easy one to design for. ====Fort's Law=== is in full effect in Pocket Linesman; I tried making the buttons as large as possible so that users would feel comfortable to try and interact with them in a fast way. The one difficult aspect of this design element was the red/yellow card input forms. THere is a lot of information we need there in order to track an offense - player number, team, and offense type. I tried to make this manual input as fast and painless as possible. Fortunately, I think Pocket Linesman's flagship feature gets around this issue.

