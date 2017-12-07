# Step 3

Now add an image

* Add an `img` tag below the `h2`:

```html
<body>
  <h1> My website </h1>
	<h2> About me </h2>
	<img  />

</body>
```
* Point out that unlike most tags, the image tag is **self-closing**. This means that it ends with a forward slash `/` just before the closing angle bracket and it does not need a closing tag.

* Tell students that the img tag needs to know what image to display. We use the `src` attribute for this. Add the following code:

```html
<body>
  <h1> My website </h1>
	<h2> About me </h2>
	<img  src=""/>

</body>
```

* Then find an image that you like on google images.

* Carefully explain that in google images we click on the image itself and then click the `View Image` button. This will open the image in a new tab. From this new tab, we copy the URL and paste it in the quotation marks after `src`.

```html
<body>
  <h1> My website </h1>
	<h2> About me </h2>
	<img src="http://www.craveonline.com/images/stories/2011/2012/May/Comedy/10-skateboarding-dogs-header.jpg" />

</body>
```

* The image should appear on our output page, but it's really big. Show the students that we can resize it using the `width` attribute. Add `width="250"` after the closing quotation mark of the `src` attribute:

```html
<body>
  <h1> My website </h1>
	<h2> About me </h2>
	<img src="http://www.craveonline.com/images/stories/2011/2012/May/Comedy/10-skateboarding-dogs-header.jpg" width="250"/>

</body>
```
