# Ex-06-Book-Cover-Design

## AIM:
To design a book-cover-design using HTML and CSS.

## DESIGN PROCEDURE:
## STEP 1:
Start define the document type as HTML.

## STEP 2:
Open the HTML structure with necessary head and body sections.In the head section ,set the title as Book Coverpage and define the styles for the bookcover.Use the CSS styles in the code.The styles include:

background-color,

background-image,

background-position,

background-repeat,

padding,

font-size,

font-family,

background-size,

color,

line-height.

## STEP 3:
In the body section ,create a division with the text with respective to the headings:

"EXPERT INSIGHT"

"Responsive Web Design with HTML5 and CSS"

" Develop future-proof responsive website using the latest HTML5 and CSS techniques "

"FIRST EDITION"

"Tella Thrishendra"

"SEC>"

## STEP 4:
Close the HTML structure.

## CODE:
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
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(https://img.freepik.com/free-vector/gradient-network-connection-background_23-2148871843.jpg);
            background-size :cover;
        }
            

        .toptext{
            color:white;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            color:white;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: "Sans-Serif";
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
            color:
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            color:white;
            top:155px;
            left:330px;
        }
        .edition{
            color:cyan;
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
                <h1>"Responsive Web Design with HTML5 and CSS"
                </h1>
            </div>
            <div class="subtitle">
                Develop future-proof responsive website using the latest HTML5 and CSS techniques 
            </div>
            <div class="photo">
                <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\181CF41CE37CF9128E1D95896661C5C9\WhatsApp Image 2023-12-15 at 10.57.06_06c6f05f.jpg" width="130" height="145"alt="">
            </div>
            <div class="id">
                <hr style="color:red;">
            </div>
            <div class="author">
               <p><b>Tella Thrishendra</b></p>
            </div>
            <div class="publisher">
                SEC>
            </div>
            <div class="edition">
                <b>FIRST EDITION</b>
            </div>
            
        </div>
    </body>
</html>
```
## OUTPUT:
![Screenshot 2023-12-15 110655](https://github.com/Thrishendra/Ex-06-Book-Cover-Design/assets/145742464/1802a143-b558-41aa-a475-e7cbd18a4a68)

## RESULT:
Thus the book-cover-design has been successfully created using HTML and CSS.

## DEVELOPED BY: T.Thrishendra
## REGISTER NO: 212223230227
## DEPT: B.Tech(AI&DS)
