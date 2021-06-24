# el.js
Use simple JavaScript to write interactive HTML.

## Status
To be build..

## Introduction

This is a for fun library which is spin-off from the
https://github.com/malcomwu/musje; a sheet music and musical processing
library in numbered musical notation.

## APIs in summary

Create an internal element object:
```
el(elName, attrs {}, content [])
el(elName, content [])
el(elName)
```

Same as above but create an dom element:
```
el.create()
```

Assign created element to a property `name` of object `obj`:
```
el.assign(obj, name).create()
```

Push created element to a property `name` of object `obj`:
```
el.push(obj, name).create()
```

Same as `el()` but create the content in html:
```
el.html()
```

Create the amount `num` of none breaking spaces:
```
el.nbsp(num)
```

Create data to sync with the html or link it from data to data:
```
el.setData()
el.linkData()
```
