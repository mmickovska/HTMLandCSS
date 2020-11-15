>> **HTML5 Game Engines**

## Why Developers Use Game Engines
Every language and library is at some level an abstraction. Developers don’t write their code in binary. Most don’t use an assembly language, and even C is considered too cumbersome for the majority of modern developers, which is why higher-level languages, i.e. languages that abstract more behaviors, are the most used and most in-demand for developers.
Although JavaScript is a higher level language, it still asks a lot of the developer when it comes to the sort of logic demanded by games. What is the edge of the map? How do I draw assets continuously as a player moves? How do I accept input from a gamepad, keyboard, mouse, and touch? What animation plays when x enemy dies as opposed to y enemy dies? What happens when a game starts? How do you load a saved game? What constitutes game over? All these questions have to be answered in order to have a proper playable game. While it’s possible to answer these questions in JavaScript — or even binary! — you will save yourself a lot of work by giving the most fundamental and oft-repeated concepts to a game engine.
While Unreal and Unity and Crytek are awesome free tools for game developers, they are not intended for a web audience. To make a game built from the ground-up to play nicely in a browser window, it’s better to use tools with that goal in mind.
Enter HTML 5 game engines.
My partner and I knew we wanted to make a game, but we also knew we didn’t want to figure out all the math and physics and states when there were a host of libraries out there. After poking through the options on HTML5 Game Engine, our list of tools boiled down to some obvious candidates.
There are two major flavors of HTML5 game engines: those with a GUI and those without. Perhaps unsurprisingly, the two most robust GUI engines are also the most popular, so we’ll start with those:

