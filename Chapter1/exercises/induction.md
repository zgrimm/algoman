#1-10: 
 
__Prove__:  

![formula](http://latex.codecogs.com/gif.latex?%24%5Cdisplaystyle%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%20i%20%3D%20n%28n%2B1%29/2%5C%3B%5C%3B%20%20for%5C%3B%5C%3B%20n%20%3E%3D%200%2C%5C%3B%5C%3B%20by%5C%3B%20induction%24 "$\\displaystyle\\sum\_{i=1}^{n} i = n(n+1)/2\\;\\;  for\\;\\; n >= 0,\\;\\; by\\; induction$")

Let n = 1. Then:

![formula](http://latex.codecogs.com/gif.latex?%24n%28n%2B1%29/2%20%3D%201%20%3D%20%5Cdisplaystyle%5Csum_%7Bi%3D1%7D%5E%7B1%7D%20i%20 "$n(n+1)/2 = 1 = \\displaystyle\\sum\_{i=1}^{1} i ")
establishing our base case.

Assume that:

![formula](http://latex.codecogs.com/gif.latex?%24%5Cdisplaystyle%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%20i%20%3D%20n%28n%2B1%29/2%5C%3B%5C%3B%5C%3B%20%20for%5C%3B%20n%20%3C%3D%20k%2C%5C%3B%5C%3B%5C%3B%20%24 "$\\displaystyle\\sum\_{i=1}^{n} i = n(n+1)/2\\;\\;\\;  for\\; n <= k,\\;\\;\\; $")

We must show:

![formula](http://latex.codecogs.com/gif.latex?%24%5Cdisplaystyle%5Csum_%7Bi%3D1%7D%5E%7Bn%20%2B%201%7D%20i%20%3D%20%28n%2B1%29%28n%2B2%29/2%5C%3B%5C%3B%5C%3B%20%24 "$\\displaystyle\\sum\_{i=1}^{n + 1} i = (n+1)(n+2)/2\\;\\;\\; $")

![formula](http://latex.codecogs.com/gif.latex?%24%5Cdisplaystyle%5Csum_%7Bi%3D1%7D%5E%7Bn%20%2B%201%7D%20i%20%3D%20n%2B1%20%2B%20%5Csum_%7Bi%3D1%2Cn%7D%20i%0A%5C%5C%3D%20n%2B1%20%2B%20n%28n%2B1%29/2%0A%5C%5C%3D%20%28n%2B1%29%28n%2B2%29/2%20%5C%5Cwhich%5C%3B%20we%5C%3B%20needed%5C%3B%20to%5C%3B%20show%5C%3B%20%3A.%24%0A%0A%0A%20%20%20%20 "$\\displaystyle\\sum\_{i=1}^{n + 1} i = n+1 + \\sum\_{i=1,n} i
\\\\= n+1 + n(n+1)/2
\\\\= (n+1)(n+2)/2 \\\\which\\; we\\; needed\\; to\\; show\\; :.$


    ")


    Assume that SUM{i=1,n}(i) = n(n+1)/2 for numbers <= n and  n >=0 
    SUM{i=1,n + 1}(i) = n+1 + SUM{i=1,n}(i)
                      = n+1 + n(n+1)/2
                      = (n+1)(n+2)/2 which we needed to show :.
                      $\displaystyle\sum_{i=1}^{n+1} i $


    
    Let n = 1. Then n(n+1)/2 = 1 = SUM{i=1,1}(i) :.
    Assume that SUM{i=1,n}(i) = n(n+1)/2 for numbers <= n and  n >=0 
    SUM{i=1,n + 1}(i) = n+1 + SUM{i=1,n}(i)
                      = n+1 + n(n+1)/2
                      = (n+1)(n+2)/2 which we needed to show :.

#1-11: 

__Prove__:  SUM{i=1,n}(i^2) = n(n+1)(2n+1)/6 for n >= 0, by induction
    
    let n = 1. Then n(n+1)(2n+1)/6 = 1 = SUM{i=1,1}(i^2)
    Assume that SUM{i=1,n}(i^2) = n(n+1)(2n+1)/6.
    SUM{i=1,n + 1}(i^2) = (n+1)^2 + SUM{i=1,n}(i^2)
                        = (n+1)^2 + n(n+1)(2n+1)/6
                        = (n+1)[6(n+1) + n(2n+1)] / 6
                        = (n+1)[2n^2 +7n + 6] / 6
                        = (n+1)(n+2)(2n +3) / 6
                        = (n+1)(n+2)(2(n+1) + 1) / 6 which we needed to how :.



1-12: 

 SUM{i=1,n}(i^3) = n^2(n+1)^2/4 for n >= 0, by induction

1-13: // Prove SUM{i=1,n}((i)*(i+1)*(i+2)) = n(n+1)(n+2)(n+3)/4 for n >= 0, by induction
 
1-14: 
Prove by induction on n >= 1 that for every a!=1
  SUM{i=0,n}(a^i) = [a^(n+1) - 1] / [a - 1]

1-15: Prove by induction on n >= 1 
  SUM{i=1,n}(1/i*(i+1)) = n/(n+1)

1-16: Prove by induction that n^3 + 2n is divisible by 3 for all n ≥ 0.

1-17: Prove by induction that a tree with n vertices has exactly n − 1 edges

1-18: Prove by mathematical induction that the sum of the cubes of the first n
positive integers is equal to the square of the sum of these integers, i.e.
	SUM{i=1,n}(i^3) = [SUM{i=1,n}(i)]^2 


    > dknfddf dknfddfdknfddfdknfddfdknfddfdknfddfdknfddf
    > dknfddfdknfddfdknfddfdknfddfdknfddfdknfddfdknfddf
    > 
    > dknfddf

    ![formula](http://latex.codecogs.com/gif.latex?%24%24%5Cint_%7Ba%7D%5E%7Bb%7D%20x%5E2%20dx%24%24 "$$\\int\_{a}^{b} x^2 dx$$")





![formula](http://latex.codecogs.com/gif.latex?%24%24%5Cint_%7Ba%7D%5E%7Bb%7D%20x%5E2%20dx%24%24 "$$\\int\_{a}^{b} x^2 dx$$")