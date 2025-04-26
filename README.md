# cs6260-homework-2--applied-cryptography-solved
**TO GET THIS SOLUTION VISIT:** [CS6260 Homework 2- Applied Cryptography Solved](https://www.ankitcodinghub.com/product/homework-2-cs6260-applied-cryptography-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118564&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6260 Homework 2- Applied Cryptography Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<em>Objectives: Understanding PRF and IND-CPA definitions, proving schemes insecure.</em>

Notation for problems below:

<ul>
<li><em>x </em>⊕ <em>y </em>refers to the XOR of <em>x </em>and <em>y</em></li>
<li><em>x </em>∥ <em>y </em>refers to concatenation of <em>x </em>and <em>y</em></li>
<li><em>x </em>refers the bitwise complement of <em>x</em></li>
</ul>
<h1>Problem 2.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (10 points)</h1>
Let <em>F </em>: {0<em>,</em>1}<em><sup>k </sup></em>×{0<em>,</em>1}<em><sup>m </sup></em>7→{0<em>,</em>1}<em><sup>n </sup></em>be a secure PRF. Prove that the function family <em>F</em><sub>1 </sub>: {0<em>,</em>1}<em><sup>k </sup></em>×{0<em>,</em>1}<sup>2<em>m </em></sup>7→{0<em>,</em>1}<sup>2<em>n </em></sup>specified for all <em>x</em><sub>1</sub><em>,x</em><sub>2 </sub>∈{0<em>,</em>1}<em><sup>m </sup></em>and all <em>K </em>∈{0<em>,</em>1}<em><sup>k </sup></em>below is not a secure PRF:

<em>F</em><sub>1</sub>(<em>K,x</em><sub>1 </sub>∥ <em>x</em><sub>2</sub>) = <em>F</em>(<em>K,x</em><sub>1</sub>) ∥ <em>F</em>(<em>K,x</em><sub>1 </sub>⊕ <em>x</em><sub>2</sub>)

<h1>Problem 2.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (10 points)</h1>
Let <em>E </em>: {0<em>,</em>1}<em><sup>k </sup></em>×{0<em>,</em>1}<em><sup>m </sup></em>7→ {0<em>,</em>1}<em><sup>m </sup></em>be a blockcipher known to be a secure PRF. Prove that the function family <em>F</em><sub>2 </sub>: {0<em>,</em>1}<em><sup>k </sup></em>×{0<em>,</em>1}<sup>2<em>m </em></sup>7→ {0<em>,</em>1}<em><sup>m </sup></em>specified for all <em>x</em><sub>1</sub><em>,x</em><sub>2 </sub>∈{0<em>,</em>1}<em><sup>m </sup></em>and all <em>K </em>∈{0<em>,</em>1}<em><sup>k </sup></em>below is not a secure PRF:

<em>F</em><sub>2</sub>(<em>K,x</em><sub>1 </sub>∥ <em>x</em><sub>2</sub>) = <em>E</em>(<em>K,E</em>(<em>K,x</em><sub>2</sub>)) ⊕ <em>x</em><sub>1</sub>

<h1>Problem 2.3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (10 points)</h1>
The CBC-Chain mode of operation is a CBC variant in which the IV that is used for the very first message to be encrypted is random, while the IV used for each subsequent encrypted message is the last block of ciphertext that was generated.

Let <em>E </em>: {0<em>,</em>1}<em><sup>k </sup></em>×{0<em>,</em>1}<em><sup>l </sup></em>7→ {0<em>,</em>1}<em><sup>l </sup></em>be a block cipher. Then CBC-Chain mode is defined as) with a message space the set of messages whose length is a multiple of <em>l </em>bits, keyspace {0<em>,</em>1}<em><sup>k </sup></em>and encryption and decryption algorithms as follows:

Lecturer: Alexandra Boldyreva&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1 Homework 2 CS6260: Applied Cryptography

Algorithm E<em><sub>K</sub></em>(<em>M</em>):Algorithm D<em><sub>K</sub></em>(<em>C</em>): static <em>IV </em>←−{<sup>$&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sup>0<em>,</em>1<em>,…,</em>2<em><sup>l </sup></em>− 1}Break <em>C </em>into <em>l</em>-bit blocks:

Break <em>M </em>into <em>l</em>-bit blocks: <em>M</em><sub>1 </sub>∥ <em>M</em><sub>2 </sub><em>… </em>∥ <em>M<sub>n</sub>C</em>0 ∥ <em>C</em>1 ∥ <em>… </em>∥ <em>C</em><em>n</em>

<em>C</em><sub>0 </sub>← <em>IV</em>For <em>i </em>= 1<em>,…,n </em>do

For <em>i </em>= 1<em>,…,n </em>do<em>M<sub>i </sub></em>← <em>E<sub>K</sub></em><sup>−1</sup>(<em>C<sub>i</sub></em>) ⊕ <em>C<sub>i</sub></em><sub>−1</sub>

<em>C<sub>i </sub></em>← <em>E<sub>K</sub></em>(<em>C<sub>i</sub></em><sub>−1 </sub>⊕ <em>M<sub>i</sub></em>)EndFor

EndForReturn <em>M</em><sub>1 </sub>∥ <em>…M<sub>n</sub></em>

<em>IV </em>← <em>C<sub>n</sub></em>

Return <em>C</em><sub>0 </sub>∥ <em>C</em><sub>1 </sub>∥ <em>… </em>∥ <em>C<sub>n</sub></em>

Show that SE is not IND-CPA secure, regardless of how secure <em>E </em>is.

<h1>Problem 2.4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (10 points)</h1>
An IND-CPA secure encryption scheme might not conceal identities, in the following sense: given a pair of ciphertexts <em>C,C</em><sup>′ </sup>for equal-length messages, it might be “obvious” if the ciphertexts were encrypted using the same random key or were encrypted using two different random keys. Demonstrate an example of a (plausibly) IND-CPA secure encryption scheme that has this property of being “identity-revealing”. You do not have to prove that the scheme is IND-CPA secure.

Lecturer: Alexandra Boldyreva&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2
