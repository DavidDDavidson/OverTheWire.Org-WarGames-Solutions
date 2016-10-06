#Natas2
=======

Observing the raw html we see:

```HTML
    <body>
        <h1>natas2</h1>
        <div id="content">
	    "There is nothing on this page"
            <img src="files/pixel.png">

    ...
```

We see that there is a image file embedded in the HTML. Upon further inspection, you'll find that the file ``pixel.png`` is located in the directory ``files``. You can utilize this information and attempt to traverse the directory from within the browser. This is called a ``directory traversal attack``. 

Navigating to the page ``http://natas2.natas.labs.overthewire.org/files/`` reveals a file called ``users.txt``. You'll find the password for the next level contained within that file.

