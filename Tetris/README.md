

 you are going to write rotate function of a tetris game. You have your bricks in a txt file in a 10x10
dimensioned matrix. You will catch the brick location and rotate it 90ᵒ in clockwise. For simplicity only two kinds of
bricks are going to be rotate by your algorithm. They are "L" character and the inverse of "L". From the input file
you can take 4 different combinations of this two bricks. Your algorithm must rotate the brick in clockwise and
write the result matrix In an output file in the same location of your executable file.


The input file name is “input.txt” and the output file name is “output.txt”. Your program can rotate the brick in the
output file which it produced before, if it is given as an input.

The sample input and output files are in the attachment.

  
    *input.txt*&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*output.txt*<br/>
    0 0 0 0 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>
    0 0 0 1 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>
    0 0 0 1 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>
    0 0 0 1 1 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 1 1 1 0 0 0 0  <br/>
    0 0 0 0 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 1 0 0 0 0 0 0  <br/>
    0 0 0 0 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>
    0 0 0 0 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>
    0 0 0 0 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>
    0 0 0 0 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>
    0 0 0 0 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>



    *input_2.txt*&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*output_2.txt*<br/>
    0 0 0 0 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>
    0 0 0 1 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>
    0 0 0 1 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 1 0 0 0 0 0 0  <br/>
    0 0 1 1 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 1 1 1 0 0 0 0  <br/>
    0 0 0 0 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>
    0 0 0 0 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>
    0 0 0 0 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>
    0 0 0 0 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>
    0 0 0 0 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>
    0 0 0 0 0 0 0 0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 0 0 0 0 0 0 0 0 0  <br/>

