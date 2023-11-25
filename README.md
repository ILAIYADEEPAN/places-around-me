# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:

Make an html file for execute the places around me on the map

### Step 2:

Now make your own place and the direct it to the another html by when we touch the place on the map by using before we create the html file.

## step 3:

Add pictures in another html where we want to see the place.

## Code:
<!DOCTYPE html>
<html>
<head>
    <title>
        imagemaps demo
    </title>
</head>
<body>
    <h1> imagemaps demo </h1>
    <img src="kilpalur.jpg" usemap="#image_map">
<map name="image_map">
  <area alt="kilpalur" title="myvillage" href="village.html" coords="608,303,51" shape="circle">
  <area alt="ricemill" title="kmd ricemill" href="mill.html" coords="975,297,1072,370" shape="rect">
  <area alt="Temple" title="muthumariyamman " href="temple.html" coords="592,789,59" shape="circle">
  <area alt="agency" title="Dhanalakshmi agency" href="agency.html" coords="315,530,383,609" shape="rect">
  <area alt="lake" title="KILPALUR LAKE" href="lake.html" coords="191,476,63" shape="circle">
</map>

</body>
</html>

## Output:
![output](/output1.jpg)
![output](/output2.jpg)
![output](/output3.jpg)
![output](/output4.jpg)

## Result:
The program for places-around-me is successfully executed.