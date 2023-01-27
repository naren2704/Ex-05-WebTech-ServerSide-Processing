# Design a Website for Server Side Processing

# AIM:

To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:
## Step 1:
clone the repository from Github

## Step 2:
create Django Admin project

## Step 3:
create a new app

## Step 4:
create python programs for views and urls

## Step 5:
create a HTML file of forms

## PROGRAM:


 <!DOCTYPE html>
 <html lang="en">
    <head>
        <style type="text/css">
        *{
            border-radius:5px;
        }
        body{
            background-color: black;
        }
        .color1{
            background-color:grey;
        }
        .color2{
            background-color: grey;
        }
        .color3{
            background-color: #FF0037;
        }
        #calculation{
            width:750px;
            height:300px;
            margin-left: auto;
            margin-right: auto;
            margin-top: 100px;
            margin-bottom: auto;
            border-width: 5px;
            border-color: #fff;
            border-style: groove;
        }
        .block{
            text-align:center;
            width:375px;
            height:40px;
            border-radius:0px;
            margin-top: auto;
            margin-bottom: auto;
            margin-left: auto;
            margin-right: auto;
            background-color: grey;
        }
        </style>
    </head>
    <body>
        <div id="calculation" class="color2" align="center">
        <h1>Volume of Cuboid</h1>
        <form method="POST" action="/volume/">
            {%csrf_token%}
            <div class="block">
            <label for="length">Length</label>
            <input type="text" name="length" id="length" value="{{ length }}"/>
            </div>
            <div class="block">
            <label for="breadth">Breadth</label>
            <input type="text" name="breadth" id="breadth" value="{{ breadth }}"/>
            </div>
            <div class="block">
            <label for="height">Height</label>
            <input type="text" name="height" id="height" value="{{ height }}"/>
            </div>
            <div class="block">
            <input type="submit" value="Calculate volume"/>
           </div>
           <div class="block">
            <label for="volume">Volume</label>
            <input type="text" name="volume" id="volume" value="{{ volume }}"/>
            </div>
        </form>
        </div>
    </body>
</html>


 

  
## HOME PAGE:
![image](https://user-images.githubusercontent.com/118706984/215162391-1dc510da-f6d4-43d0-b4f7-af599fef382c.png)

## OUTPUT:

![image](https://user-images.githubusercontent.com/118706984/215162471-033d86ea-785a-4fb9-b663-ba764b292e46.png)




# RESULT:

The program is executed succesfully
