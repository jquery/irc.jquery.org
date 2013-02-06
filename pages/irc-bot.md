# IRC Bot
The IRC bot, b-ot, is a helpful little minion that you can use inside the IRC room to get quick access to info from around the web.

## Using the bot
b-ot comes with a number of commands. All commands consist of the <code>`</code> (backtick) plus the trigger word. Most commands also have a shorthand single letter trigger.

### jQuery API
Quick access and search of the jQuery API. 

**trigger:** \`api <term>

	wesbos      `api slideUp
	b-ot        wesbos: .slideUp(): Hide the matched elements with a sliding motion. http://api.jquery.com/slideUp/

	wesbos      `api index
	b-ot        wesbos: .index(): Search for a given element from among the matched elements. http://api.jquery.com/index/

### caniuse
### 8ball
### control
### convert
### crew
### desc
### domain
Check if a domain name is available. Uses the [domai.nr](http://domai.nr) API.

**trigger:**  \`d or \`domain <domain>

	wesbos    `domain jquery.com
	b-ot      wesbos: jquery.com - ☹ TAKEN

	wesbos    `d heyoheyoheyo.io
	b-ot      wesbos: heyoheyoheyo.io - ☺ AVAILABLE

### down
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

The Unmentionables
### uptime
### urbandictionary
### wat
