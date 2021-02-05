# Document-Scanner
Building a document scanner using Python, OpenCV and Computer Vision<br>
Steps involved - 
<ol>
  <li>Detect Edges</li>
  <li>Use the edges in the image to find contour(outline) representing the piece of paper being scanned</li>
  <li>Apply perspective transform to obtain the top-down view of the document</li>
</ol>
<br>
To run the script - <br>
$ python scan.py --image Images/receipt.jpeg
<br>
An example of a test image post scanning has been added to the Images folder.
