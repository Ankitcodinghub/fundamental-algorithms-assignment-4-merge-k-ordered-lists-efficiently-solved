# fundamental-algorithms-assignment-4-merge-k-ordered-lists-efficiently-solved
**TO GET THIS SOLUTION VISIT:** [Fundamental-Algorithms Assignment 4-Merge k Ordered Lists Efficiently Solved](https://www.ankitcodinghub.com/product/fundamental-algorithms-assignment-4-merge-k-ordered-lists-efficiently-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97159&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Fundamental-Algorithms Assignment 4-Merge k Ordered Lists Efficiently Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="section">
<div class="layoutArea">
<div class="column">
Merge k Ordered Lists Efficiently

You are required to implement c​orrectly and e​fficiently an O(nl​ogk​) method for m​erging k sorted sequences,​where n is the total number of elements. (Hint: use a heap, see seminar no. 2 notes).

Implementation requirements:

● Use linked lists to represent the k sorted sequences and the output sequence

Input: k lists of numbers &gt;,

</div>
</div>
<div class="layoutArea">
<div class="column">
​

</div>
</div>
<div class="layoutArea">
<div class="column">
Output: a permutation of the union of the input sequences: &lt; &gt;

Thresholds

7 Adapt heap operations to work on new structure (list_index, key); use min­HEAP

<ol start="9">
<li>9 &nbsp;Correct and complete algorithm implementation, with demo on a small­sized input</li>
<li>10 &nbsp;Evaluation, interpretations, discussion</li>
</ol>
Evaluation

! Before you start to work on the algorithms evaluation code, make sure you have a correct

algorithm! You will have to show your algorithm works on a small­sized input (e.g. k=4, n=20).

We will make the average case analysis of the algorithm. Remember that, in the average case, you have to repeat the measurements several times. Since both k​and n​may vary, we will make each analysis in turn:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Threshol d

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Requirements

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Generate k random sorted lists, having n elements in total (n and k given as parameters); merge 2 lists

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
<ol>
<li>Choose, in turn, 3 constant values for k (k1=5, k2=10, k3=100); generate k r​andom sorted lists for each value of k so that the combined number of elements in all the lists (n) varies between 100 and 10000, with a maximum increment of 400 (we suggest 100); run the algorithm for all values of n (for each value of k); generate a chart that represents the sum of assignments and comparisons done by the merging algorithm for each value of k as a curve (total 3 curves).</li>
<li>Set n = 10.000; the value of k must vary between 10 and 500 with an increment of 10; generate k r​andom sorted lists for each value of k so that the combined number of elements in all the lists is 10000; test the merging algorithm for each value of k and generate a chart that represents the sum of assignments and comparisons as a curve.</li>
<li>Interpret your charts.</li>
</ol>
</div>
</div>
</div>
</div>
