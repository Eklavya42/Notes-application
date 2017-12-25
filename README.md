# Notes-Application
Node.js command line application built for creating, removing and listing notes.


### Prerequisites

To get this project on your local machine, you need to have [Node.js](https://nodejs.org).

### Installing

Install the project  by navigating to the note-app directory  in bash  and running



```bash
npm install
```

This will install all the necessary dependencies. 

### How To

 Main functionality of the application will be shown here .
 To see the help, run: 

```bash
node app.js --help
```

###  To Add a note

You can add a note simply by runnning the following command in the project directory:

```bash
node app.js add -t=“Title of Note" -b=“Body of the note"
```

't’ is alias for title and 'b’ is alias for body, so you alternatively write like this too:

```bash
node app.js add --title="Title of Note " --body="Body of the note "
```


### To List all Notes

To list all notes run the following command


```bash
node app.js list
```

This will list all the notes with their information, separated by ----------

### To Show a specific note

To show a specific note, run:

```bash
node app.js read -t title_of_note
```

Where title_of_note is the title of the note you want to read

### Remove a note

To remove a note,

```bash
node app.js remove -t sometitle
```

Where sometitle is the title of one of your notes.


## Built With

* [Node.JS](http://nodejs.org) - Platform
* [Yargs](http://yargs.js.org/) - Parsing command line arguments 
* [Lodash](https://lodash.com) -  Makes JavaScript easier by taking the hassle out of working with arrays, numbers, objects, strings, etc. 

## Author

* **Eklavya Chopra** 

##
##


* Thanks to Andrew Mead for creating the course [The Complete Node.js Developer Course 2.0](https://www.udemy.com/the-complete-nodejs-developer-course-2/)
