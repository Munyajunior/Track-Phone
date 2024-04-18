<h1>Track PHONE or Any Device and get Location and other details</h1>

<h2>>GOALS</h2>
  The goal of this script is to use a website or link, based on osint info gotten from target and send the link to the target, and when they open the link, we get thier gps location, ip address, uagent etc

<h3>>Steps</h3>

    #Step 1:

            * Create a locate host copy of the website by downloading / saving it as webpage, for this script we'll be using an instagram meme, Copy the embed code of the video.

    #Step 2:

            * Create a file name it as you want in any code editor with the extension .html and past the embed code. save it

    #Step 3:

            * Host the file you just created above, for this example we'll be hosing using [infinityfree.com] because it is free and get the work done. this way any body that loads the link gets directed to a webpage hosting our meme

    #Step 4:

            * Host 2 files, the main html file containning the video, with the js code using the GET method,xhttp, send the location details saved it to the server using a store.php file.
            * Host store.php which create a location.txt file, write the location,uagent, and ip details into it.