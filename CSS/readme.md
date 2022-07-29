# css
stands for cascading Style Sheet it is a language  that describes the style of an HTML element. It describes how HTML elements should be displayed. Css used to give the style to html elements.
## features
* css describes how HTML elements are to be displayed on screen, paper or in other media.
* CSS save a lot of work. it can control the layout of multiple webpages all at once.
* external style sheet are stored in CSS files.
## selectors in CSS
* Element Selectors

        p{
            color: yellow;
        }
* Id selectors

        #pawan{
            color:blue;
        }
* Class selectors

        .pawan{
            color:pink;
        }
* Grouping Selection

        h1,p,h2{
            color: yellow;
        }

## Type of css

### Inline CSS 
For single element 

        <p><span style="color:Blue;"> kamal verma </span></p>

## Internal CSS  
For one single page and defined in the head element

        <html>
            <head>
                <style>
                    body{
                        color:aqua;
                        background-color: yellow;
                    }
                </style>
            </head>
        </html>

## External CSS
can change entire website by just change in one file i.e **style sheet**
extention is ".CSS"

## border in css
you can add width height color also
like in stylesheet

        height: ; width: ; border: type color pixcle;

* double
* solid
* dashed
* dotted
* inset
* outset
* groove
* ridge
* none
* hidden

border can be styled as
-        border-style: type;
-
        border-width: value;
-
        border-color: name;
-
        border-top-style: type;
        border-right-style: type;
        border-bottom-style: type;
        border-left-style: type;
-
        border-style: top-type, right-type, bottom-type,left-type;
        border-style: top, bottom, right&left;
        border-style: top&bottom, right&left;
        border-style: allside;
- for rounded borders

        border-radius: value;

## colorscheme
* **color _value/ name_**

        color: red;
* RGB

        color: rbg(255,255,255);
* RGBA

        color: rgba(255,255,255,0-1)
* HEXA
( _hexdecimal means 0-9,a-f = 15 value in #RRGGBB format_ )

        color: #ff0000;

* HSL (Hue(0-360),Saturation(0-100%), Lightness(0-200%))

        color: hsl(50,80%,100%);
* HSLA (adding alfa(0-1) too)

        color: hsla(50,60%,100%, 0.5)

## CSS BACKGROUND
-
        background-color: red;
-
        background-image: url("href");
-
        background-repeat: repeat x/y or no-repeat;
-
        background-postion: right top;
-
        background-attachment: fixed/scroll;

* short-hand technique for background

        background: yellow url("href") no-repeat fixed right-top;

## PADDING & MARGIN & LINK
-
        padding: topvalue, rightvalue,bottomvalue,leftvalue;
-
        margin-top:15%;
        margin-bottom: value;
- link are of four type ( link, hover, visited, active )

        a:link{color:red;}
        a:hover{color: blue;}
        a:visited{color: pink;}
        a:active{color: purple;}
