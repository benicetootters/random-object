# random-object
Some JavaScript interacting with Gallery System's EmbARK Kiosk to randomly select images to display from a collection

Requires two files to be placed in the appropriate locations in the Kiosk folder structure:

* Templates/API/brief.html
* Database/Webfolder/random.html

In both files there is a snippet like [your kiosk base URL] which you should change to your unique kiosk URL (e.g., https://collection.mymuseum.org/). 

brief.html (line 7 before &lt;!--#4DTEXT ImagePath("Surrogates")--&gt;" )

random.html (line 4 after url=)



