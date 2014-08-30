custom-card
===========
Simple and responsive web component for create cards, like profile cards,  but also create, for instance, project cards, github profile cards, social cards

###Example
![image](http://snag.gy/ZVfoK.jpg)

###Install
 Using [Bower](http://bower.io):
 
 1.Install platform.js:
  
 ```sh
 $bower install polymer-platform
 ```
 
2.Install custom card:
 
```sh
$bower install custom-card
```

3.Place the following in the head:

```html
<script type="text/javascript" src="bower_components/polymer-platform/platform.js"></script>
<link rel="import" href="bower_components/custom-card/custom-card.html"/>
```
##Using
```html
<custom-card></custom-card>
```
####Options

Attribute  |type     						|	 
---		   |---      						|
title	   |text    			    		|	
icon       |URI      						|
h          |number					        |
attributes |text - comma separated values	|
back	   |text							|


###Browser suport
![IE](https://cloud.githubusercontent.com/assets/398893/3528325/20373e76-078e-11e4-8e3a-1cb86cf506f0.png) | ![Chrome](https://cloud.githubusercontent.com/assets/398893/3528328/23bc7bc4-078e-11e4-8752-ba2809bf5cce.png) | ![Firefox](https://cloud.githubusercontent.com/assets/398893/3528329/26283ab0-078e-11e4-84d4-db2cf1009953.png) | ![Opera](https://cloud.githubusercontent.com/assets/398893/3528330/27ec9fa8-078e-11e4-95cb-709fd11dac16.png) | ![Safari](https://cloud.githubusercontent.com/assets/398893/3528331/29df8618-078e-11e4-8e3e-ed8ac738693f.png)
--- | --- | --- | --- | --- |
Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ |
