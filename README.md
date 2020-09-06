# Duke_HTML

## lesson 1
  Build a Web Page with HTML
  https://codepen.io
  
  WordPress

## lesson 2
  HTML5

  HTML is not a programming language, markup language.
  Specifies contents of web page, used by browsers.
  Specifies meaning or semantics.
    Display different, CSS helps!
    Emphasized.

  1993 create
  2014 current standard

  end with "/"
  <html>
  </html>
  
  In <body>,tag <p> means paragraph, <p> will create some space before/after it automatically.
  
## lesson 3
  Different types of elements
  
  ### Metadata elements
    Information about page (e.g. <html>, <head>, <title>)
  ### Sectioning elements
    Define regions (e.g. <body>, <h1>, <div>)
  
  ### Metadata elements
    <html>
      Contains all other elements
      Specifies using HTML standard
    <head>
      Information about the page: title, scripts, CSS
    <title>
      Specifies page title, which is website's name
      Nested inside <head> </head> tags

  ### Sectioning elements
    <body> 
      Contains all items seen on page
    <h1>
      Section header
      Also <h2>,<h3>,...<h6>, but normally h1 is larger than others
    <div>
      Defines section/division of web page
      Useful for CSS, grouping elements together 
    
 ### lesson_3 website
 <div>
  <h1>Janet's Page of Interests</h1>
  <p>The world wants to know: who is Janet? Read this page to learn about Janet's likes (and maybe her dislikes)!</p>
</div>

<div>
  <h2>What's Your Top 5?</h2>
  <p>Janet was recently asked about her top 5 movies, musicians, and places she has visited. Here are her answers!</p>
  <h3>Movies</h3>
  <h3>Music Artists</h3>
  <h3>Places I've Visited</h3>
</div>
      
 ## lesson 4
 ### Tags surround text or page elements
    <b> bold </b>
    <em> emphasize </em>, means italics
    <b>this</b> <em>is an <b>example of nested</b> tags</em>
    
 <b> bold </b>  
 <em> emphasize </em>  
 <b>this</b> <em>is an <b>example of nested</b> tags</em>

## lesson 5
### Adding Images and Links
    Image tag: e.g.
      <img src="http://xyzw--png" width="75%"/>
      <img src="http://bit.ly/firstimage" />
    Options: extra information
      Some required
    No end tag, src required, width optional
      height=
      CSS later
### Linking Pages Together
    <a href = "https://onesource.com">
    a resource for learning
    </a> HTML.
    
    * anchor tag : <a></a>
    * herf attribute : http ... website address
    * clickable text : a resource for learning
    
## lesson 6

    Some images are copyrighted
      laws
      ok for non-commercial use, like personal use
      usage rights with copyright holder
    Some images in public domain
      wikimedia commons
      creative commons
    Inline or Hot linking
      for personal pages, copyrights usually ok
      websites with lots of traffic? maybe a concern
    Finding Links to Online Photos
      create links to photos found online
        right-click and copy URL, then paste
    Some sites don't allow hot-linking
      e.g. pixabay
      need to test your webpage
        use incognito or private browsing

quiz:
You are creating a website that has multiple images. Instead of saving the images and installing them on their own server you choose to create a link within your page with the URL of the original sever. This process is known as: inline linking.

### resources websites
    https://commons.wikimedia.org/wiki/Main_Page
    https://pixabay.com


## lesson 7
  ### Unordered List 
  
      *
      *
      *
      
      Some lists use circles or bullets
        These are unordered lists, tag: <ul></ul>
        Contents viewed in order, list labels are dufault
        
      <li></li> list item
      
      Inside <ul></ul> must have sequence of <li></li> elements.
      There can be <img>, <a href>, <ul>... between <li></li> elements.
      
 ### Ordered List  
 
     1.
     2.
     3.
     
     These are ordered lists, tag: <ol></ol>
     <li></li> required between <ol> and </ol>
        automatic numebring items
     
     numbers are important,
     also possible: letters
     
### List Elements of
    lists of images
    list of lists (nested), like a loop in a loop

### HTML Tables
    also can add image into table
    
    HTML table elements
      <table></table>
      contains rows <tr></tr>, means table row
      
    Rows contain  
      <th></th> header elements, means table header
      <td></td> table cells, means table data
      
      
## lesson 8
  ### How CSS is used to design web pages
    Cascading Style Sheets
      Specifies look and formatting
      Seperates content from presentation
    Design that Scales
      1000 pages on website
  
  ### Why CSS?
    Reusability
    Maintainability
    CSS resource check website: https://developer.mozilla.org/en-US/docs/Web/CSS/Reference
  
  ### CSS Classes
    if we dont want to set all the website into one style, name them into classes
    Classes: named styles
      HTML
        <li class="foodLi"> Chocolate </li>
        <li class="foodLi"> Cherries </li>
        <li class="foodLi"> Ice Cream </li>
      CSS
        .foodLi {
          color : green;
        }
        
        . Dot: Making a class, naming a class
        foofLI: class name, anything you want
    
  ### CSS IDs
    IDs: Name one element
      HTML
        <img src="cake.jpg" id="cakeImg" />
      CSS
        #cakeImg {
          float:right;
        }
  ### CSS Combinators
    Combinators: select by relationship
      Style <li> inside of <ul>:
        ul li { ... }
      More advanced relationships exist 
      
  ### Classes and IDs: Name and Reuse
    Class and ID: name style
      Re-use as needed, can use in every page of your website
      Mant elements in one page
      Across pages
      Name + use: recurring concept in CS
  
  ### Some resources
    CSS home: https://www.w3schools.com/css/default.asp
    CSS more colors: https://www.w3schools.com/cssref/css_colors.asp
  
