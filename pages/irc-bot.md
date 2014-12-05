<script>{
	"title": "IRC Bot Commands"
}</script>

The IRC bot, b-ot, is a helpful little minion that you can use inside the IRC room to get quick access to info from around the web.

## Using the bot

b-ot comes with a number of commands. All commands consist of the <code>`</code> (backtick) plus the trigger word. Most commands also have a shorthand single letter trigger.

You can also direct the bot to answer at someone other than yourself by appending

	wesbos      `api slideUp @ajpiano
	b-ot        ajpiano: .slideUp(): Hide the matched elements with a sliding motion. http://api.jquery.com/slideUp/

## Commands you can use in #jQuery

It is acceptable to use any of the following commands in #jQuery. Please be mindful and do not spam the chatroom with commands.

### jQuery API

Quick access and search of the jQuery API.

**trigger:** \`api <term>

	wesbos      `api slideUp
	b-ot        wesbos: .slideUp(): Hide the matched elements with a sliding motion. http://api.jquery.com/slideUp/

	wesbos      `api index
	b-ot        wesbos: .index(): Search for a given element from among the matched elements. http://api.jquery.com/index/

### caniuse

An interface for [caniuse.com](http://caniuse.com/). Use this to find out browser compatibility for HTML5/CSS3 features.

**trigger:**  \`c or \`caniuse <term>

	wesbos    `c canvas
	b-ot      wesbos: You can use Canvas (basic support) with: Internet Explorer 9, Firefox 2, Chrome 4, Safari 3.1, Opera 9, iOS Safari 3.2, and Opera Mobile 10. http://caniuse.com/#search=canvas

	wesbos    `caniuse web workers
	b-ot      wesbos: You can use Web Workers with: Internet Explorer 10, Firefox 3.5, Chrome 4, Safari 4, Opera 10.6, iOS Safari 5.0-5.1, and Opera Mobile 11. http://caniuse.com/#search=webworkers

### 8ball
### control
### convert
### desc
### domain
Check if a domain name is available. Uses the [domai.nr](http://domai.nr) API.

**trigger:**  \`d or \`domain <domain>

	wesbos    `domain jquery.com
	b-ot      wesbos: jquery.com - ☹ TAKEN

	wesbos    `d heyoheyoheyo.io
	b-ot      wesbos: heyoheyoheyo.io - ☺ AVAILABLE

### down

Check if a website is down. Mimics the functionality of [downforeveryoneorjustme.com](http://www.downforeveryoneorjustme.com/).

This command accepts domain names, ports and paths. It will tell you if the site is really down as well as the status code.

**trigger:** \`api <url>

	wesbos    `down jquery.com
	b-ot      wesbos: It's just you. http://jquery.com is up! (200 OK)

	wesbos    `down jquery.com/not-a-real-page
	b-ot      wesbos: It's not just you! http://jquery.com/not-a-real-page is down! (404 Not Found)

### eval
### factoid
### flair
### github
### google
### ideone
### kickflip
### seen
View the last time a user was on the IRC network.

### shared
### spotify
### tell
### twitter
### weather

## Commands you can use in your own IRC Channel

Some of these commands will be disabled in #jQuery

### crew
### uptime
### urbandictionary
### wat
