# Document Object Model Tree 

The tree-representation of a Document Object Model. This project was created for CS 112 (Data Structure, Spring 2015) at Rutgers University. 

The Document Object Model (DOM) is an interface that represents the HTML layout of a document. It allows other scripts and programs to modify this structure, which can then be pushed back to the webpage.

The following HTML code:

      <html>
      <body>
      <center>The <em>quick</em> brown fox</center>
      </body>
      </html>

would appear as the following in the webpage:

<html>
<body>
<center>The <em>quick</em> brown fox</center>
</body>
</html>




The API is as follows:

            public class Tree {
            public Tree(Scanner sc)                         //Initializes a new scanner with which to build tree in build()
            public void build()                             //Recursively builds tree (also implemented iteratively with stack)
            public void replaceTag(String old, String new)  //Replaces all occurrences of old with new
            public void boldRow (int row)                   //Recursively bold the entire specified row
            public void removeTag(String tag)               //Recursively removes all instances of tag. See assignment for more details
            public void addTag(String word, String tag)     //Recursively Adds tag to all instances of word
            public String getHTML()                         //Return HTML representation of tree
            }
            

The project was completed on March 23rd 2015

