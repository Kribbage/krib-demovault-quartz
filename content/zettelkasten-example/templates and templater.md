---
courseid: 4
---

#obsidiancourse 

# Templates and the templater community plugin 


## Templates - what are they?

Templates are files in a specified folder in your vault - usually the /templates/ folder - that holds [[markdown]] files that you can use as a base for creating new notes, journal pages, or anything else repetitive that you may need to insert into another note. It also has some features that let you replace some of the text in the template using special tags that tell the template plugin to do some action such as:

- Inserting the current date and time into the file 
- renaming the file with a unique timecode or ID 
- moving files
- fetching certain information from the web and placing it as text in your file
- many more things


>[!warning] warning
>you are telling the plugin to modify your files when you use this so there is risk of accidentally deleting content if you make a mistake. So just be make sure you have backups of anything you cannot afford to lose.


## Why are we using them?

>you can get as complicated as you would like with templater but for the majority of people, we are just trying to remove friction and save time by automating redundant, tedious tasks like naming files and creating the same few headers, tags or metadata in your daily, quick capture or permanent notes.


## Templates - basic functionality

>Once you have created a folder for your templates to live in, you can specify it in the settings and then begin making templates. 

- First, you will create a file with a relevant name.
- Input any formatting - headers, tags, metadata, etc. - that you wish for any note matching that template to have.
- next change out any "wildcard" text you would like the templates core plugin to replace with a different piece of information
	- e.g. {{date}} when inserted into a new file outputs 2023-02-17 - (as of this writing)
	- {{title}} - returns the title of the active note
	- {{time}} - current time when created
- these are part of the core template plugin - the templater community plugin allows for many more "wildcards"

## Templater - community plugin


Templater has syntax auto completion similar to how the file linking popup works. So, it is somewhat intuitive if you have ever tinkered with coding or scripting and the examples you find need to be tweaked for your use.

a date "wildcard" for templater looks like this.

```
tp.date.now("YYYY-MM-DD HH mm SS") 
<% tp.date.now("YYYY-MM-DD HH mm SS") %>
```

[Templater Documentation](https://silentvoid13.github.io/Templater/introduction.html)

>[!info] Templater
>Templater is a community plugin that expands the functionality of base templates, there is a little bit of code involved but it are a lot of helpful resources to just copy paste into your templates and once you have them set up it is as simple as clicking a button.  I'm going to provide some useful snippets as well. 

>Use the second link in the web version of this vault. The following will work only if opening this vault directly in obsidian from the releases page.


Let's go back [[home canvas.canvas| home]] but its a little different.

[_home - Web link](https://demovault.kribbitt.cc/home-canvas.html)