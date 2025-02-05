# Integers

**Definition**: (a-b) is an integer if a,b belongs to N (natural numbers). *If (a-b) = (c-d) => a+d = b+c* 

**Note: All instances of '-' is not 'minus' or "subtraction" or any kind of operator **YET**, it is simply a dash for representation**

# Lemma (Addition and multiplication)

Arriving to subtraction operator:

````
Since (a-b) = (a'-b') => a+b' = a'+b
then, (a-b) + (c-d) = (a'-b') + (c-d).
and, (a-b)*(c-d) = (a'-b')*(c-d)
````

## Proof

$$ (a-b) + (c-d) = (a+c) - (b+d) $$
**LHS** $$ (a-b) + (c-d) = (a+c) - (b+d) $$
**RHS** $$ (a'-b') + (c-d) = (a'+c) - (b'+d) $$

Now,
(a-b) = (a'-b') => a+b' = a'+b

Add b/s by (c+d)

(a+b') + (c+d) = (a'+b) + (c+d) <=> (a+c) + (b'+d) = (a'+c) + (b+d)  ----------> (1)

Now by the definition of integers:
$$(a+c) - (b+d) = (a'+c) - (b'+d)$$   --------------> (2)

This is valid. Take a moment to understand what it is truly is and do not simply make a mistake (or) assumption that we re-arranged equation (1) to get equation (2) because the rearrangement of positive numbers is not something we have defined yet as subtraction or the concept of negative numbers is not available yet!

**Multiplication**

say, (n-0) belongs to integers

now, $$(n-0) + (m-0) = (n+m) - (0+0) = (n+m) - 0$$
and $$(n-0)\*(m-0) = (nm+0) - (0+0) = n\*m-0$$

The sum of 2 natural numbers a and b is shown as a+b and product of them is denoted as ab (or a*b).

Now this shows some sort of relation between natural numbers and integers,
Any natural number k can be shown as an integer:

k = (k-0)
1 = (1-0)
0 = (0-0)

# Negation

* $$-(a-b) := (b-a)$$, a,b belongs to N.
* $$(n-0) = (0-n)$$

## Lemma (Trichotomy)

x belongs to integer then,

1) x = 0
2) x = n, n is positive and not negative
3) x = -n

### Proof

say x = (a-b), a,b belongs to N

Now, we have 3 possible combinations:
1) a>b
2) a=b
3) a<b

#### For case 1

$$a = b+c <=> (a-b) = (c-0) = c$$

#### FOr case 3

$$b = a+d

(b-a) = (d-0) = d
(a-b) = -(b-a) = -d$$

#### For case 2

$$a = a

so, a + 0 = a + 0
or, (a - a) = 0 - 0 = 0

So, (a-b) = (a-a)
$$
##### Proof that we have a trichotomy
$$
say, x = n where n is a positive natural number.

Now, x = (a-b) = n <=> (a-b) = (n-0)

so, a = b+n
or, (a-b) = -n 

where, -n = -(n-0) = (0-n)
so, a+n = b+0 = b

Since a = b+n => b+n+n = b (or) n+n = b - b = 0.
$$
Since n is a positive natural number, we have contradiction. Thus, at a given moment any one of the statements may remain true.

Thus, we can conclude the following properties:
### Properties

1) x+y = y+x
2) x+(y+z) = (x+y)+z
3) x+0 = 0+x = x
4) x + (-x) = (-x) + x
5) x\*y = y\*x
6) (x\*y)\*z = x\*(y\*z)
7) x\*1 = 1\*x
8) x\*(y+z) = x\*y + y\*z
9) (y+z)\*x = y\*x + z\*x

# Subtraction

With the availability of negation, we can define subtraction as:

$$x - y = x + (-y)$$

## Proof

$$x - y = x + (-y)

<=> (x - 0) + { - (b - 0) } = (a - 0) + (0 - b)

=> (a+0) - (0+b) =x (a+b)$$