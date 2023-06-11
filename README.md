## EXPERIMENT 09: CREATE A BIRTHDAY CARD USING HTML AND CSS.
## AIM:
To create a birthday card using html and css.

## ALGORITHM:
1. Create an HTML document with a head and body section.
2. In the head section, set the meta tags for character encoding, compatibility, and viewport.
3. Add a title for the document.
4. Define CSS styles to set the body background image and container background image, as well as positioning and styling for the text and image elements.
5. In the body section, create a container div with nested elements to display the birthday invitation content, including headings, text, and an image.

## PROGRAM:
### CARD.HTML
```
<!DOCTYPE html>
<html>
    <head>
        <style>
            .card-image
             {
                background-image: url("bcard.jpg");
                height:750px;
                background-position: center;
                background-repeat: no-repeat;
                background-size: cover;
                position: relative;
             }

            .card-text
             {
                 text-align: center;
                 position: absolute;
                 top: 50%;
                 left: 50%;
                 transform: translate(-50%, -50%);
                 color: #000000;
            }
        </style>
    </head>
    <body>
    <div class="card-image">
    <div class="card-text">
        <h1 style="font-size:70px"><i>HAPPY BIRTHDAY </i></h1>
        <h2>
            You are a wonderful person.
            <br/>
            Wishing you a joyful birthday with full of blessing!!
            <br/>
            I hope your day is filled with lots of love and laughter.
        </h2>
        <h1 style="font-size:40px">Have a great birthday &#10084</h1>
    </div>
    </div>
    </body>
</html> 
```
## OUTPUT:
![image](https://github.com/Evangelin-Ruth/modernweb-ex9/assets/94219798/a04d0308-fef3-4c33-8b69-a908aec8509a)
## RESULT:
Thus, a birthday card is created using html and css.

