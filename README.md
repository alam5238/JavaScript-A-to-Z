# JavaScript-A-to-Z
Full guide and lesson about JavaScript include in this repository 

![Screenshort](images/javascript.png "javascript")

## JavaScript
- JavaScript is used in millions of Web pages to improve the design, validate forms, detect browsers, create cookies, and much more.
- JavaScript is the most popular scripting language on the internet, and works in all major browsers, such as Internet Explorer, Mozilla, Firefox, Netscape, Opera.

###### WHAT IS JAVASCRIPT?
- JavaScript was designed to add interactivity to HTML pages 
- JavaScript is a scripting language (a scripting language is a lightweight programming language) 
- A JavaScript consists of lines of executable computer code 
- A JavaScript is usually embedded directly into HTML pages 
- JavaScript is an interpreted language (means that scripts execute without preliminary compilation) 
- Everyone can use JavaScript without purchasing a license

###### Why Study JavaScript?

- JavaScript is one of the 3 languages all web developers must learn:
  - HTML to define the content of web pages
  - CSS to specify the layout of web pages.
  - JavaScript to program the behavior of web pages.
  
###### Are Java and JavaScript the Same? 
- NO!
- Java and JavaScript are two completely different languages in both concept and design!
- Java (developed by Sun Microsystems) is a powerful and much more complex programming language - in the same category as C and C++.

###### JavaScript vs. PHP

![Screenshort](images/PHP-vs-JavaScript.png "PHP-vs-JavaScript")

- Similarities:
  - both are interpreted, not compiled
  - both are relaxed about syntax, rules, and types
  - both are case-sensitive
  - both have built-in regular expressions for powerful text processing
- Differences:
  - JS is more object-oriented
  - JS focuses on user interfaces and interacting with a document; PHP is geared toward HTML output and file/form processing
  - JS code runs on the client's browser; PHP code runs on the web server
  
###### JavaScript Capabilities
- Improve the user interface of a website
- Make your site easier to navigate
- Easily create pop-up alert, windows
- Replace images on a page without reload the page
- Form validation
- Many others …

## How to Put a JavaScript Into an HTML Page?
Use <script></script> html tag and script type are text/javascript for putting or including a JavaScript into HTML pages.

###### Examples:
```
<script type="text/javascript">
document.write("Hello World!")
</script>
```

###### Here are the full code:
```
<html>
<body>
<script type="text/javascript">
document.write("Hello World!")
</script>
</body>
</html> 
```

## Embedding JavaScript into HTML page?
Use **src** html tag attribute for putting or including a JavaScript into HTML pages.

###### Examples:
```
<script language=“JavaScript” src=“your_source_file.js”></script>
```

###### Here are the full code:
```
<html>
<head>
<title>First JavaScript Program</title>
</head>
<body>
<script language=“JavaScript” src=“your_source_file.js”></script>
</body>
</html>
 
```

## JavaScript Commenting:

- Used this `<!–` for begin hiding JavaScript and by End hiding JavaScript use `-->`
- For single-line comment use `//` 
- For multiple-line comment use `/* … */`

###### Examples:
```
<script language=“JavaScript”>
<!– begin hiding JavaScript
// single-line comment, /* … */ multiple-line comment
End hiding JavaScript -->
</script>
```

## Hide JavaScript from incompatible browsers?
Use `<noscript></noscript>` tag for hide JavaScript from incompatible browsers.

###### Examples:
```
<noscript>
Your browser does not support JavaScript.
</noscript>
```







