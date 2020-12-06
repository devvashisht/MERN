# MERN
## complete 2020 web development course: 

**CSS display property:**
 - DISPLAY:  BLOCK, INLINE, INLINE-BLOCK, NONE
  - BLOCK: P, h, div,
        <p>hello</p>
        <p>world</p>
  
  <span>Pro</span>: span is inline display element: only occupy require width and height (same for image and a tags)

: you can not change the width or height of span element
We can change width of BLOCK element but still occupy whole width
INLINE-BLOCK:  can provide width and on same line.

**CSS Positioning:**
- *STATIC*: All element are static by default
- *Relative*: Relative to normal position (i.e how element is displayed static position)
	It does not affect anything on the screen
- *Absolute*:  Relative to its parent element
	 It affects another element on the screen
- *Fixed*:  stay on the same position on scrolling.

*Margin*:  Auto for centring the element when width or height is given
FONT SIZE : 
Font-size : 90px (px: is not a dynamic size; stay static
16px =  100%  :  dynamic font
Em : size of M  :  1em = 16px = 100%
% and em are inherited for example  : 2em in body and h1 we specify 5 then final font size in h1 will be 7
Em vs Rem  : Root em : ignore root font size


**UI design Concept  :**
 - Layout  (Typography)
 - Line size ( per line character)
 - uniform alignment of line(reduce no alignment points)
 - color contrast (color palatte)
 - size of elements and text ( keep size and color as per foucs)
 - white space ()
 - target audience

 **UX design**
 - simplicity
 - consistency
 - Reading patterns ( F pattern )
 - all platform design
 - so many banners 
 
 **WEB DEESIGN**
  -  canva.com  : Design principles : design and publish your webpage


  **Document object model**
    - document.querySelector("h1").innerHTML = "Good Day";
    - document.querySelector("h1").style.color = "red";
    - document.querySelector("input").click();
    -   **properties** : innerHTML, style, firstChild ; **METHOD** :  click(), appendChild(), setAttribute()
    - **document/getElmentsByTagName("li)**  :  Array of element 
    - **document/getElmentsByClassName("className)**  :  Array of element 
    - **document/getElmentsByID("ID")**  :  Array of element 
    - **document.querySelector("h1")**  :  first occuring element 
    - **document.querySelectorAll("h1")**  :  Array of element 


    ##  Accessing style via JavaScript ##
    - document.querySelector("h1").style.color = "Red"
    - **CamelCase in case of javascript access the style**

    ## Class Add/Remove/Toggle  via javascript ##
    - document.querySelector("h1").classList  ,document.querySelector("h1").classList.add("className") : remove/toggle

 -  **innerHTML** manipulates the HTML content as well along with text content whereas **textContent** only deals with Text

 ## Get attribute for a element ##
- document.querySelector("a").attributes : List of currently associated attibute e'g href
- document.querySelector("a").getAttribute("attributeName(e.g href)") : current value of attribute
- document.querySelector("a").setAttribute("attributeName(e.g href)","finalValue") : current value of attribute
- 



  

