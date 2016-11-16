[![](public/images/objectus128.png)](http://github.com/acidjazz/objectus)
![](public/images/plus48.png)
[![](public/images/coffee128.png)](http://coffeescript.org/)
![](public/images/plus48.png)
[![](public/images/pug128.png)](https://pugjs.org/)
![](public/images/plus48.png)
[![](public/images/stylus128.png)](http://stylus-lang.com/)
![](public/images/plus48.png)
[![](public/images/gulp128.png)](http://gulpjs.com//)



# [SPA](https://en.wikipedia.org/wiki/Single-page_application) skeletal setup
> *Note*: currently in early development


## Usage

*  compile all javascript, css, and html
```bash
gulp
```

*  compile all vendor included libraries specified in `gulpfile.coffee` to `public/javascript/vendor.js` and `public/css/vendor.css`
```bash
gulp vendor
```

* compile all 3 but minified, uglified, and non-sourcemaped
```bash
gulp prod
```

* run browser-sync and host `public/` and all its related directories 
```bash
gulp sync
```
