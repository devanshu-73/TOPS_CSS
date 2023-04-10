# CSS Types :
    - We can add CSS in three approaches: Inline, Internal, and External.

##  (1)  CSS INLINE

    - Inline CSS is the technique to define the single element with 
    the insert style sheets in an HTML document. 

### Example :
    <h1 style="color:yellow;text-align:center;">I Am Inline Css....</h1>
   
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>INLINE CSS</title>
</head>
<body>
<h1 style="color:yellow;text-align:center;">I Am Inline Css....</h1>
</body>
</html>

##  (2)  CSS INTERNAL

    - Internal CSS is used to define a style for a single HTML page.
    - Internal CSS is defined in the <head> portion of HTML page, within a <style> portion.

### Example :
    <head>
      <style>
        p{
          font-size:30px;
          color:red;
          text-align:center;
         }
      </style>
    </head>
    <body>
    <p>I Am Internal Css....</p>
    </body>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>INTERNAL CSS</title>
<style>
p{
font-size:30px;
color:red;
text-align:center;
}
</style>
</head>
<body>
   <p>I Am Internal Css....</p>
</body>
</html>

##  (3)  CSS EXTERNAL
    - To use an external style sheet, add a link to it in the <head> section of each HTML page.

### Example :
    <!DOCTYPE html>
    <html lang="en">
    <head>
    <title>INTERNAL CSS</title>
    <link rel="stylesheet" href="style.css">
    </head>
    <body>
    <h3>I Am External Css....</h3>
    </body>
    </html>
    
<!DOCTYPE html>
<html lang="en">
<head>
<title>EXTERNAL CSS</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<h3>   I Am External Css....   </h3>
</body>
</html>
      


# CSS class:

    - The class selector selects HTML elements with a specific class attribute.
    - To select elements with a specific class, write dot (.), followed by the class name.

### Example :
    .one {
    text-align: center;
    color: blue;
    }

# CSS id:

    - The id uses the id attribute of an HTML element to select a specific element.
    - The id of an element is unique.
    - write a hash (#),followed by the id name.

### Example :
    #one {
    text-align: center;
    color: red;
    }


# BOX MODEL :

    - Content - The content of the box, where text and images appear.
    - Padding - padding is space around a content.
    - Border - A border that goes around the padding and content
    - Margin -space around area outside the border.

<img src="/img/boxmodel.png" style="width:600px;height:300px;" alt="boxmodel">