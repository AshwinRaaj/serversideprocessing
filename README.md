# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

### Step 1:

Desing your website for calculation using wireframe work.

### Step 2:

Then to execute the wireframe work desing use html,css

### Step 3:

Use views.py to execute the coding in serverside.

### Step 4:

Mention the path of the website in urls.py.

### Step 5:

Publish the website in the given URL.http://ashwinash.student.saveetha.in/

## PROGRAM :
### Area.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Area of Rectangle</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <link rel='stylesheet' type='text/css' media='screen' href='main.css'>
    <script src='main.js'></script>
</head>
<style>
    *{
        box-sizing: border-box;
        font-family:Arial, Helvetica, sans-serif ;
    }
    body{
        background-color:rgb(231, 114, 46);
    }
    .container{
    width: 1080px;
    height: 500px;
    margin-top: 100px;
    margin-left: auto;
    margin-right: auto;
    border-radius: 10px;
    border: 10px solid rgb(0, 0, 0);
    background-color:rgb(226, 0, 0);
    }
    h1{
        text-align: center;
        padding-top: 20px;
    }
    .calculate{
        padding-top: 10px;
        padding-bottom: 10px;
        padding-left: 10px;
        padding-right:10px;
        text-align: center;
        font-size: 20px;
    }
    .footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: rgba(15, 15, 15, 0.938);
  text-align: center;
  padding-top: 10px;
  padding-right: 5px;
  margin-right: 15px;
  margin-bottom: 20px;
  color: white;
  margin-top: 150px;
}
</style>
<body>
    <div class="container">
<h1>Area Of Rectangle</h1>   
<form method ="POST">
    {% csrf_token %}
    <div class="calculate"> 
Length=<input type="text" name="length" value="{{l}}"></input></br>
    </div>
    <div class="calculate"> 
Breadth=<input type="text" name="breadth" value="{{b}}"></input></br>
    </div>
    <div class="calculate"> 
<input type="submit" value="calculationarea"></input></br>
    </div>
    <div class="calculate"> 
area=<input type="text" name="area" value="{{area}}"></input></br>
    </div>
    <br>
    <div class="footer">
        Developed by Ashwin Raaj.S.
    </div>
</form>
</body>
</html>
```
## OUTPUT:

### Home Page:
![Without Output](Withoutoutput.png)

### Calculation Output:
![Without Output](Withoutput.png)

## Result:
A website to perform mathematical calculations in server side is created.
