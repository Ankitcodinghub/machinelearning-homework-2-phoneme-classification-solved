# machinelearning-homework-2-phoneme-classification-solved
**TO GET THIS SOLUTION VISIT:** [MachineLearning Homework 2-Phoneme Classification Solved](https://www.ankitcodinghub.com/product/machinelearning-homework-2-phoneme-classification-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92712&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MachineLearning Homework 2-Phoneme Classification Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

</div>
</div>
</div>
</div>
<div class="page" title="Page 3"></div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
Task Introduction

Task: MulticlassClassification

Framewise phoneme prediction from speech.

What is a phoneme?

</div>
<div class="column">
Machine

M M M AH AH SH SH IH IH IH

</div>
<div class="column">
N N N

</div>
<div class="column">
N …

</div>
</div>
<div class="layoutArea">
<div class="column">
A unit of speech sound in a language that can serve to distinguish one word from the other.

<ul>
<li>● &nbsp;bat / pat , bad / bed</li>
<li>● &nbsp;Machine Learning → M AH SH IH N L ER N IH NG</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
Task Introduction

Data Preprocessing

</div>
</div>
<div class="layoutArea">
<div class="column">
a vector

</div>
</div>
<div class="layoutArea">
<div class="column">
39-dim MFCC

frame 80-dim filter bank …

</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
Task Introduction

Acoustic Features – MFCCs (Mel Frequency Cepstral Coefficients)

</div>
</div>
<div class="layoutArea">
<div class="column">
vector

</div>
<div class="column">
For more details,

please refer to Prof. Lin-Shan Lee’s [Introduction to Digital Speech Processing] Chap.7

&nbsp;

</div>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<div class="layoutArea">
<div class="column">
shape (11,39)

prev frames flatten

</div>
<div class="column">
label

</div>
</div>
<div class="layoutArea">
<div class="column">
More Information About the Data

Since each frame only contains 25 ms of speech, a single frame is unlikely to represent a complete phoneme

● Usually, a phoneme will span several frames ○ Hint: post-processing may help

<ul>
<li>● &nbsp;Concatenate the neighboring phonemes for training
<ul>
<li>○ &nbsp;In this HW, we concatenate the past and the future five
frames for training (total 11 frames)
</li>
<li>○ &nbsp;You may reshape the input (1,429) back to (11,39) to get
separated 11 frames
</li>
<li>○ &nbsp;Just remember that the label corresponds to the center
frame
</li>
</ul>
</li>
<li>● &nbsp;Finding testing labels or doing human labeling are strictly prohibited!
Introduction to Digital Speech Processing
</li>
</ul>
</div>
<div class="column">
future frames

reshape to (11,39)

</div>
</div>
<div class="layoutArea">
<div class="column">
shape (1,429) flatten 11 frames 11 * 39 = 429 dim

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
Dataset &amp; Data Format

● Dataset: TIMIT Acoustic-Phonetic Continuous Speech Corpus ○ Phonetically balanced for English

● Data Format (The TAs have already preprocessed the data)

timit_11/

<ul>
<li>– &nbsp;train_11.npy → training data (# of training frames, 11 x feature dim)</li>
<li>– &nbsp;train_label_11.npy → framewise phoneme label (0-38)</li>
<li>– &nbsp;test_11.npy → testing data (# of testing frames, 11 x feature dim)</li>
</ul>
● Acoustic features (39-dim MFCC)

<ul>
<li>○ &nbsp;Concatenate the past and the future five frames (feature dim = 11 x 39)</li>
<li>○ &nbsp;The phoneme label of each input corresponds to the center frame</li>
</ul>
● Using additional data is prohibited. Your final grade will be multiplied by 0.9!

</div>
</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="section">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Class Phoneme Example

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Class Phoneme Example

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Class Phoneme Example

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<ol start="0">
<li>0 &nbsp;iy beet</li>
<li>1 &nbsp;ih bit</li>
<li>2 &nbsp;eh bet</li>
<li>3 &nbsp;ae bat</li>
<li>4 &nbsp;ah but</li>
<li>5 &nbsp;uw boot</li>
<li>6 &nbsp;uh book</li>
<li>7 &nbsp;aa bob</li>
<li>8 &nbsp;ey bait</li>
<li>9 &nbsp;ay bite</li>
<li>10 &nbsp;oy boy</li>
<li>11 &nbsp;aw bout</li>
<li>12 &nbsp;ow boat</li>
</ol>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<ol start="13">
<li>13 &nbsp;l lay</li>
<li>14 &nbsp;r ray</li>
<li>15 &nbsp;y yacht</li>
<li>16 &nbsp;w way</li>
<li>17 &nbsp;er bird</li>
<li>18 &nbsp;m mom</li>
<li>19 &nbsp;n noon</li>
<li>20 &nbsp;ng sing</li>
<li>21 &nbsp;ch choke</li>
<li>22 &nbsp;jh joke</li>
<li>23 &nbsp;dh then</li>
<li>24 &nbsp;b bee</li>
<li>25 &nbsp;d day</li>
</ol>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<ol start="26">
<li>26 &nbsp;dx</li>
<li>27 &nbsp;g</li>
<li>28 &nbsp;p</li>
<li>29 &nbsp;t</li>
<li>30 &nbsp;k</li>
<li>31 &nbsp;z</li>
<li>32 &nbsp;v</li>
<li>33 &nbsp;f</li>
<li>34 &nbsp;th</li>
<li>35 &nbsp;s</li>
<li>36 &nbsp;sh</li>
<li>37 &nbsp;hh</li>
<li>38 &nbsp;sil</li>
</ol>
</div>
<div class="column">
muddy gay pea tea key zone van

fin thin sea she hay

silence/closure sounds

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 10">
<div class="section">
<div class="layoutArea">
<div class="column">
Sample Code

Colab Link:

https://colab.research.google.com/github/ga642381/ML2021-Spring/blob/main/HW 02/HW02-1.ipynb

● Simple baseline

○ You should able to pass the simple baseline using the sample code provided.

● Strong baseline

<ul>
<li>○ &nbsp;Model architecture (layers? dimension? activation function?)</li>
<li>○ &nbsp;Training (batch size? optimizer? learning rate? epoch?)</li>
<li>○ &nbsp;Tips (batch norm? dropout? regularization?)</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="section">
<div class="layoutArea">
<div class="column">
Grading (8pt/10pt)

<ul>
<li>● &nbsp;(4pt) Submit code to NTU COOL</li>
<li>● &nbsp;(1pt) Public simple baseline</li>
<li>● &nbsp;(1pt) Public strong baseline</li>
<li>● &nbsp;(1pt) Private simple baseline</li>
<li>● &nbsp;(1pt) Private strong baseline</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="section">
<div class="layoutArea">
<div class="column">
Grading — Kaggle

</div>
</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="section">
<div class="layoutArea">
<div class="column">
Bonus (0.5pt)

<ul>
<li>● &nbsp;If you get full marks in this part, we will make your code public to the class.</li>
<li>● &nbsp;In this case, if you also submit a PDF report briefly describing your methods (&lt;100 words in English), you get a bonus of 0.5 pt.

(your report will also be available to all students)</li>
<li>● &nbsp;Report template</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 14">
<div class="section">
<div class="layoutArea">
<div class="column">
Kaggle Submission

Kaggle Link: https://www.kaggle.com/c/ml2021spring-hw2

<ul>
<li>● &nbsp;Displayed name: &lt;student ID&gt;_&lt;anything&gt;
<ul>
<li>○ &nbsp;e.g. b06901020_puipui</li>
<li>○ &nbsp;For auditing, don’t put your student ID in your displayed name.</li>
</ul>
</li>
<li>● &nbsp;Submission format: .csv file</li>
<li>● &nbsp;Evaluation metric: accuracy</li>
<li>● &nbsp;Submission deadline:</li>
</ul>
○ 2021/04/02 23:59 (UTC+8)

</div>
</div>
</div>
</div>
<div class="page" title="Page 15">
<div class="section">
<div class="layoutArea">
<div class="column">
Kaggle Submission

<ul>
<li>● &nbsp;You may submit up to 5 results each day (UTC).</li>
<li>● &nbsp;Up to 2 submissions will be considered for the private leaderboard.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
remember to select 2 results for your final scores before the competition ends!

</div>
</div>
</div>
</div>
<div class="page" title="Page 16">
<div class="section">
<div class="layoutArea">
<div class="column">
Code Submission

<ul>
<li>● &nbsp;Compress your code and report, then submit it to NTU COOL. &lt;student ID&gt;_hw2.zip
<pre>                          e.g. b06901999_hw2.zip
</pre>
</li>
<li>● &nbsp;We can only see your last submission.</li>
<li>● &nbsp;Do not submit your model or dataset.</li>
<li>● &nbsp;If your code is not reasonable, your final grade will be multiplied by 0.9!</li>
<li>● &nbsp;Submission deadline:</li>
</ul>
○ 2021/04/04 23:59 (UTC+8)

</div>
</div>
</div>
</div>
<div class="page" title="Page 17">
<div class="section">
<div class="layoutArea">
<div class="column">
Code Submission

● Your .zip file should include only

<ul>
<li>○ &nbsp;Code: either .py or .ipynb</li>
<li>○ &nbsp;Report: .pdf (only for those who got 8 points in part one)
● Example:
</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 18">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
2-2 Hessian Matrix

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 19">
<div class="section">
<div class="layoutArea">
<div class="column">
Task Introduction

Task: Hessian Matrix

Imagine we are training a neural network, and we try to find out whether the model reaches a local minima-like point, saddle point, or none of the above. We can make our decision by calculating the Hessian matrix.

What is Hessian?

Hessian is the second order partial derivatives of a model. It is highly recommended to watch the lecture video before starting this part.

</div>
</div>
</div>
</div>
<div class="page" title="Page 20">
<div class="section">
<div class="layoutArea">
<div class="column">
Task Introduction

The target function in this task is a one-variable sinc function.

You will get

<ul>
<li>● &nbsp;a model checkpoint trained by TA,</li>
<li>● &nbsp;a batch of training data,</li>
<li>● &nbsp;a loss function.</li>
</ul>
You will calculate the Hessian matrix and make the decision accordingly.

</div>
</div>
</div>
</div>
<div class="page" title="Page 21">
<div class="section">
<div class="layoutArea">
<div class="column">
Gradient Norm / Minimum Ratio

1. Gradient Norm

In a normal training process, we rarely have gradients equal to zero. In this homework, we regard those gradient norm less than 1e-3 as zero.

2. Minimum Ratio

For an ideal local minima, all the eigenvalues of the hessian matrix are greater than zero. We define the proportion of positive eigenvalues as minimum ratio.

In this homework, if minimum ratio is greater than 0.5 and gradient norm is less than 1e-3, then we assume that the model is at “local minima like”.

</div>
</div>
</div>
</div>
<div class="page" title="Page 22">
<div class="section">
<div class="layoutArea">
<div class="column">
Gradient Norm / Minimal Ratio

In this homework, we assume that

<ul>
<li>● &nbsp;gradient norm &lt; 1e-3 and minimum ratio &gt; 0.5 =&gt; local minima like,</li>
<li>● &nbsp;gradient norm &lt; 1e-3 and minimum ratio &lt;= 0.5 =&gt; saddle point,</li>
<li>● &nbsp;gradient norm &gt;= 1e-3 =&gt; none of the above.</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 23">
<div class="section">
<div class="layoutArea">
<div class="column">
Important Notice

<ul>
<li>● &nbsp;You don’t need to and shouldn’t change any part of the code.</li>
<li>● &nbsp;You can only use colab to run the code. Otherwise, your result might
differ due to environmental issue.
</li>
<li>● &nbsp;You will get a different checkpoint according to your student ID, so please
make sure to fill in your student ID in the sample code correctly.
</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 24">
<div class="section">
<div class="layoutArea">
<div class="column">
Sample Code

Colab Link:

https://colab.research.google.com/github/ga642381/ML2021-Spring/blob/main/HW 02/HW02-2.ipynb

<ul>
<li>● &nbsp;After executing the sample code, you should get a result like this.</li>
<li>● &nbsp;Notice that each student will get a different answer, so your answer may
differ from the example.
</li>
<li>● &nbsp;Choose your answer from local minima like, saddle point, or none of the above.</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 25">
<div class="section">
<div class="layoutArea">
<div class="column">
Grading (2pt/10pt)

● (2pt) Correct answer.

</div>
</div>
</div>
</div>
<div class="page" title="Page 26">
<div class="section">
<div class="layoutArea">
<div class="column">
NTU COOL Submission

<ul>
<li>● &nbsp;After you choose your answer, submit it to NTU COOL.</li>
<li>● &nbsp;You can change your answer multiple times before the deadline.</li>
<li>● &nbsp;Submission deadline:</li>
</ul>
○ 2021/04/02 23:59 (UTC+8)

</div>
</div>
</div>
</div>
<div class="page" title="Page 27">
<div class="section">
<div class="layoutArea">
<div class="column">
Deadlines

● 2-1

<ul>
<li>○ &nbsp;Kaggle: 2021/04/02 23:59 (UTC+8)</li>
<li>○ &nbsp;NTU COOL: 2021/04/04 23:59 (UTC+8)
● 2-2
</li>
<li>○ &nbsp;NTU COOL: 2021/04/02 23:59 (UTC+8)</li>
</ul>
</div>
</div>
</div>
</div>
