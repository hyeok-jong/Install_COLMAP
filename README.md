# Install_COLMAP  
For NeRF, It's mandatory that installing colmap.  
However there are so many bugs....  

I found that the reason of the bugs is ceres-solver.  
So I tried dozens of versions, finally figured out the succeed version of ceres-solver.  

And, I found that others had same trouble like me [ISSUE](https://github.com/hyeok-jong/hanbok_image/issues?q=is%3Aissue+is%3Aclosed).  

So, I fixed the version.    

Here is full code in [Colab env](https://colab.research.google.com/drive/107a_dVa_XtaulTmkckRYzACNl9NGYgAT?usp=sharing)  
And [COLMAP](https://github.com/hyeok-jong/colmap) and [ceres-solver](https://github.com/hyeok-jong/test4)  

Note that even though official doc of colmap suggest dev branch, I used master branch.  




