## About
`bwt-uploader` is a file uploader with support for pdf files, jpeg, png and bmp images written in Polymer. It follows a plug and play model with a few configurations needed to enable certain features. It is partially inspired by the vaadin uploader and came out as a result of a component we built at Blue Water Tracks. Images are converted to base64 images which might increase the size of the file by a small percentage.  

## Features
- Simple Drag and Drop along with browse option
- Ability to upload images and pdf files
- Down sample and resize images (optional)
- Ability to upload pdf files
- Preview of pdf and image files (just the first page in case of pdf files)
- Progress Bar
- Configurable AJAX options as well as ability to insert extra fields into the upload object
- Ability to skip downsampling of image
- Configurable maximum file size
- Customizable CSS and shape of preview area

## Installation
To install `bower install bwt-uploader`

To run the code, head into the component's folder and run `polymer serve`

To run the tests `polymer test`

## Demo And Documentation
[bluewatertracks.github.io/bwt-uploader][cf34a7bc]

  [cf34a7bc]: https://bluewatertracks.github.io/bwt-uploader "Demo page"

## Example
A simple example of an Image upload

`<bwt-uploader target="[yourUrl]" method="PUT" body="[[your Object]]" value="[[valueToBeDatabindedAsOutput]]"></bwt-uploader>`

## Feedback and Contributions
 Both are welcome, feel free to create an issue and we will try to come up with fixes or added features for requests.

## Contributors

| | | |
|----------|:-------------:|------:|
| [![@bhargavkonkathi](https://avatars2.githubusercontent.com/u/24550636?v=3&u=ddd3f64f6888100d6eebd283768b61dabc6f495d&s=80)](https://github.com/bhargavkonkathi) |  Programming is like playing chess; each line is as important as each step to determine what kind of player or programmer you are. When ever not playing chess, it's Javascript, Java and mongodb.
| [![@maisnamraju](https://avatars2.githubusercontent.com/u/2786378?v=3&s=80)](https://github.com/maisnamraju) |  Javascript Ninja; saving the world with one line of javascript at a time. ;) 
| [![@dhrytsenko](https://avatars0.githubusercontent.com/u/12988041?v=3&s=80)](https://github.com/dhrytsenko) | What is my opinion about JavaScript, NodeJS, MongoDB and Polymer? Building blocks to the future! Allowing me to help make the world a better place.


## LICENSE
This project is licensed under the terms of the MIT license.
