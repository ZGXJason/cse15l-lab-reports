# lab report 5
## part 1 
The student psot:<br>
I am testing my ListExamples.java merge method on ListExamplesTests.java. However, one failure message appeared on the terminal regarding a Timeout Exception. I guess this might be caused by some of the local variable haven't be updated. Here's a screenshot of the output and corresponding code.
![Image1](labreport5.1.png) <br>
The TA response:<br>
Jason Zhang: try to replace the `index1` into `index2` in the last `while - loop`. <br>
<br>
After changing the code and the description of the bug: <br>
The third while loop in the original code tries to add the remaining elements from `list2` to the result arraylist. However, this while loop checks to see if `index2` is smaller than the arraylist's size. The original code includes a line `index+=1`;, which increments `index1` each time the condition is met. As a result, the while loop runs indefinitely because `index2` never changes. Instead of incrementing `index1`, `index2` should be incremented by `index2+=1`; this ensures that the code behaves correctly.
