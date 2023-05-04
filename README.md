Download Link: https://assignmentchef.com/product/solved-cs526-homework-assignment-5
<br>
This assignment is an extension of Homework 3. In Homework 3, you implemented a generic binary search tree <em>MyBST</em> and implemented an <em>add</em> method in it.




For this assignment, you are required to implement the following methods.




Algorithm successor(p)

Input parameter:

p: The position of the node whose successor is searched

Output:

Returns the position of the successor of p

If there is no successor of p in the tree, returns null.




<strong>Note: Let <em>e</em> be the element of <em>p</em>. The <em>successor</em> of <em>p</em> is the node which has the smallest element that is larger than <em>e</em>. In other words, if we list all nodes in the tree in increasing order of elements, the <em>p</em>’s successor is located immediately after <em>p</em>.</strong>




Algorithm predecessor(p)

Input parameter:

p: The position of the node whose predecessor is searched

Output:

Returns the position of the predecessor of p

If there is no predecessor of p in the tree, returns null.




<strong>Note: Let <em>e</em> be the element of <em>p</em>. The predecessor of <em>p</em> is the node which has the largest element that is smaller than <em>e</em>. In other words, if we list all nodes in the tree in increasing order of elements, the <em>p</em>’s predecessor is located immediately before <em>p</em>. </strong>




Algorithm delete(p, e)

Input parameters:

p: The position of the root of the tree (or subtree) from which

the node with the element e is to be deleted

e: The element of the node to be deleted

Output:

Returns e if a node with e exists.

If there is no node with e in the tree, returns null.




<strong>Note: You must implement the delete method that is described in pages 464-465 of the textbook. Otherwise, you will lose points even if your implementation deletes a given node correctly. </strong>




<h1>Documentation</h1>




No separate documentation is needed. However, you must include sufficient inline comments within your program.




<h1>Grading</h1>




The successor method will be tested three times and 3 points will be deducted for each wrong result.




The predecessor method will be tested three times and 3 points will be deducted for each wrong result.




The delete method will be tested three times and 5 points will be deducted for each wrong result.




Points will be deducted up to 20 points if you do not include sufficient inline comments.




<h1>Deliverables</h1>




You need to submit a revised the <em>MyBST.java</em> file. Combine this file with all other files, which are necessary to compile and execute your program, into a single archive file, such as a <em>zip</em> file or a <em>rar</em> file, and name it <em>LastName_FirstName_hw5.EXT</em>, where <em>EXT</em> is an appropriate file extension (such as <em>zip</em> or <em>rar</em>). Upload it to Blackboard.