* GUI-Based HTML5 Game Engines
[GDevelop](https://gdevelop-app.com/) and 
[Construct 3](https://www.scirra.com/)


While both of these GUI game engines are well-supported and have enormous communities, my partner and I immediately dismissed them. GDevelop may have been viable for a longer-term project, using a GUI to do all the work necessarily prevented us from learning how to code a game. It’s right there in GDevelop’s pitch: “Create games without programming.” That’s not what we were looking for in a coding boot camp.

* Non-GUI Options

Now we’re talking. All of the following engines have different tradeoffs and philosophies, and even though they abstract complicated ideas away from the user, they still demand an intermediate to high amount of JavaScript knowledge.

[ImpactJS](https://impactjs.com/)

ImpactJS comes bundled with a few extra goodies that make it a pleasing all-in-one package. When reviewing the code-heavy game engines, though. Reviewers consistently sided with Phaser 3 over ImpactJS for the simplicity of Phaser’s design.

[BabylonJS](https://www.babylonjs.com/)

BabylonJS leans into the realm of 3D game development in HTML5. If we were interested in making a 3D game, we probably would have gone with BabylonJS, but since we were aiming for a simple 2D game, we went another way.

[pixi.js](https://github.com/pixijs/pixi.js)

Perhaps unfairly, pixi.js is often brought up as a substitute for old-school Flash games, especially since Adobe is discontinuing all Flash support in 2020. Since we didn’t have a lot of Flash experience between us, it seemed like it might be better to use one of the other tools.

[Phaser 3](http://phaser.io/)

Phaser is a warhorse of 2D game development, and its syntax seemed, from my inspection, the closest to dealing with JavaScript without the same volume of headaches, so that’s what I ended up going with.

Truthfully, we don’t have nearly enough experience in any of the above tools to give an informed opinion. Every tool has a best usage case. While I intend to poke around in all the game engines to figure out the best fit for me, I’m excited to make things in Phaser 3 to sharpen my burgeoning game design skills!

>> **HTML5 Game Development**

There are plenty of valid ways to create an HTML5 game, and quite a bit of material on the technical aspect of each, so for this article I’ll be giving more of a broad overview of HTML5 game development. How “HTML5” can be better than native, where to start with the development process, where to go when you’re stuck, and how to monetize and distribute games.

Most of the audience here already sees the value in HTML5, but I want to re-iterate why you should be building an HTML5 game. If you are just targeting iOS for your game, write the game in Objective-C, the cons outweigh the benefits in that scenario… but if you want to build a game that works on a multitude of platforms, HTML5 is the way to go.

* ## Cross-Platform

One of the more obvious advantages of HTML5 for games is that the games will work on any modern device. Yes, you will have to put extra thought into how your game will respond to various screen sizes and input types, and yes, you might have to do a bit of ‘personalization’ in the code per platform (the main inhibitor being audio); but it’s far better than the alternative of completely porting the game each time.

I see too many games that don’t work on mobile and tablets, and in most instances that really is a huge mistake to make when developing your game – keep mobile in mind when developing your HTML5 game!


* ## Unique Distribution


Most HTML5 games that have been developed to this point are built in the same manner as Flash and native mobile games. To some extent this makes sense, but what’s overlooked is the actual benefits The Web as a platform adds. It’s like if an iOS developer were to build a game that doesn’t take advantage of how touch is different from a mouse – or if Doodle Jump was built with arrow keys at the bottom of the screen instead of using the device’s accelerator.

It’s so easy to fall into the mindset of doing what has worked in the past, but that stifles innovation. It’s a trap I’ve fallen into – trying to 100% emulate what has been successful on iOS, Android, and Flash – and it wasn’t until chatting with former Mozillian Rob Hawkes before I fully realized it. While emulating what worked in the past is necessary to an extent, The Open Web is a different vehicle for games, and innovation can only happen when taking a risk and trying something new.

Distribution for HTML5 games is often thought of as a weakness, but that’s just because we’ve been looking at it in the same sense as native mobile games, where a marketplace is the only way to find games. With HTML5 games you have the incredible powerful hyperlink. Links can so easily be distributed across the web and mobile devices (think of how many links you click in the Facebook and Twitter apps), and it certainly should not just be limited to the main page for the game. The technology is there to be able to link to your game and do more interesting things like jump to a specific point in a game, try to beat a friend’s score, or play real-time against that friend – use it to your advantage!

Take a good look at was has worked for the virality of websites and apply those same principles to your games.

* ## Quicker Development Process

No waiting for compilation, updates and debugging in real-time, and once the game is done, you can push out the update immediately.

* ## Choosing a Game Engine
Game engines are just one more level of abstraction that take care of a few of the more tedious tasks of game development. Most take care of asset loading, input, physics, audio, sprite maps and animation, but they vary quite a bit. Some engines are pretty barebones, while some (ImpactJS for example) go as far as including a 2D level editor and debug tools.

* ## Decide Whether or Not You Need a Game Engine

This is largely a personal decision. Game Engines will almost always reduce the time it takes for you to create a fully-functional game, but I know some folks just like the process of building everything from the ground up so they can better understand every component of the game.

For simple games, it really isn’t difficult to build from scratch (assuming you have a JavaScript background and understand how games work). Slime Volley (source) for example was built without having a game engine, and none of the components were rocket science. Of course, Slime Volley is a very basic game, building an RPG from the ground up would likely lead to more hair pulling.

* ## Choosing Between a “Game Engine” and a “Game Maker”

Most of the typical audience of Mozilla Hacks are probably going to lean toward using a game engine or building from scratch, but there is also the alternative of using a “Game Maker” like Construct 2. Using a Game Maker means you won’t actually write in JavaScript; instead, you create code-like events in the editor. It’s a trade of ease-of-use and quickness to prototype/develop vs customization and control over the end result. I’ve seen some very impressive games built with either, but as a developer-type, I tend to favor writing from scratch / using an engine.

* ## Finding the Right Game Engine / Game Maker for you

There are so many HTML5 game engines out there, which in part is a good thing, but can also be a bad thing since a large percentage have either already stopped being maintained, or will soon stop being maintained. You definitely want to pick an engine that will continually be updated and improved over the years to come.
HTML5GameEngine.com is a great place to start your search because the hundreds of game engines are narrowed down to about 20 that are established, actively maintained, and have actual games being developed with them.

For a more complete list of engines (meaning there can be some junk to sift through), this list on GitHub is your best bet.

* ## Technical Tutorials

jsGameWiki is full of links to technical tutorials and resources.
HTML5 Gamedev Starter – similar to jsGameWiki, but a bit easier to digest.
Mozilla Hacks -> Games
How To Design A Mobile Game With HTML5 for developing a game that’s mobile friendly.
No Tears Guide to HTML5 Games is relatively old (2.5 years), but still is a very good learning tool if you’re not using a game engine.


* ## Game Design Tutorials

With game development, the technical aspect isn’t everything – what’s more important is that the game actually be fun. Below are a few places to start when learning about game mechanics.

Fewer Mechanics, Better Game
Gamasutra -> Design
HTML5 Games: Learning from Mobile and Flash Games

* ## Helpful Game Tools

User Retention, Monetization and more
Full disclosure here: I am a co-founder at Clay.io.

Making a game function is just part of the equation. You also want players to play longer, come back, tell their friends about it, and maybe even buy something. Common elements in games that focus on these areas are features like user accounts, high scores, achievements, social integration, and in-game payments. On the surface most are typically easy enough to implement, but there are often many cross-platform issues and intricacies that are overlooked. There is also value in having a central service running these across many games – for example, players genuinely care about achievements on Xbox Live because Gamerscore matters to them.

Clay.io – user accounts, high scores, achievements, in-game payments, analytics, distribution, and more.
Scoreoid – similar to above.

* ## Development Tools

stats.js – A JavaScript performance monitor. Displays framerate, and performance over time.
Socket.IO – realtime client-server communication (if you’re going to have a backend for your game).
pixi.js – A canvas and WebGL rendering engine.
CocoonJS – Improves HTML5 game performance on iOS and Android with an accelerated canvas bound to OpenGL ES.