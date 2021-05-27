# im2col3
A 3D analog of MatLab's im2col( I, blocksize ) with a specified step. For example, stepsize = [ 1 1 1 ] corresponds to im2col( I, blocksize, 'sliding' ), 
while stepsize = blocksize corresponds to im2col( I, blocksize, 'distinct' ).

This MatLab function extracts 3D blocks of size blocksize (3-value vector) at steps stepsize (3-value vector) from a 3D image and returns the 
blocks pixels as column vectors in the ouput 2D matrix.
