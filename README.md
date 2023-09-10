# data-structure-lab
Given an image as a 2-D character array or a string [], scale it up by factor. That is, if the original image is M x N, the scaled image should be (Mfactor) x (Nfactor). Each character in the input should be represented by factor x factor of the same character in the output.

EXPLANATION
In this problem , for any image of M x N, the scaled image
should be (Mfactor) x (Nfactor). Each character in the input
should be represented by factor x factor of the same character in
the output
Imagine a matrix . In that M represents the number of rows and N represents the
number of columns of 2D array.
In for loop each elements of 2D array is collected.
Finally we input the number of times the elements in 2D array to repeat itself in
self as well as whole row too.
1.The output should repeat the same element with the given number.
Same element repeat itself in q loop and j loop helps to move to next element.
2.The p for loop helps in doing the same activity in another iteration.
Finally i for loop is incremented thereby moves to new row and repeats step 1
and 2.
Thus we get the enlarged image.
