# Solution
I believe I've seen something similar to this before (perhaps with coins instead of balls), so this is heavily based on that.  In fact, I may have come across this while looking at puzzles for the CICS Interview Puzzle lecture 😃

If I recall correctly, the notion is that you label each box 1-10.  Then you take `n` balls out of box `n` and put them into a new box (to be weighed).  Thus, the total weight of the box should be 10*(1+2+...+10) = 550, however your weight will be short by some value `t`, which is the number of 9gm balls that were added (each one subtracting 1 from the total expected weight).  Thus, box `t` has the defective, 9gm balls.
