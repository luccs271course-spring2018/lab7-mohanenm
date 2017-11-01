<h1>  What is the purpose of the various auxiliary methods populateList, populateFifoList, and ReverseLines.printReverse? </h1>
Allows the program to be recursive, called within the method while also being the method(so the compiler can recongnize it in other .java files).
populate list: retrieves object from node and add to the top of the list
populateFifoList: retrieves object and adds it to index 0.
ReverseLines.printReverse: takes line from input, and echos it in the terminal based of fifo principals. 
<h1>  Why do these methods need to have arguments, and how does the argument change from one recursive call to the next? </h1>
So we have references to the ones we need to update, one is added to it everytime, so it will access the next index(0,1,2,3). 
Without references, they would not be able to recursive such that we would not be able to call them. 
<h1>   What are the time and space complexity of each of the populateList populateFifoList methods, as well as ReverseLines.printReverse?</h1>
All are 0(n). 
<h1>   Which of these methods can be implemented using while loops?</h1>
All recursion statments can be implemented using a while loop. 