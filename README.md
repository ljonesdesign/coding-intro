# coding-intro
## Very First Steps with Programming

Our first steps with coding were issuing simple commands in our terminal when we logged into the OPAL server, like ```ls```, ```cd```,```mkdir```,```rm```.

## Client Side Scripting Demo
Client side scripting means that code is run on the client`s computer. JavaScript is a client scripting language that runs in a browser (which uses the client's computer memory and processor). 

### Create a minimum HTML document:
Use your editor to create this for you, or you can copy and paste this code:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Write Demo - JS</title>
</head>
    <body>

    </body>
</html>
```

### Set up Script element in the body section

All you have to do to begin coding in JavaScript is to put valid javascipt between open and closing scripts tags:

```
  <body> <!-- Don't copy this again. -->
```     
```
     <script>

     </script>
```
```
   </body>  <!-- Don't copy this again. -->
```
### Add a document.write method 
*Using document.write method is not recommended for actual coding, but for beginners, it is a quick way to show how javascript is similar to other programs that use print(Python), or echo (PHP):*

**JavaScript** (*will run in a browser if user has not disabled JavaScript*)
```
   <script>
      document.write("Hello World!")
   </script>   
```

**PHP** (*will only run in a server environment where PHP module is enabled*)
```
    <?php 
       echo 'Hello World'; 
    ?>
```
**Python** (*does not run in a browser*)
```
Python 3.10.6
Type "help", "copyright", "credits" or "license" for more information.
>>> print("Hello World!")
Hello World!
>>> 
```
Save your file and preview it in a browser and you will see that Hello World is now showing in the browser. Now that you have done a document.write Method, lets move on to a better [Hello World Workflow at Mozilla developer network](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics#a_hello_world!_example)
