app.js and leaflet.js are directly copied from the (leaflet example in the nanocomponent repo)[https://github.com/choojs/nanocomponent/tree/master/example

index.js and index.html are boilerplate for a basic electron app that loads and displays an html page

running app using
`electron index.js`
does NOT trigger any onload event

running using `budo app.js` (or other method using browserify) DOES trigger onload event
