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
```
<html>
<head>
</head>
<body>
<p style="font-size:30px"><b>Agricultural Search</b></p>
<a href="https://milnepublishing.geneseo.edu/botany/chapter/rice/">
<img style="border:5px solid black;"src="/home/sec/Pictures/rice.jpeg"width=300" height="400"><br>
<br>
<a href="https://en.wikipedia.org/wiki/Wheat">
<img style="border:5px solid black;"src="/home/sec/Pictures/wheat.jpeg"width=300" height="400"><br>
<br>
<a href=https://www.zzhuayo.com/product/mini-plough/">
<img style="border:5px solid black;"src="/home/sec/Pictures/simple-plough.jpg"width=300" height="400"><br>
<br>
<a href=https://en.wikipedia.org/wiki/Fertilizer'>
<img style="border:5px solid black;"src="/home/sec/Pictures/fertilizer.jpeg"width=300" height="400"><br>
</a>
</body>
</html>
```

## OUTPUT
![1](https://github.com/Krithikadini/Ex04_Web-Design/assets/127816336/1adda9d3-0786-4c0a-929f-9bcf7bf3bb40)


## RESULT
 Images as hyperlinks is implemented successfully.
