<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>

# [draft] Spatial dimension-node equivalence

## Requisite Reading

## Abstract

## Introduction

The spatial dimensions that we are familiar with form from increasing
energy levels ($\Sigma \bullet_{1}$) in a function. To be more precise, the
probability that nodes will form an edge that can be observed as a
spatial dimension increases discreetly and proportionally with the sum
of nodes in that function.

## Kinematics

The relation between spatial dimensions and their probability is shown
by the following recursive formula:

$$
  d_{x} = \left( \frac{d_{x - 1}}{x} \right)^{x}
$$

For each traditional spatial dimension $x$ (1, 2, 3, etc) the product
of its probability $d_{x}$ and the sum of function's nodes
$\Sigma \bullet_{1}$ need to be 1 or above to signify it's possible:

$$
  d_{x}\Sigma \bullet_{1}  \geq 1
$$

### 1+1 dimension function

The probability for a 1+1 dimension (1D) function can be taken as 1:

$$
  d_{1} = 1
$$

### 2+1 dimensions

The probability for a function to behave beyond 1+1 dimension depends on
the sum of nodes in the function. The probability that a function will
exhibit behaviour in 2+1 dimensions (the 2D function) is the following:

$$
  d_{2} = .25  = \frac{1}{4}
$$

So at its native scale a test for the 2D function can effectively be:

$$
  d_{2}\Sigma \bullet \geq 1
$$

Thus any function with 4 nodes ($4\bullet$) there is a hyperedge that
demonstrates a 2+1 dimension relation ([Fig. 13](#2D)).

<a name="2D">![2D hyperedge](./figures/fig13.svg)</a>

*Fig. 13: 2D hyperedge*

As the 1D edges of the system each have a probability of 1, this means
the 2D hyperedge also has a probability of 1.

Interestingly the 2D function in [Fig. 13](#2D) intuitively looks to support 2 2D
dimensions. Though if this was the case they would be interpreted
simultaneously as 2 1D systems, thus the system would be too ambiguous
to clearly denote 2D behaviour.

### 3+1 dimensions

Using the formula for 3+1 dimensions:

$$
  d_{3} = 5.787\underline{037} \times 10^{- 4} = \frac{1}{1728}
$$

The test for a 3D function is:

$$
  d_{3}\Sigma \bullet_{1} \geq 1
$$

### 4+1 dimensions

$$
  d_{4} = 4.3811193275... \times 10^{- 16} = \frac{1}{2282521714753540}
$$

For the purposes of this contribution we are only concerned with systems that
pass the following:

$$
  d_{4}\Sigma \bullet < 1 
$$

4D functions and beyond are out of the scope of this contribution.


## Tests


### Proven


### Proposed