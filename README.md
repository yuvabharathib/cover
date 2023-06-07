# Ex.06 Book Front Cover Page Design
## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```
 
 <!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 500px;
            height: 650px;
            color:rgb(255, 0, 13);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/image/world.png);
            background-size: cover;
        }
            

        .insight{
            color:blue;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:lime;
            top:180px;
            
            font-family:italic;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:150px;
            left:270px;
        }
        .ed{
            color: purple;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:55px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(255, 0, 13);">
            </div>
            <div class="booktitle">
                <h1>The Web Developer's Handbook: Essential Skills for the Digital Age</h1></div>
            <div class="subtitle">
                with HTML,CSS,Java Script,Go,Ruby Insights
            </div>
            <div class="mypic">
                <img src="/static/image/photo.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color:crimson;">
            </div>
            <div class="author">
               <p><b>SUBALAKSHMI S</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Limited Edition</b>
            </div>
        </div>
    </body>
</html>
```

## OUTPUT:
![Screenshot (17)](https://github.com/yuvabharathib/cover/assets/113497404/4a367662-da50-42a8-b401-73d619bba1c1)


## HTML VALIDATOR:
![Screenshot (16)](https://github.com/yuvabharathib/cover/assets/113497404/5bc17758-c49a-46f9-aa34-74ec1b8e1abc)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
