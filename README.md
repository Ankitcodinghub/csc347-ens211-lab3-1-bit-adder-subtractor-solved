# csc347-ens211-lab3-1-bit-adder-subtractor-solved
**TO GET THIS SOLUTION VISIT:** [CSC347-ENS211 Lab3-1-bit Adder/Subtractor Solved](https://www.ankitcodinghub.com/product/csc347-ens211-lab3-1-bit-adder-subtractor-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94093&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC347-ENS211 Lab3-1-bit Adder\/Subtractor Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<strong>Lab</strong><strong> 3 1-bit Adder/Subtractor </strong>

The objective of this lab is to build a circuit to perform 1-bit addition/subtraction.

<strong>Chips: </strong>

<strong>&nbsp; </strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;74HCT<strong>08</strong> Quad 2-input AND gate, 74HCT<strong>32</strong> Quad 2-input OR gate, 74HCT<strong>04</strong> inverter, 74HCT<strong>86</strong> Quad 2-input XOR gate

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/07/999.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/07/872.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/07/281.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

<strong>Procedure</strong>

Build a circuit with AND, OR and XOR gates to perform 1-bit addition.

<ol>
<li>Derive the truth table for 1-bit full adder:</li>
</ol>
A circuit that adds a column of three bits is called a full-adder. We can design such a circuit by making a table listing the outputs for all possible input combinations. Note that in each column there is a sum bit which is put at the bottom and a carry bit that is taken to the next column. So we need to specify two output bits for each input combination. Let us call the two data bits A and B. (These are the bits in the two bottom rows of the sum, corresponding to the given numbers to be added.) We call the input carry Cin. The output bits will be S for the sum bit and Cout for the output carry. The summation is shown symbolically below, together with the table giving the outputs for each input combination. Each row of the table is filled in simply by writing in binary the sum of the three bits A + B + Cin, using 0 = (00)<sub>2</sub>, 1 = (01)<sub> 2</sub>, 2 = (10)<sub> 2</sub>, and 3 = (11)<sub> 2</sub>.

<table>
<tbody>
<tr>
<td width="30">A</td>
<td width="25">B</td>
<td width="38">Cin</td>
<td width="46">Cout</td>
<td width="42">S</td>
</tr>
<tr>
<td width="30">0</td>
<td width="25">0</td>
<td width="38">0</td>
<td width="46">0</td>
<td width="42">0</td>
</tr>
<tr>
<td width="30">0</td>
<td width="25">0</td>
<td width="38">1</td>
<td width="46">0</td>
<td width="42">1</td>
</tr>
<tr>
<td width="30">0</td>
<td width="25">1</td>
<td width="38">0</td>
<td width="46">0</td>
<td width="42">1</td>
</tr>
<tr>
<td width="30">0</td>
<td width="25">1</td>
<td width="38">1</td>
<td width="46">1</td>
<td width="42">0</td>
</tr>
<tr>
<td width="30">1</td>
<td width="25">0</td>
<td width="38">0</td>
<td width="46">0</td>
<td width="42">1</td>
</tr>
<tr>
<td width="30">1</td>
<td width="25">0</td>
<td width="38">1</td>
<td width="46">1</td>
<td width="42">0</td>
</tr>
<tr>
<td width="30">1</td>
<td width="25">1</td>
<td width="38">0</td>
<td width="46">1</td>
<td width="42">0</td>
</tr>
<tr>
<td width="30">1</td>
<td width="25">1</td>
<td width="38">1</td>
<td width="46">1</td>
<td width="42">1</td>
</tr>
</tbody>
</table>
&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<ol start="2">
<li>Write the Boolean functions for Cout and S based on the truth table (sum of minterms):</li>
</ol>
Cout&nbsp;&nbsp; =&nbsp; A’BCin+AB’Cin+ABCin’+ABCin

S&nbsp; = A’B’Cin+A’BCin’+AB’Cin’+ABCin

<ol start="3">
<li>Write the Boolean functions for Cout and S based on the given logic diagram (simplified functions):</li>
</ol>
Cout&nbsp; =&nbsp; AB+(A⊕B)(Cin)

S&nbsp; = (A⊕B) ⊕Cin

<ol start="4">
<li>Circuit Construction on Tinkercad</li>
</ol>
The full-adder circuit diagram shown in the previous page uses two XOR gates, two AND gates, and one OR gate. The circuit can be built with one 7408 AND chip, one 7432 OR chip, and one 7486 XOR chip. DIP switches will be used to supply all three input logic levels A, B and Cin, and LEDs will be used to provide readout of the two output bits Cout and S.

<ol>
<li>Make a copy of the start kit from <a href="https://www.tinkercad.com/things/19XqriP2dMF">https://www.tinkercad.com/things/19XqriP2dMF</a> and rename the copy as “Lab 3 1-bit Adder/Subtractor” on Tinkercad Circuits dashboard.</li>
<li>Connect chips together according to the schematic diagram shown in the previous page.</li>
<li>Connect the inputs (A, B, Cin) to three switches, and the two outputs (Cout, S) to a pair of LEDs.</li>
<li>Press “Start Simulation”</li>
<li>Apply all eight combinations of logic LOW and HIGH levels to the three gate inputs using the DIP switches. Observe the two outputs, and record the results in a truth table, in the form of 0s and 1s. Verify if your table matches with the truth table shown in the first page.</li>
</ol>
&nbsp;

<ol start="5">
<li>Homework: Follow the same procedure for the 1-bit adder to build a 1-bit subtractor. Derive the truth table for 1-bit full subtractor (A- B – Bin), write down the functions, and build the subtractor using the given logic diagram.</li>
</ol>
<table>
<tbody>
<tr>
<td width="30">A</td>
<td width="25">B</td>
<td width="38">Bin</td>
<td width="46">Bout</td>
<td width="42">D</td>
</tr>
<tr>
<td width="30">0</td>
<td width="25">0</td>
<td width="38">0</td>
<td width="46">0</td>
<td width="42">0</td>
</tr>
<tr>
<td width="30">0</td>
<td width="25">0</td>
<td width="38">1</td>
<td width="46">1</td>
<td width="42">1</td>
</tr>
<tr>
<td width="30">0</td>
<td width="25">1</td>
<td width="38">0</td>
<td width="46">1</td>
<td width="42">1</td>
</tr>
<tr>
<td width="30">0</td>
<td width="25">1</td>
<td width="38">1</td>
<td width="46">1</td>
<td width="42">0</td>
</tr>
<tr>
<td width="30">1</td>
<td width="25">0</td>
<td width="38">0</td>
<td width="46">0</td>
<td width="42">1</td>
</tr>
<tr>
<td width="30">1</td>
<td width="25">0</td>
<td width="38">1</td>
<td width="46">0</td>
<td width="42">0</td>
</tr>
<tr>
<td width="30">1</td>
<td width="25">1</td>
<td width="38">0</td>
<td width="46">0</td>
<td width="42">0</td>
</tr>
<tr>
<td width="30">1</td>
<td width="25">1</td>
<td width="38">1</td>
<td width="46">1</td>
<td width="42">1</td>
</tr>
</tbody>
</table>
&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<strong><u>Submission Instructions:</u></strong>

<u>Lab work submission</u>

<ol>
<li>For each input combination, take a screenshot of your circuit.</li>
<li>Copy the link of your circuit for sharing.</li>
<li>On the Blackboard, click on Lab 3. Attach the 8 screenshots from Step 1 and paste the link from Step 2 into the Comments area, then hit Submit button.</li>
</ol>
<u>Lab report submission</u>

Lab report is needed for this lab. Please follow the guidelines and sample report on the Blackboard when you are writing your lab report. Click on <strong>Lab 3 Report Submission</strong> to submit your report. It is due one week after the lab is done.

<u>TESTING INPUT COMBINATIONS FOR ADDER:</u>

<u>https://www.tinkercad.com/things/gBXckLXPbDP-copy-of-csc-347-starter-kit/editel?sharecode=Fgs8tWlkZwnfxNLX6TlnRi6d18ig4ayYRGUeFaG48sA</u>

0+0+0=00

0+0+1=01

0+1+0=01

0+1+1=10

1+0+0=01

1+0+1=10

&nbsp;

1+1+0=10

1+1+1=11

<u>&nbsp;</u>
