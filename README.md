# cpsc449-exercise-2-haskell-solved
**TO GET THIS SOLUTION VISIT:** [CPSC449 Exercise 2-Haskell Solved](https://www.ankitcodinghub.com/product/cpsc-449-haskell-exercises-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116296&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CPSC449 Exercise 2-Haskell  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
For this exercise you are expected to develop at least 6 of the programs below. The tutorials will work through (some of) the solutions. You are expected to hand in a documented Haskell script containing your solutions … I encourage you to discuss these programs with your classmates: the aim is to complete these exercises (somehow!) so that you get used to thinking in Haskell syntax and using high-order functions. You should comment your code indicating, in particular, how you arrived at a solution. Recall that it is important that you understand the solutions as this comprehension will be tested in the tutorial written tests.

Please name your functions according to what is prescribed below. If there are name conflicts with names defined in Prelude, then (a) explicitly import Prelude, and (b) use the hiding clause to hide the conflicting names when importing (see the grey box on page 53 of [Thompson]).

1. A logical formula in two variable is a function of the form f :: (Bool,Bool)− &gt; Bool. Write a function

twoTautology:: ((Bool,Bool) -&gt; Bool) -&gt; Bool

which determines whether a logical formula f is always true (i.e. a tautology): to be a tautology it must be true for all possible arguments of f)! Now write a function which determines whether two logical functions of two variables are equivalent:

twoEquiv::((Bool,Bool)-&gt;Bool)-&gt;((Bool,Bool)-&gt;Bool)-&gt;Bool

This should be true when the functions agree on all inputs.

2. Write a function

badFermat :: Integer

that shows Fermat’s conjecture (all numbers of the form 22n+1 are prime) is false by finding a number for which it is not true. What happens if the conjecture is true?

3. The function

collatz :: Int -&gt; Int

is defined by collatz(n) = n/2 if n is even and collatz(n) = 3n + 1 if n is odd. It is believed that if collatz is applied repeatedly, then eventually one will see the number 1. For example, collatz(5) = 16, and collatz(16) = 8, and collatz(8) = 4, and collatz(4) = 2, and collatz(2) = 1. The Collatz index of a number is the minimum number of times that collatz needs to be applied to obtain 1. For example, the Collatz index of 5 is 5, and the Collatz index of 7 is 16 (the sequence is

[7,22,11,34,17,52,26,13,40,20,10,5,16,8,4,2,1]. Write a Haskell function

collatzIndex :: Int -&gt; SF [Int]

which computes the Collatz “index” of a number by calculating the sequence ending in 1. What happens if a number has no Collatz index?

4. The bisection method is a neat way to find (approximate) roots to continuous functions –it has advantages to Newton’s method because it only requires the function to be continuous instead of differentiable. Fix e to be a really small number (sometimes called machine epsilon) by making it a constant

e :: Double e = exp (-150)

We will regard any x with |x| &lt; e as being effectively zero. Let f : R → R be a continuous function, and a and b are numbers for which f(a) and f(b) have opposite signs. Then f has a zero (crosses the axis) in the interval [a,b]. The bisection method computes the midpoint, m, of a and b, and then compares the sign of f(a), f(b), f(m). One of the pairs (f(a),f(m)) or (f(m),f(b)) have opposite signed numbers, or m is a root |f(m)| &lt; e. Use this information to either return the root, or continue searching on a smaller interval. Write a Haskell program

bisection::(Double-&gt;Double)-&gt;(Double,Double)-&gt;Maybe Double

which given a function f and a pair of initial values (a,b), returns, when f(a) and f(b) are of opposite sign or one is effectively zero, the value (up to e!) of a zero crossing for the function f.

5. Implement bubble sort, quicksort, and merge sort in Haskell:

bsort::(a -&gt; a -&gt; Bool) -&gt; [a] -&gt; [a] qsort::(a -&gt; a -&gt; Bool) -&gt; [a] -&gt; [a] msort::(a -&gt; a -&gt; Bool) -&gt; [a] -&gt; [a]

6. A matrix in Haskell can be represented by the type

type Matrix a = [[a]] type DoubleMatrix = Matrix Double

Write functions

transpose:: Matrix a -&gt; (Maybe (Matrix a)) addMat :: DoubleMatrix -&gt; DoubleMatrix -&gt; (Maybe DoubleMatrix) multMat :: DoubleMatrix -&gt; DoubleMatrix -&gt; (Maybe DoubleMatrix)

Which returns a matrix when these functions are well-defined.

7. Implement list reversal in at least two different ways from naive reverse, fast reverse, ahigher-order reverse (using a fold left):

nreverse:: [a] -&gt; [a] freverse:: [a] -&gt; [a] hreverse:: [a] -&gt; [a]

8. An AVL tree is a binary search tree:

data STree a = Node (STree a) a (STree a)

| Leaf

consisting of a tree of items which are ordered satisfying two conditions

(a) The value of an item at a node is larger than any item in its left tree and smaller than anyitem in its right tree

(b) The tree is balanced: the difference in height between the left tree and right tree at anynode is at most 1.

Write a function to determine whether a tree is an AVL tree:

isAVL:: (Ord a) =&gt; STree a -&gt; Bool

9. Calculate the factorial of 1,891 or explain six different ways of programming factorial (seehttp://www.willamette.edu/ fruehr/haskell/evolution.html).

10. Given a Rose tree ( data Rose a = RS a [Rose a] ) calculate the width of the tree

(that is, in the undirected graph of the tree, the length of the longest path):

widthRose: Rose a -&gt; Int

Can you do this using a fold?
