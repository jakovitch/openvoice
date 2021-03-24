# Welcome! to OpenVoice 🎙
OpenVoice is a painless method to host a podcast on your website without PHP, Ruby, Python or other difficult procedures. You have only to change some files and you are ready to host your podcast. 

## How to: customize OpenVoice
To personalize OpenVoice you need to change some JS files.
You can use a text editor, for example Notepad++.

After personalization, check your code. Here two handy tools:
**JS Beautifer**: [Press here](https://beautifier.io/)
**JS Validator**: [Press here](https://esprima.org/demo/validate.html)

### properties.js
You will find this at ***/assets/js/properties.js**, and you had to change some properties:
* **title**: the name of your podcast, it will be used in many occurencies.
* **desc**: the description of your podcast, it will published on the homepgage.
* **beta_advise**: Enable or Disable the "OpenVoice is in beta" alert.

After these setting, you will find the external links, each "social" has a:
* **enabled** property, that enable the button or not.
* **href** property, here you need to paste the link.

### tracklist.js
This file contains your episodes, it is in ***/assets/js/tracklist.js***, for every track you need to specify:
* **name**: the title of your episode, it will showed in the player.
* **desc**: the description, for example what you will talk about.
* **active**: with "false", the specified episode will be hidden.
* **path**: the path of your track, only mp3 supported.

Indexing is automatic, just put your episode in order in the ***track_list** array.


## Put on a web server
You don't need to install PHP or something else.
OpenVoice run in "local" on a javascript-enabled browser.
You can check ***beta.html*** to view supported browser.
