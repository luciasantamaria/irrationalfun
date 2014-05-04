Irrational Fun
=============

The ratio of a circle's circumference to its diameter, represented by
the Greek letter π, is an irrational number—it never terminates or
repeats. The goal is to find the SoundCloud logo in π.
Details: https://developers.soundcloud.com/blog/buzzwords-contest

To run the code in the browser:

- place the ipython notebook in a directory containing
the file pi-billion.txt.

- start ipcluster for parallel processing with the ipython
  notebook. (http://ipython.org/ipython-doc/stable/parallel/parallel_process.html).
  Command: $ ipcluster start -n 8

- start the ipython notebook
  Command: $ ipython notebook --pylab=inline

- run the notebook in the browser (Menu -> Cell -> Run All)

The results of running the notebook in a multicore Linux machine with 32Gb RAM and 8 CPU cores can be visualised here: http://nbviewer.ipython.org/github/luciasantamaria/irrationalfun/blob/master/IrrationalFun.ipynb
