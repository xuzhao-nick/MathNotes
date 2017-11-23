##Functions

A <i><b>function</b></i> is a way of maching up one set of numbers with another. The first set of numbers is called the <b><i>domain</i></b>. For each of the numbers in the domain, the function assigns exactly one number from the other set, the range.

For example, the domain of the function could be the set of numbers {1, 4, 9, 25, 100}, and the range could be {1, 2, 3, 5, 10}. Suppose the function takes 1 to 1, 4 to 4,2, 9 to 3, 25 to 5, and 100 to 10. This could be illustrated by the following:
```
1  ->  1
4  ->  4
9  ->  3
25 -> 25
100 -> 10
```
   
Because we sometimes use several fuctions in the same discussion, it makes sense to give them names. Let us call the function we just mentioned by the name <i>Eugene</i>. Thus, we can ask, "Hey, what does Eugene do with the number 4?" The answer is "Eugene takes 4 to the number 2."

Mathematicians like to write as little as possible. Thus, instead of writing "Eugene takes 4 to the number 2," we often write "Eugene(4) = 2" to mean the same thing. Similarly, we like to use names that are as short as possible, such as f(for function), g(for function when f is already being used), h, and so on. The trigonometric functions all have three letter names like sin and cos, but even these are abbreviations. So let us save space and use f instead of Eugene.

Because the domain is small, it is easy to write out everything:

```
f(1) = 1
f(4) = 2
f(9) = 3
f(25) = 5
f(100) = 10

```

However, if the domain were large , this would get very tedious. It is much easier to find a pattern and use that pattern to describe the function. Our function f just happens to take each number of its domain to the square root of that number. Therefore, we can describe f by saying:

```
f(a number) = the square root of that number
```

Of course, anyone with experience in algebra knows that writing "a number" over and over is a waste of time. Why not just pick a <i>variable</i> to represent the number? Just as <i>f</i> is a typical name for a function, little <i>x</i> is often used for a variable name. Using both, here is a nice way to represent our function <i>f</i>:

$$ f(x) = \sqrt{x} $$

This tells us that putting a number into the function <i>f</i> is the same as putting it into . Thus,

$$f(25) = \sqrt{25} = 5 $$ and $$f(4) = \sqrt{4} = 2.$$




####Example

Find the value of g(3) if

$$ g(x) = x^2 + 2 $$

####Solution
Replace each occurrence of x with 3.

$$ g(3) = 3^2 + 2 $$

Simplify.

$$g(3) = 9 + 2 = 11 $$

####Example
Find the value of h(-4) if 

$$h(t) = t^3 - 2t^2 + 5$$

Simplify.

$$h(-4) = -64 - 2(16) + 5 = -64-32+5 = -91$$

####Practice

<b>1.</b> Find the value of f(5) when f(x) = 2x - 1.

<b>2.</b> Find the value of g(-3) when 

$$ g(x) = x^3 + x^2 + x + 1.$$

<b>3.</b> FInd the value of h(1/2) when 

$$ h(t) = t^2 +  {3 \over 4}. $$

<b>4.</b> Find the value of f(7) when f(x) = 2

<b>5.</b> Find the value of m(-1/5) when 

$$ m(t) = -5t^3$$.

<b>6.</b> Find the value of h(64) when 

$$ h(x) = \sqrt{x} - \sqrt[3]x$$

<b>7.</b> Suppose that after t seconds, a rock thrown off a bridge has height

$$ s(t) = -16t^2 + 20t + 100$$

feet of the ground. What is the height above the ground after 3 seconds?

<b>8.</b> Suppose that the profit on making and selling x cookies is 

$$ P(x) = {x \over 2} - {x^2 \over 10,000} - 10.$$

How much profit is made on selling 100 cookies?

##Plugging Variables into Functions

Variables can be plugged into functions just as easily as numbers can. Often though, the result can't be simplified as much.

####Example
Simplify f(w) if

$$f(x) = \sqrt{x} + 2x^2+2$$

####Solution
Replace each occurrence of x with w.

$$f(w) = \sqrt{w} + 2w^2 + 2$$

That is all we can say without knowing more about w.

####Example
Simplify g(a + 5) if

$$ g(t) = t^2 - 3t + 1.$$

####Solution
Replace each occurence of t with (a+5).

$$g(a + 5) = (a + 5)^2 - 3(a + 5) + 1$$

Multiply out 

$$(a + 5)^2$$ and $$-3(a + 5)$$.

$$g(a+5)= a^2 + 10a + 25 - 3a - 15 + 1 $$

Simplify.

$$ g(a + 5) = a^2 + 7a + 11 $$

####Example
Simplify 

$$f(x + a) - f(x) \over a$$

if $$f(x) = x^2 $$

####Solution
Start with what needs to be simplified.
$$ f(x+a) - f(x) \over a $$

Use $$f(x) = x^2 $$ to evaluate f(x + a) and f(x).

Multiply out $$(x + a)^2.$$

Cancel the $$x^2$$ and the $$-x^2$$

Factor out an a.

$$(2x + a)a \over a$$

Cancel an a from the top and bottom.

$$2x + a$$














Reference book "CALCULUS success in 20 minutes a Day"(Mark A. McKibben)







