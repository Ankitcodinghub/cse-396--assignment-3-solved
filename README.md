# cse-396--assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CSE 396- Assignment 3 Solved](https://www.ankitcodinghub.com/product/cse-396-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;72481&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;&nbsp; CSE 396- Assignment 3&nbsp;Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
In lecture this week, we finished everything needed to complete the conversion back from regex to a DFA algorithm. This required the introduction of nondeterminism, which is a relaxation on the DFA model. In comparison to the DFA model, we made some drastic changes: we can make transitions without reading input and the transition function maps to a (possibly empty) set of states instead of a single state. That said, computation still proceeds more or less the same. Instead of processing one state and one symbol, we need to consider a set of active states and individually see where each one transitions. With this in mind, we are able to complete the cycle with regex translating nicely to NFA models and then NFAs translating (not so nicely) to DFA models.

Problem 1.&nbsp; Complete the TopHat worksheet )

Problem 2. ( Consider the regex <em>r </em>= 11(0∪1)<sup>∗ </sup>∪(0∪1)<sup>∗</sup>0 that matches strings starting with 11 or ending with 0.

2(a) Using the process from lecture, convert <em>r </em>to an equivalent NFA <em>N</em>. Be sure to include all of the intermediary NFAs and the -arcs that are required. Note that this differs slightly from the textbook examples as we require every stage to produce a single final state on our diagram. You may use the following shortcut (only for) (0∪1)<sup>∗</sup>:

0,1

2(b) Convert your resulting NFA into an equivalent DFA using the process from lecture. You should omit any unreachable states. Note that this will not have hundreds of states that might be expected by the conversion process.

Problem 3. (6+2+2+6 points) For this problem, let Σ = {a<em>,</em>b}. Construct an NFA <em>N </em>= (<em>Q,</em>Σ<em>,δ,s,F</em>) and the NFA <em>N</em><sup>0 </sup>= (<em>Q,</em>Σ<em>,δ,s,Q </em>− <em>F</em>) such that there is a string <em>w </em>∈ Σ<sup>∗ </sup>such that <em>w </em>6∈ <em>L</em>(<em>N</em>) and <em>w </em>6∈ <em>L</em>(<em>N</em><sup>0</sup>). Provide the computation tree of each NFA given the input <em>w</em>. To answer this problem, you should (a) construct your NFA <em>N</em>, (b) draw the resulting NFA <em>N</em><sup>0</sup>, (c) state the string <em>w</em>, and (d) draw the two computation trees.

&nbsp;
