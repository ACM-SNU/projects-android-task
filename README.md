# SNU ACM Projects | Android Task

The task is to create an Android application that displays two text fields and an image inside a card view. The app should parse a remote JSON file to fetch the text field values and the image URL. There are two items in the JSON file and the contents of each one of them should be displayed in a separate card view.

The JSON file that the app should parse: ``
The following is the structure of the JSON file for your reference:
```json
{
  "items": [
    {
      "title": <string, text>,
      "sub": <string, text>,
      "image": <string, URL>,
    },
    ...
  ]
}
```

The result should look close to the following wire-frame:

