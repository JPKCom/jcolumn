# jcolumn
A jQuery plugin to make selected html elements the same height.

###Without jcolumn

![without jcolumn screenshot](http://oliverj.net/img/jcolumn/without-jcolumn.png)

###With jcolum
![with jcolumn screenshot](http://oliverj.net/img/jcolumn/with-jcolumn.png)

##Install
-----

###Bower
```html
bower install jcolumn
```

###The oldschool way
Reference the JavaScript file manually directly after [jQuery](http://jquery.com):

```html
<script src="jcolumn.min.js" type="text/javascript" charset="utf-8"></script>
```

##Usage
-----


Just invoke jcolumn on a class of elements.

```javascript
$('.col').jColumn();
```

##Options
-----

option   | default | Description
-------- | ------- | -----------
delay    | 500     | The delayed time after the resize happens
maxWidth | 767     | Every document width smaller than maxWidth will not use jColumn

```javascript
$('.col').jcolumn({
    delay: 500,
    maxWidth: 767
});
```

##Authors 
-------

Oliver Jessner [@oliverj_net](https://twitter.com/oliverj_net), [Website](http://oliverj.net) 

Copyright © 2015