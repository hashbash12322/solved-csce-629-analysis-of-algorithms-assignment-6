Download Link: https://assignmentchef.com/product/solved-csce-629-analysis-of-algorithms-assignment-6
<br>



(The homework is due April 30, at 5:00pm. Please submit it to HRBB 315C)

<ol>

 <li>A <em>vertex cover </em>in an undirected graph <em>G </em>is a set <em>C </em>of vertices in <em>G </em>such that every edge in <em>G </em>has at least one end in <em>C</em>. Consider the following two versions of the Vertex-Cover problem:</li>

</ol>

VC-D: Given a graph <em>G </em>and an integer <em>k</em>, decide whether <em>G </em>contains a vertex cover of at most <em>k </em>vertices.

VC-O: Given a graph <em>G</em>, construct a minimum vertex cover for <em>G</em>

Prove: VC-D is solvable in polynomial time if and only if VC-O is solvable in polynomial time. <strong>2. </strong>Prove that the VC-D problem given in Question 1 is in NP.

<ol start="3">

 <li>Using the fact that the independent set problem is NP-complete, prove that the following problem is NP-complete:</li>

</ol>

Clique: Given a graph <em>G </em>and an integer <em>k</em>, is there a set <em>C </em>of <em>k </em>vertices in <em>G </em>such that for every pair <em>v </em>and <em>w </em>of vertices in <em>C</em>, <em>v </em>and <em>w </em>are adjacent in <em>G</em>?

1

<strong>Definitions.</strong>

<ol>

 <li>P is the collection of all (decision) problems that can be solved in polynomial time. Thus, P is the collection of all “easy” problems.</li>

 <li>NP is the collection of all (decision) problems whose solutions, though perhaps not easy to construct, but can be checked in polynomial time. NP contains many problems that are not known to be in P. Examples include traveling salesman, satisfiability, and independent set. Huge amount of efforts has been paid trying to develop polynomial-time algorithms for these problems, but all failed. A common belief is that these problems are hard and do not belong to P, i.e., P6= NP.</li>

 <li><em>Q</em><sub>1 </sub>≤<em><sup>p</sup><sub>m </sub>Q</em><sub>2 </sub>means that up to polynomial-time computation, <em>Q</em><sub>1 </sub>is not harder than <em>Q</em><sub>2</sub>.</li>

 <li>NP-hard problems are those that are not easier than any problems in NP (up to polynomial-time computation). Based on the common belief given in 2, an NP-hard problem cannot be solved in polynomial time.</li>

</ol>

<strong>Some thing you may want to remember.</strong>

<ol>

 <li>To show <em>Q</em><sub>1 </sub>≤<em><sup>p</sup><sub>m </sub>Q</em><sub>2</sub>, you need to construct a polynomial-time algorithm that computes a function <em>f </em>such that <em>x </em>is a yes-instance of <em>Q</em><sub>1 </sub>if and only if <em>f</em>(<em>x</em>) is a yes-instance of <em>Q</em><sub>2</sub>.</li>

 <li>To prove that a problem <em>Q </em>is in NP, you need to construct a polynomial-time algorithm <em>A</em>(<em>x,y</em>) such that for any yes-instance <em>x</em><sub>1 </sub>of <em>Q</em>, there is a <em>y</em><sub>1 </sub>such that <em>A</em>(<em>x</em><sub>1</sub><em>,y</em><sub>1</sub>) = 1, and for any no-instance <em>x</em><sub>2 </sub>of <em>Q</em>, <em>A</em>(<em>x</em><sub>2</sub><em>,y</em>) = 0 for all <em>y</em>.</li>

 <li>To prove that a problem <em>Q </em>is NP-hard, you need to pick a problem <em>Q</em><sub>0 </sub>that is known to be NP-hard, and show <em>Q</em><sub>0 </sub>≤<em><sup>p</sup><sub>m </sub>Q</em>.</li>

 <li>To prove that a problem <em>Q </em>is NP-complete, you need to prove both that <em>Q </em>is NP-hard and that <em>Q </em>is in NP.</li>

 <li>You should remember of the definitions of at least the following NP-complete problems:</li>

</ol>

satisfiability, independent set, vertex cover, partition, and subset-sum.

2