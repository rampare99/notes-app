# Notes App
Basic notes app made using chalk and yargs. It works in the terminal and it saves your notes in a JSON file.

## Installation
```
npm install
```

## Usage
###### Create a note
```
node app.js add --title="your title" --body="your description"
```
###### Remove a note
```
node app.js remove --title="your title"
```

###### List all notes
```
node app.js list
```

###### Read a note
```
node app.js read --title="your title"
```
