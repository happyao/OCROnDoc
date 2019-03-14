# CROnDoc
Character Recognition on a Region of a Document.

**Steps**
1.  Detect the 4 borders of a document.
  
2.  Transform the document based on the four borders

3.  Rotate the document in the right orientation

4.  Crop the image by (1/3 of height and 1/2 of width) to get a smaller region around name field area

5.  character recognition by Tesseract
