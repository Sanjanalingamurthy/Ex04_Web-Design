# Ex.04 Images as Hyperlinks
## AIM
  Insert five different images ( 2 on Crops and 2 on Machines and 1 on Fertilizer required ). 
  Skip two lines between each image. Each image should have a title. 
  Display the images with a border of size 2, a width of 200, and a height of 200, 
  it should be linked to a search engine of your choice and when each image is clicked, 
  the respective search engine should be opened in a new window.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the required images using ```<img>``` tag.

### STEP-3
  Set the image border size as 2, image width as 200 and height as 200.

### STEP-4
  Use the ```<a>``` anchor tag to link the corresponding search engines.  

### STEP-5
  Give double line spacing between the images using ```<br>``` tags.
  
### STEP-6
  Open the file in a browser and verify the output.
  
## CODE
~~~
<html>
<head>
<title>AGRICULTURE</title>
</head>
<body>
<h1>PLOUGHER</h1>
<a href="https://www.thefreedictionary.com/plougher#:~:text=n.,means%20of%20a%20strong%20blade.">
<img src="plougher.jpg"
wdth="200" heght="2000"></a>
<br>
<br>
<h1>WEEDER</h1>
<a href="https://en.wikipedia.org/wiki/Weeder">
<img src="weeder.jpg" width="200" height="200"></a>
<br>
<br>
<h1>FLORICULTURE</h1>
<a href="https://vikaspedia.in/agriculture/farm-based-enterprises/floriculture#:~:text=Floriculture%20or%20flower%20farming%20is,and%20in%20the%20pharmaceutical%20sector.">
<img src="floriculture.jpg" width="200" height="200"></a>
<br>
<br>
<h1>HARVESTER</h1>
<a href="https://www.fieldking.com/product-portfolio/combine-harvester/">
<img src="harvester.jpg" width="200" height="200"></a>
<br>
<br>
<h1>ARBORICULTURE</h1>
<a href="https://www.sciencedirect.com/topics/earth-and-planetary-sciences/arboriculture#:~:text=Arboriculture%20is%20the%20art%20of,trees)%20in%20a%20certain%20setting.">
<img src="arboriculture.jpeg"  width="200" height="200"></a>
</body>
</html>
~~~


## OUTPUT
![out1](https://user-images.githubusercontent.com/127816526/235470030-b1f7f6f7-2320-4ae7-9cad-3541a68f0b5b.JPG)
![out2](https://user-images.githubusercontent.com/127816526/235470095-f2d3019d-d021-41af-be87-b79166fca93d.JPG)
![out3](https://user-images.githubusercontent.com/127816526/235470152-0c02b69f-d425-4e73-8e82-06975a3eac8f.JPG)



## RESULT
 Images as hyperlinks is implemented successfully.
