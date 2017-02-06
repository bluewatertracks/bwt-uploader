## A bower build for [mozilla/pdf.js](https://github.com/mozilla/pdf.js)

### Usage

`bower install pdfjs-bower --save`

Link the necessary javascript files into your page.

    <script src="/bower_components/pdfjs-bower/dist/compatibility.js"></script>
    <script src="/bower_components/pdfjs-bower/dist/pdf.js"></script>

__Enjoy__

---

### Updating or building manually
Currently the build is for pdf.js `v1.0.233`.
You can build yourself by doing the following

##### Prepping (getting pdf.js)
- `git clone https://github.com/joseym/pdfjs-bower.git`
- `git submodule init`
- `git submodule update` -- used to get the current version of pdf.js

##### Building
> In your terminal please navigate to where the project is cloned

- `cd pdfjs-bower`
- `npm install -d`
- `grunt`

> You should now see 3 files within the `dist` directory

- `pdf.js`
- `pdf.woker.js`
- `compatibility.js`