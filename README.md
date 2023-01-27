Ex-06-Book-Cover-Design
## AIM:
To develop a website to display the cover page design of a book

Design Steps:
## Step 1:
Clone the Github repository and create a Django admin interface.

## step 2:
Write HTML and CSS code for designing book cover page and execute them.

## code:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url("/static/images/back.jpeg");
            background-size: cover;
        }
            

        .toptext{
            color:black;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: rgb(8, 8, 8);
            display: inline;
            position: relative;
            color:rgb(8, 8, 8);
            top:180px;
            
            font-family:Cosmic;
            font-size: medium;
        }
        .booktitle{
            font-family: 'sans-serif';
            font-size: larger;
            text-align: center;
            position: relative;
            top: 20px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:145px;
            left:330px;
        }
        .edition{
            color:rgb(255, 208, 0);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Segoe UI;
            font-size: large;
            position: relative;
            top:40px;
        }
        .photo{
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
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>RESPONSIVE WEB DESIGN USING HTML5 AND CSS</h1></div>
            <div class="subtitle">
                Develop future-proof responsive websites using the latest HTML5 and CSS Techniques
            </div>
            <div class="photo">
                <img src="/static/images/photo.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: yellow;">
            </div>
            <div class="author">
               <p><b>R.UDAYAKUMAR</b></p>
            </div>
            <div class="publisher">
                RELX
            </div>
            <div class="edition">
                <b>Seventh Edition</b>
            </div>
            
        </div>
    </body>
</html>
```
## Output:
![](output.png)

## HTML Validator:
![OUTPUT](Valid.png)

## Result:
The program for designing book cover page using HTML and CSS is executed successfully.