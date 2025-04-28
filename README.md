# Ex.06 Book Front Cover Page Design
# Date:
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:

'''
book.html

<html>
    <head>
        <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
        <style>
            .bookpage{
                width: 400px;
                height: 600px;
                color:rgb(14, 15, 15);
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow',  Arial, sans-serif;
                background-image: url(bgimage.jpg);
                background-size: cover;
            }

            .insight{
                color: rgb(18, 17, 17);
            }

            .hrstyle{
                width:100px;
            }
            .author{

                display: inline;
                position: relative;
                color: rgb(64, 62, 64);
                top:190px;

                font-family:Georgia;
                font-size: medium;
            }
            .booktitle{
                font-family: 'Courier New', Courier, monospace;
                font-size: larger;
                text-align: center;
                position: relative;
                top: 30px;
            }
            .id{
                width:400px;
                position: relative;
                top:180px;

            }
            .pub{
                font-size: medium;
                position: relative;
                top:155px;
                left:330px;
            }
            .ed{
                color: rgb(126, 197, 19);
                font-size: medium;
                font-family: Verdana;
                position:relative;
                top:85px;
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
                <hr style="color: rgb(115, 0, 255);">
            </div>
            <div class="booktitle">
                <h1>Anna Karenina</h1>
            </div>
            <div class="subtitle">
                The 10th greatest book of all time
            </div>
            <div class="mypic">
                <img src="author.png" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(230, 25, 73);">
            </div>
            <div class="author">
                <p text align="right"><b>Leo Tolstoy </b></p>
                  <b>Extended Edition</b>
                </div>
            </div>
        </b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
              <b>Extended Edition</b>
            </div>
        </div>
    </body>
</html>

'''
# OUTPUT:
![alt text](<cover/bookapp/static/Screenshot 2025-04-28 053437.png>)
![alt text](<cover/bookapp/static/Screenshot 2025-04-28 053455.png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
