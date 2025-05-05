# cs5446-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS5446 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs5446-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94828&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS5446 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Problem 1: Classical Planning

<ol>
<li>(a) &nbsp;Consider the 8 puzzle with the Slide schema. Consider (i) ignoring Blank(s2) in the precondition as a heuristic and (ii) ignoring Blank(s2) ∧ Adjacent(s1, s2) in the precondition as a heuristic. Which of (i) or (ii) will result in fewer nodes being explored when used with the A* algorithm? Explain why.
Both are admissible heuristics for 8 puzzle. The first case h1 is actually the sum of Manhattan distance to goal for each tile; the second situation h2 is the number of misplaced tiles. h1 will always explore fewer nodes with A*. In other words, h1 dominates h2.
</li>
<li>(b) &nbsp;Consider the Air Cargo problem. Describe how to modify the problem so that each plane can only carry one cargo.
We could add a precondition for action Load to ensure there are not other cargo on the plane.

Action(Load(c, c′, p, a),

PRECOND:At(c, a)∧At(p, a)∧¬In(c′,p)∧Cargo(c)∧Cargo(c′)∧Plane(p)∧Airport(a)

EFFECT: ¬At(c, a) ∧ In(c, p))
</li>
<li>(c) &nbsp;In the Air Cargo problem, write the successor state axiom for the fluent At(P1, SF O).
At(P1,SFO)t+1 ⇔ Fly(P1,JFK,SFO)t ∨ (At(P1,SFO)t ∧ ¬Fly(P1,SFO,JFK)t)
</li>
</ol>
Problem 2: Decision Theory

<ol>
<li>(a) &nbsp;Bob is risk adverse but rational. His utilities for A, B, and C are U(A) = 0, U(B) = 100 and U(C) = 40. He is given a choice between C and a lottery [0.4, A; 0.6, B]. Which would he choose and why?
The expected utility of the lottery is U(lottery) = 0.4 ∗ 0 + 0.6 ∗ 100 = 60 is bigger than U(c). An agent is rationally by choosing an action that maximizes the expected utility; therefore, Bob would choose to the lottery within two choices.
</li>
<li>(b) &nbsp;Alices utility function for money is U(x) = x. Argue that Alice is risk seeking. (Hint: U(x) is a strictly convex function. Jensens inequality may be useful here.)</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
For any lottery p,

the expected value of the lottery would be x ̄ = E[x] = 􏰀 p(x) ∗ x;

</div>
</div>
<div class="layoutArea">
<div class="column">
p x∈X

the expected utility of the lottery would be E[u(x)] = 􏰀x∈X p(x) ∗ U(x).

</div>
</div>
<div class="layoutArea">
<div class="column">
f(x) is a strictly convex function, since f′(x) = 2x, f′′(x) = 2 &gt; 0.

According to Jensen equality, for any strictly convex function, we have E[f(x)] &gt;

</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
f(E[x]), which means E[U(x)] &gt; U(E[x]) = U(x ̄ ). We could conclude that Alice is p

risk seeking.

(c) Cathy prefers A to B but prefers lottery C = [0.2, A; 0.8, B] to lottery D = [0.3, A; 0.7, B]. Argue that there is no utility function that satisfies Cathy’s preferences.

Cathy prefers A to B, which means that U(A) &gt; U(B);

Cathy prefers lottery C to lottery D, showing that U(lottery C) = 0.2 ∗ U(A) + 0.8 ∗ U(B) &gt; U(lottery D) = 0.3 ∗ U(A) + 0.7 ∗ U(B). We get U(A) &lt; U(B) after simplification. The two formulas are actually contradicted, which indicates that there is no utility function that satisfies Cathy’s preferences.

</div>
</div>
</div>
