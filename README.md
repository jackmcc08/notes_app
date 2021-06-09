# Notes App

Makers Week 7 Afternoon Group Coding Challenge.

Notes App created by:
- Will - willspencer16
- Alex - yates101
- Stu - StuBehan
- Jack - jackmcc08

The was created with vanilla Javascript(no packages like jQuery), HTML and CSS. It also incorporates an emoji API to generate emojis based on shortcodes and utilise localContent on your browser to preserve the notes data.

As part of development we also created our own testing script - `Is it ducking working?`

The app is hosted on github pages, please visit the following on your browser (tested on chrome and firefox):
- Notes App: https://willspencer16.github.io/notes_app/
- Test page for App: https://willspencer16.github.io/notes_app/TestRunner.html
		- look in the console on developer tools (cmd + option + i) for output of all the tests.

Image Credits:
- Testing gif - Giphy - https://gph.is/2JzLlHY
- Background image of web page - Ann H - https://www.pexels.com/photo/snow-water-summer-winter-6432494/

Trello Board for Planning:
- https://trello.com/b/IOFj0gu7/notesapp

## Development History

The application was developed over a 4 day week in the afternoon only, by a group of 4 people. Our approach was to use Vanilla JS, so we could understand how to build dynamic and responsive web apps without the use of simplifying packages. 

In addition we were tasked with building our own testing app which we did with delight. 

On completion the app passed all tests we wrote from our testing suite.

## Tech Stack
- Vanilla Javascript
- HTML, CSS
- Use of local storage to store notes
- connects to emojify API - https://makers-emojify.herokuapp.com/

## To develop further

1. git clone to your local machine
2. run `yarn install`
3. open index.html in project root to see app working in your browser
4. open TestRunner.html in project root see testing suite in your browser (you need to open the developer console to see the tests run)

## User Stories:

All delivered

```
As a programmer
I can see a list of my notes, where each note is abbreviated to the first 20 characters
So I can find the one I want
```

```
As a programmer
I can create a new note
So I can record something I need to remember
```

```
As a programmer
I can see the full text of an individual note on its own page
So I can see all the information in the note
```

```
As a programmer
I can use shortcodes like `:fire:` that get converted into emojis like 🔥
So I can record notes with fun little pictures
```

<!-- ### MVP:

Notes:
- [x] Separate js class for notes
- [x] Return first 20 characters


List of notes:
- Separate class for list of notes, consisting of notes
- New note
- View note

Index.html:
- Displays the above


### Phase 2:

Notes class
- Edit notes

List of notes class
- Delete notes


### Model:

Class Note {
	constructor (content) {
		this.content = content
	}

	preview () {
		return string 20 characters
	}
}


Class List {
	constructor () {
		this.store = []
	}

	createNote (content) {
		add created note to this.store
	}
}


## Local Storage route model

makeNote on click
	-> createNote
		-> store.push(content)
			-> mountPreviews
				-> getPreviews(store)
					-> note.preview() -->
