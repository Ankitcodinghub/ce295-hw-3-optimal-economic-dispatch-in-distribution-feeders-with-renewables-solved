# ce295-hw-3-optimal-economic-dispatch-in-distribution-feeders-with-renewables-solved
**TO GET THIS SOLUTION VISIT:** [CE295 HW 3-Optimal Economic Dispatch in Distribution Feeders with Renewables Solved](https://www.ankitcodinghub.com/product/ce295-hw-3-optimal-economic-dispatch-in-distribution-feeders-with-renewables-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95669&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CE295 HW 3-Optimal Economic Dispatch in Distribution Feeders with Renewables Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
HW3: Optimal Economic Dispatch in Distribution Feeders with Renewables

This assignment will provide hands-on practice for optimization with application to the economic dispatch problem in power systems. The assignment is organized in a tutorial fashion, thereby allowing you to practice optimization theory on a relevant real-world energy system example.

Background

In this assignment you will practice optimization with the DistFlow equations of Baran &amp; Wu [1] (1)-(9). The DistFlow equations model power flow through radial distribution power networks. The beauty of the DistFlow equations is that they are relatively simple (i.e. they yield convex programs). Yet, they model active &amp; reactive (AC) power, branch power flow limits, node voltage limits, etc. Despite their simplicity, the DistFlow equations are much more sophisticated that the “supply = demand” single equation used by many energy policy researchers. In this assignment, your objective is to optimally schedule distributed energy generators in a distribution feeder to minimize economic costs, while maintaining safe operating constraints.

Consider the IEEE 13-node Test Feeder shown in Fig. 1, adopted from [2]. We mathematically rep- resent this test feeder by a radial undirected graph G = (N,L). Symbol N = {0,1,2,··· ,12} repre- sents the set of nodes (a.k.a. “buses” in power sys- tems jargon). Symbol L ⊂ N × N represents the set of edges (a.k.a. “lines” in power systems jar- gon). For notational convenience, we introduce the concepts of parent nodes and the adjacency matrix. The parent of j, ρ(j), is the adjacent node in the direction toward node 0. The adjacency matrix, A, encodes the network topology. Mathematically, it is a13×13matrixofzerosandones. Aij =1ifnode i is the parent node of node j. Otherwise, Aij = 0.

Ateachnodej∈N,wehaveljP,ljQ activeandre-

active power consumed, respectively. Additionally,

pj , qj active and reactive power are generated, re-

spectively. Note that total power is complex num-

ber (due to AC power flow), where the real part is Figure 1: IEEE 13-Node Test Feeder

given by active power pj and the imaginary part is given by reactive power qj. The magnitude of complex power is given by sj in equation (6).

Voltage at each node is a complex number. We mathematically model this by the squared voltage magnitude Page 1 of 6

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
0 54123

11 10 6 8 9 12 7

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Vj. In general, we must schedule generators to regulate nodal voltages around a nominal value (see (8)). Each edge (i,j) (or “line”) has a characteristic impedance, decomposed into resistance rij and reactance xij. The active and reactive power flowing along line (i,j) is given by Pij and Qij, respectively. Finally, the squared magnitude of complex current on line (i,j) is given by Lij. Lines have a maximum current capacity, given by constraint (9).

Power is supplied in two ways. First, power can be imported from the transmission grid connected to node 0. Second, power can be generated from distributed generators within the feeder network. We have a gas generator on node 3, and solar generator on node 9.

Your objective is to supply all electricity demand at minimum cost. Simultaneously, you must ensure all generator output powers, nodal voltages, and line currents are within safe operating bounds.

</div>
</div>
<div class="layoutArea">
<div class="column">
Table 1: Nomenclature

</div>
</div>
<div class="layoutArea">
<div class="column">
Symbol

N

E

ρ(i)

A

pi

qi

si

si,max

liP , liQ

Vi

vmin, vmax ci

rij

xij

Pij

Qij

Lij

Iij WA,WB σA,σB

</div>
<div class="column">
Description

</div>
<div class="column">
Units

[-]

[-]

[-]

[-]

[MW]

[MVAr] [MVA]

[MVA]

[MW], [MVAr] [p.u.]

[p.u.] [USD/MVA] [p.u.]

[p.u.]

[MW] [MVAr] [p.u.]

[p.u.]

[MVA]

[%]

</div>
</div>
<div class="layoutArea">
<div class="column">
Set of nodes (a.k.a. buses)

Set of edges (a.k.a. lines)

Parent of node i, e.g. ρ(6) = {1}, ρ(12) = {10}

Adjacency Matrix (13×13) encoding network structure

active power generated at node i

reactive power generated at node i

apparent power generated at node i

apparent power generation capacity at node i

active, reactive power consumed at node i

Squared voltage magnitude at node i

Minimum, maximum nodal voltage

Marginal cost of apparent power generation at node i

resistance of line (i, j )

reactance of line (i, j )

active power flowing on line (i, j)

reactive power flowing on line (i, j)

Squared magnitude of complex current on line (i,j)

Maximum magnitude of complex current on line (i,j)

Uncertain &amp; weather-dependent power capacity of PV panels A,B Percentage power output of PV panels A,B

</div>
</div>
<div class="layoutArea">
<div class="column">
Note: The acronym “p.u.” stands for per-unit. It’s power systems jargon for “normalized to a unitless quantity”. For your convenience, all the data has been normalized to simplify your analysis. For interested readers, the base parameters for normalization in this HW are Sbase = 1 MW, Vbase = 4.17 kV.

Page 2 of 6

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
CE 295: Energy Systems and Control UC Berkeley

Pij = (ljP − pj) + rijLij + 􏰉 AjkPjk k∈N

Qij = (ljQ − qj) + xijLij + 􏰉 AjkQjk k∈N

V=V+(r2+x2)L −2(rP +xQ)

</div>
<div class="column">
Spring 2019 Professor Scott Moura

∀j∈N,i=ρ(j) (1) ∀j∈N,i=ρ(j) (2)

∀j∈N,i=ρ(j) (3) ∀j∈N,i=ρ(j) (4) ∀j∈N (5)

∀j∈N (6) ∀j∈N (7) ∀j∈N (8)

∀j∈N,i=ρ(j) (9)

</div>
</div>
<div class="layoutArea">
<div class="column">
j i ij ij ij Pij2 +Qij2

</div>
<div class="column">
ij ij

</div>
<div class="column">
ij ij

</div>
</div>
<div class="layoutArea">
<div class="column">
Lij= V j

</div>
</div>
<div class="layoutArea">
<div class="column">
pj≥0, qj≥0

􏰐

pj 2 + qj 2 = ∥[pj , qj ]∥2 = sj sj ≤ sj,max

v2 ≤V≤v2 min j max

L ≤I2

ij ij,max

Problem 1: Network Parameters

</div>
</div>
<div class="layoutArea">
<div class="column">
Download and open the data file HW_Data.xls. Copy over the test network parameters from the xls file into the Matlab/Python skeleton code file.

<ol>
<li>(a) &nbsp;Create a bar plot of the active and reactive power consumption. Make the x-axis the node index number, while the y-axis is the power consumption. Place the active &amp; reactive powers side-by-side for each node. Add a legend.</li>
<li>(b) &nbsp;Fill out the adjacency matrix with zeros and ones. Include in your report.</li>
</ol>
Problem 2: Balancing Supply &amp; Demand without a Network

Start simple: In this problem, we will optimally dispatch our generators to minimize cost, while disregarding the network completely. That is, we seek to balance active &amp; reactive power supply &amp; demand, while minimizing generation cost and completely ignoring line losses and constraints.

<ol>
<li>(a) &nbsp;What are the optimization variables?</li>
<li>(b) &nbsp;Write down the objective function, using the notation in Table 1.</li>
<li>(c) &nbsp;Write down ALL the constraints, using the notation from Table 1. Label the physical meaning of each constraint. For this problem, ignore voltages and all constraints associated with line flows.</li>
<li>(d) &nbsp;Is this a linear program (LP), quadratic program (QP), or convex program (CP)? Why or why not? What happens when we relax (6) from an equality constraint to an inequality (≤) constraint?</li>
<li>(e) &nbsp;Code and numerically solve this problem in Matlab or Python using cvx or cvxpy, respectively. Use the relaxed version of (6), so your optimization program is convex. In your report provide (i) the optimal active &amp; reactive generator powers, and (ii) the minimum generating cost.</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Problem 3: Add Line Power Flows

Next, we add line power flows Pij,Qij but still neglect the nodal voltage Vj and Lij terms.

<ol>
<li>(a) &nbsp;What are the optimization variables?</li>
<li>(b) &nbsp;Write down ALL the constraints, using the notation from Table 1. Label the physical meaning of each constraint. For this problem, ignore (3)-(4) and drop the Lij terms from (1)-(2).</li>
<li>(c) &nbsp;Code and numerically solve this problem in Matlab or Python using cvx or cvxpy, respectively. In your report provide (i) the optimal active &amp; reactive generator powers, and (ii) the minimum generating cost. Should the minimum and minimizers be different or the same as Problem 2? Why?</li>
<li>(d) &nbsp;In your code, declare a dual variable μs corresponding to the inequality (7). Re-compute the optimal solution and dual variable. If we could increase the solar power capacity by 1MW, then how much money would we save?</li>
</ol>
Problem 4: The Complete Optimal Economic Dispatch with DistFlow Equations

Now we add the nodal voltages Vj, squared current magnitudes Lij, and their bounds (8)-(9). This incor- porates impedance (i.e. losses) across the network, along with nodal voltage and line transmission limits.

<ol>
<li>(a) &nbsp;What are the optimization variables?</li>
<li>(b) &nbsp;Write down ALL the constraints, using the notation from Table 1. Label the physical meaning of each constraint.</li>
<li>(c) &nbsp;Is this a convex program (CP)? Why or why not? What happens when we relax (4) from an equality constraint to an inequality (≥) constraint?</li>
<li>(d) &nbsp;Code and numerically solve this problem in Matlab or Python using cvx or cvxpy, respectively. In your report provide (i) the optimal active &amp; reactive generator powers, and (ii) the minimum generating cost. Use vmin = 0.95, vmax = 1.05 as your voltage limits. Is the solution equivalent to the solution in Problem 3? Why or why not?</li>
<li>(e) &nbsp;Use the dual variables to determine which constraints are active. Specifically, identify at which nodes the voltage constraint (8) and line current constraint (9) are active.</li>
<li>(f) &nbsp;Now re-solve the problem with vmin = 0.98, vmax = 1.02 as your voltage limits. In your report provide (i) the optimal active &amp; reactive generator powers, and (ii) the minimum generating cost. Why did the solution change?</li>
</ol>
Problem 5: [OPTIONAL] Robust Economic Dispatch with Renewables. Next, we explore robust economic dispatch in the face of uncertain renewable generation. Imagine the solar generator at node 9 is comprised of two solar panels, A and B. The output of each panel is uncertain, and weather dependent. Mathematically, we write:

s9 ≤WA ·σa +WB ·σb (10) where σa, σb ∈ [0, 1] represent the percentage output of each panel. Symbols WA, WB are random variables

that represent the uncertain power capacity of each panel, due to weather. We hypothesize that WA,WB Page 4 of 6

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
vary between 1 MW and 1.5 MW. Our goal, in this problem, is to optimally schedule the generators in the face of uncertain solar capacity. Note, this problem is similar to Example 3.4 in the CH3 notes.

<ol>
<li>(a) &nbsp;Re-arrange(10)intotheformaTy≤b. Whatarea,y,andb? Hint: a∈R3,y∈R3,b∈R.</li>
<li>(b) &nbsp;We now hypothesize that vector a is uncertain, but lies within an ellipsoid
a ∈ E = {a ̄ + Eu | ∥u∥2 ≤ 1} (11)

Provide the values for a ̄ and E. Hint #1: a ̄ ∈ R3 represents the center of the ellipsoid. Hint #2: E ≽ 0 ∈ R3×3 encodes the lengths of the semi-axes. If E is diagonal, then the diagonal elements represent the semi-axis lengths along each coordinate of a.
</li>
<li>(c) &nbsp;The robust version of (10) is
aTy≤b, ∀a∈E (12) Convert this robust linear inequality into a second-order cone constraint. In your report, it is only

necessary to provide the final written form of the second order cone constraint.
</li>
<li>(d) &nbsp;In your report, write down the new robust optimization problem. What are the optimization variables? Write down ALL the constraints, using the notation from Table 1. Label the physical meaning of each constraint.</li>
<li>(e) &nbsp;Now solve the optimization program with vmin = 0.95,vmax = 1.05 as your voltage limits. In your report provide (i) the optimal active &amp; reactive generator powers, and (ii) the minimum generating cost. How did the solution change?</li>
</ol>
Interesting Remarks

<ul>
<li>Power system operators utilize day-ahead load predictions to solve the economic dispatch problem and procure generation on an hourly basis. Mismatch between predicted and actual load is compensated by “spinning reserves”.</li>
<li>This homework is not trivial. However, by completing it, you have quickly acquired sophisticated knowledge and skills in power systems and optimization. DistFlow equations, convex optimization, and robust optimization are skills one normally finds in power systems / optimization PhD students. Well done!
Deliverables

Submit the following on bCourses. Be sure that the function files are named exactly as specified (including spelling and case). Please do NOT zip files.

LASTNAME_FIRSTNAME_HW3.PDF

LASTNAME_FIRSTNAME_HW3.xyz which contains your respective Matlab or Python files, i.e. xyz ∈ {m, ipynb}.
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
How to Download and Install CVX

Matlab Instructions

<ul>
<li>Go to http://cvxr.com/cvx/download/</li>
<li>In the “Download Matrix”, focus your attention on the “Standard bundles, including Gurobi and/or MOSEK”.</li>
<li>Click the package corresponding to your system. For example, I have a MacBook Pro Early 2015, so I’ll select mexmaci64. You can download a .zip or .tar.gz file.</li>
<li>Download and unpack anywhere you like. The Downloads folder is a reasonable option.</li>
<li>Start Matlab.</li>
<li>Change directories to the top of the CVX distribution. Hint: Use command » cd /Users/scottmoura/ Downloads/cvx</li>
<li>Run Matlab command » cvx_setup</li>
<li>The cvx_setup command runs a variety of checks to verify your installation is correct.</li>
<li>After successfully installing CVX, please go to http://cvxr.com/news/2014/02/cvx-demo-video/ to watch the Getting Started Demo from Prof. Stephen Boyd.</li>
<li>Toconfirmasuccessfulunderstanding,trycodingandsolvingtheexampleshownathttp://cvxr.com/cvx/
Python Instructions

<ul>
<li>Ensure you have installed Anaconda, as recommended in this class</li>
<li>Go to https://www.cvxpy.org/install/index.html</li>
<li>Follow the instructions corresponding to your system</li>
<li>After successfully installing CVXPY, fire-up the iPython notebook. You can try the Portfolio opti- mization example linked here.
References
</li>
</ul>
</li>
</ul>
<ol>
<li>[1] &nbsp;M. Baran and F. Wu, “Network reconfiguration in distribution systems for loss reduction and load balancing,” IEEE Transactions on Power Delivery, vol. 4, no. 2, pp. 1401–1407, apr 1989. [Online]. Available: http://ieeexplore.ieee.org/document/25627/</li>
<li>[2] &nbsp;J. Fuller, Y. Xu, B. Kersting, R. Dugan, and S. Carneiro Jr., “IEEE PES Distribution Test Feeders,” 2010. [Online]. Available: https://ewh.ieee.org/soc/pes/dsacom/testfeeders/
Page 6 of 6
</li>
</ol>
</div>
</div>
</div>
