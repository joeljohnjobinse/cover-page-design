# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the GitHub repository, and inside it start a Django project.
### Step 2:
Create the folder 'static' and inside it create the folders 'html' and 'images'.
### Step 3:
Inside 'images', insert the background image and your image in it.
### Step 4:
Write the necessary code to print the book cover in a file called "cover.html".
### Step 5:
Run the webpage and screenshot the output.

## Code:
### cover.html:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
            .bookpage{
                width: 400px;
                height: 600px;
                color: red;
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                background-image: url(/static/images/bg.jpg);
                background-size: cover;
            }

            .insight{
                color: brown;
            }

            .hrstyle{
                width: 100px;
            }

            .author{
                color: white;
                display: inline;
                position: relative;
                color: red;
                top: 190px;
                font-family: Georgia;
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
                width: 400px;
                position: relative;
                top: 180px;
            }

            .pub{
                font-size: medium;
                position: relative;
                top: 155px;
                left: 330px;
            }

            .ed{
                color: blue;
                font-size: medium;
                font-family: Verdana;
                position: relative;
                top: 85px;
            }

            .subtitle{
                font-family: Tahoma;
                font-size: large;
                position: relative;
                top: 40px;
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
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Fundamentals of Web Application Development</h1>
            </div>
            <div class="mypic">
                <img src="/static/images/me.jpeg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
                <p><b>Joel John Jobinse</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
        </div>
    </body>
</html>
```

## Output:
![Cover](/myproj/static/images/cover.JPG)

## Result:
The program is executed successfully.
