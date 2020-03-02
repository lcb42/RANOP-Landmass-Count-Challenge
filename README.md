# RANOP-Landmass-Count-Challenge

This is the technical challenge undertaken before being offered a job at XXXXXX.

The problem:
- A text file consisting of various symbols representing islands and seas was given
- The solution must detect exactly how many islands are present on the map.txt which was given.

My Solution:
- While most solutions work iteratively, first finding one land char before spiralling out, I used 
  the two-pass algorithm as seen in my Computer Vision lectures.
- The two-pass algorithm scans the file twice, the first time labelling every char, and the second time grouping these labels
- This makes it much more efficient than any iterative solution.
