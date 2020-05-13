# dirtyCow
Dirtycow also known as CVE-2016-5195

First of all choose the fitted linux version for that vuulnerability.

then install it via vbox or others etc..

after install it follow those instructions.

1.create a user without having root access.

2.log into that created user.

3.create directory

4.create root access .txt document and give to it read only permission.

5.compile and run the .c file in where the .txt file created.

7.then run it., 
          before it running there are two arguments want to give to it.
          ./<compile name of file> <created r-only file> <write here something>


Referances,
1.https://chao-tic.github.io/blog/2017/05/24/dirty-cow#fn:madv
2.https://www.youtube.com/watch?v=0BHFT8YkApI
3.https://en.wikipedia.org/wiki/Copy-on-write#Copy-on-write_in_virtual_memory_management
4.https://gist.github.com/rverton/e9d4ff65d703a9084e85fa9df083c679
5.https://www.cs.toronto.edu/~arnold/427/18s/427_18S/indepth/dirty-cow/index.html
6.https://www.makeuseof.com/tag/dirty-cow-vulnerability-everything-know/
7.https://en.wikipedia.org/wiki/Dirty_COW
8.https://gist.github.com/rverton/e9d4ff65d703a9084e85fa9df083c679
9.https://www.youtube.com/watch?v=CQcgz43MEZg
10.https://www.youtube.com/watch?v=kEsshExn7aE&t=4s
