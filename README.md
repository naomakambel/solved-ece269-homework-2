Download Link: https://assignmentchef.com/product/solved-ece269-homework-2
<br>
<ol>

 <li><strong>Problem 1: Affine functions. </strong>A function <em>f </em>: <strong>R</strong><em><sup>n </sup></em>→ <strong>R</strong><em><sup>m </sup></em>is said to be <em>affine </em>if for any <strong>x</strong>, <strong>y </strong>∈<strong>R</strong><em><sup>n </sup></em>and any <em>α</em>, <em>β</em>∈<strong>R </strong>with <em>α </em>+ <em>β </em>= 1, we have</li>

</ol>

<em>f</em>(<em>α</em><strong>x </strong>+ <em>β</em><strong>y</strong>) = <em>αf</em>(<strong>x</strong>) + <em>βf</em>(<strong>y</strong>).

Note that without the restriction <em>α </em>+ <em>β </em>= 1, this would be the definition of linearity.

<ul>

 <li>Suppose that <strong>A </strong>∈<strong>R</strong><em><sup>m</sup></em><sup>×<em>n </em></sup>and <em>b </em>∈<strong>R</strong><em><sup>m</sup></em>. Show that the function <em>f</em>(<strong>x</strong>) = <strong>Ax </strong>+ <strong>b </strong>is affine.</li>

 <li>Prove the converse, namely, show that any affine function <em>f </em>can be represented uniquely as <em>f</em>(<strong>x</strong>) = <strong>Ax </strong>+ <strong>b </strong>for some <strong>A </strong>∈<strong>R</strong><em><sup>m</sup></em><sup>×<em>n </em></sup>and <strong>b </strong>∈<strong>R</strong><em><sup>m</sup></em>.</li>

</ul>

<ol start="2">

 <li><strong>Problem 2: Linear Maps and Differentiation of polynomials. </strong>Let P<em><sub>n </sub></em>be the vector space consisting of all polynomials of degree ≤ <em>n </em>with real coefficients. (a) Consider the transformation <em>T </em>: P<em><sub>n </sub></em>→P<em><sub>n </sub></em>defined by</li>

</ol>

<em>dp</em>(<em>x</em>)

<em>T</em>(<em>p</em>(<em>x</em>)) =   .

<em>dx</em>

For example, <em>T</em>(1 + 3<em>x </em>+ <em>x</em><sup>2</sup>) = 3 + 2<em>x</em>. Show that <em>T </em>is linear.

(b) Using {1, <em>x</em>, . . . , <em>x<sup>n</sup></em>} as a basis, represent the transformation in part (a) by a matrix <strong>A </strong>∈<strong>R</strong>(<em>n</em>+1)×(<em>n</em>+1). Find the rank of <strong>A</strong>.

<ol start="3">

 <li><strong>Problem 3: Matrix Rank Inequalities.</strong></li>

</ol>

Show the following identities about rank. (a) If <strong>A </strong>∈<strong>F</strong><em><sup>m</sup></em><sup>×<em>n</em></sup>,<strong>B </strong>∈<strong>F</strong><em><sup>n</sup></em><sup>×<em>k </em></sup>then

rank(<strong>B</strong>) ≤ rank(<strong>AB</strong>) + dim(null(<strong>A</strong>))

<ul>

 <li>If <strong>A </strong>∈<strong>F</strong><em><sup>m</sup></em><sup>×<em>n</em></sup>,<strong>B </strong>∈<strong>F</strong><em><sup>m</sup></em><sup>×<em>n </em></sup>then</li>

</ul>

rank(<strong>A </strong>+ <strong>B</strong>) ≤ rank(<strong>A</strong>) + rank(<strong>B</strong>)

<ul>

 <li>Suppose <strong>A</strong>, <strong>B </strong>∈<strong>F</strong><em><sup>m</sup></em><sup>×<em>m</em></sup>. Then show that if <strong>AB </strong>= <strong>0 </strong>then</li>

</ul>

rank(<strong>A</strong>) + rank(<strong>B</strong>) ≤ <em>m</em>

<ul>

 <li>Suppose <strong>A </strong>∈<strong>F</strong><em><sup>m</sup></em><sup>×<em>m</em></sup>. Then show <strong>A</strong><sup>2 </sup>= <strong>A </strong>if and only if</li>

</ul>

rank(<strong>A</strong>) + rank(<strong>A </strong>− <strong>I</strong>) = <em>m</em>

where <strong>I </strong>∈<strong>F</strong><em><sup>m</sup></em><sup>×<em>m </em></sup>is the identity matrix.

<ol start="4">

 <li><strong>Problem 4: Solution of Linear System of Equations. </strong>Consider the system of linear equations</li>

</ol>

<strong>y </strong>= <strong>ABx</strong>

where <strong>A </strong>∈<strong>R</strong><em><sup>n</sup></em><sup>×<em>n </em></sup>and <strong>B </strong>∈<strong>R</strong><em><sup>n</sup></em><sup>×<em>m</em></sup>, <em>m </em>≤ <em>n</em>. For each of the following cases, find conditions (in terms of null spaces and range spaces of <strong>A </strong>and <strong>B</strong>) under which there can be a unique solution, no solution, or infinite number of solutions.

<ul>

 <li>rank(<strong>A</strong>) = <em>n</em>, and rank(<strong>B</strong>) = <em>m</em>.</li>

 <li>rank(<strong>A</strong>) = <em>n</em>, and rank(<strong>B</strong>) <em>&lt; m</em>. (c) rank(<strong>A</strong>) <em>&lt; n</em>, and rank(<strong>B</strong>) = <em>m</em>.</li>

</ul>

<ol start="5">

 <li><strong>Problem 5: Infinite Dimensional Vector Spaces. </strong>Recall that <em>C</em><sup>0</sup>([0,1]) is defined as the set of all continuous functions <em>f </em>: [0,1] → <strong>R</strong>, is a vector space over <strong>R</strong>. Let <em>S </em>= {1, (<em>x </em>+ 1), (<em>x </em>+ 2)<sup>2</sup>, (<em>x </em>+ 3)<sup>3</sup>, . . . , (<em>x </em>+ <em>i</em>)<em><sup>i</sup></em>, . . . }.

  <ul>

   <li>Is there a vector in <em>S </em>which can be represented as a finite linear combination of other vectors in <em>S</em>?</li>

   <li>Can any vector in <em>C</em><sup>0</sup>([0,1]) be represented as a finite linear combination of vectors in <em>S</em>?</li>

  </ul></li>

</ol>

[Finite linear combination is a linear combination with finite number of terms]