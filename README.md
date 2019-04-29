# gnuplot
fork of http://hackage.haskell.org/package/gnuplot

I forked the Hackage project because it did not build under recent GHC (I am on 8.6.2).
There were problems with very old dependencies, in trivial areas like System.Time locale handling.
Also, Monoids and Semigroups are a bit different than they were.
Maybe a couple of other things too, but nothing significant.
Sorry I didn't make my pathces availabe on the old code, but as I don't do darcs, it was too difficult.

At some point in future I may go back to the original code and prodcue a comprehensive diff, but not for now.
