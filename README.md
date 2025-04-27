# isye-6740-homework-6-solved
**TO GET THIS SOLUTION VISIT:** [ISYE 6740 Homework 6 Solved](https://www.ankitcodinghub.com/product/isye-6740-homework-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;57026&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ISYE 6740 Homework 6  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (5 votes)    </div>
    </div>
As usual, please submit a report with sufficient explanation of your answers to each the questions, together with your code, in a zip folder.

<ol>
<li><strong>Neural networks. </strong>(20 points)
<ul>
<li>(10 points) Consider a neural networks for a binary classification using sigmoid function for eachunit. If the network has no hidden layer, explain why the model is equivalent to logistic regression.</li>
<li>(10 points) Consider a simple two-layer network in the lecture slides. Given the cost functionused to training the neural networks</li>
</ul>
</li>
</ol>
where <em>σ</em>(<em>x</em>) = 1<em>/</em>(1 + <em>e</em><sup>−<em>x</em></sup>) is the sigmoid function. Show the that the gradient is given by

<em>.</em>

where). Also find the gradient of <em>` </em>with respect to <em>α </em>and <em>β</em>.

<ol start="2">
<li><strong>Comparing SVM and simple neural networks. </strong>(40 points)</li>
</ol>
This question is to implement and compare <strong>SVM and simple neural networks </strong>for the same datasets we tried for the last homework. We suggest to use Scikit-learn, which is a commonly-used and powerful Python library with various machine learning tools. But you can also use other similar libraries in other programming languages of your choice to perform the tasks.

You may use a neural networks function sklearn.neural network with hidden layer sizes=(5, 2). Tune the step size so you have reasonable results. You may use svc and tune the penalty term <em>C </em>to get reasonable results.

<strong>Part One (Divorce classification/prediction). </strong>(20 points)

We will compare using the same dataset as the last homework, which is about participants who completed the personal information form and a divorce predictors scale.

The data is a modified version of the publicly available at https://archive.ics.uci.edu/ml/datasets/ Divorce+Predictors+data+set (by injecting noise so you will not replicate the results on uci website). There are 170 participants and 54 attributes (or predictor variables) that are all real-valued. The dataset <strong>q3.csv</strong>. The last column of the CSV file is label <em>y </em>(1 means “divorce”, 0 means “no divorce”). Each column is for one feature (predictor variable), and each row is a sample (participant). A detailed explanation for each feature (predictor variable) can be found at the website link above. Our goal is to build a classifier using training data, such that given a test sample, we can classify (or essentially predict) whether its label is 0 (“no divorce”) or 1 (“divorce”).

Build two classifiers using SVM and a simple neural networks. First random shuffle the data set. Then use the first 80% data for training and the remaining 20% for testing. If you use scikit-learn you can use train test split to split the dataset.

<ul>
<li>(15 points) Report testing accuracy for each of the two classifiers. Comment on their performance: which performs better and make a guess why it performs better in this setting.</li>
<li>(15 points) Use the first two features to train two new classifiers. Plot the data points and decisionboundary of each classifier. Comment on the difference between the decision boundary for the two classifiers. Please clearly represent the data points with different labels using different colors.</li>
</ul>
<strong>Part Two (Handwritten digits classification). </strong>(20 points) Repeat the above part (a) using the <strong>MNIST Data </strong>in our previous homework. Here, give “digit” 6 label <em>y </em>= 1, and give “digit” 2 label <em>y </em>= 0. All the pixels in each image will be the feature (predictor variables) for that sample (i.e., image). Our goal is to build classifiers such that given a new testing sample, we can tell it is a 2 or a 6. Using the first 80% of the samples for training and remaining 20% for testing. Report the classification accuracy on testing data, for each of the two classifiers. Comment on their performance: which performs better and make a guess why they perform better in this setting.

<ol start="3">
<li><strong>AdaBoost. </strong>(40 points)</li>
</ol>
Consider the following dataset, plotting in Figure 1. The first two coordinates represent the value of two features, and the last coordinate is the binary label of the data.

<em>X</em><sub>1 </sub>= (−1<em>,</em>0<em>,</em>+)<em>,X</em><sub>2 </sub>= (−0<em>.</em>5<em>,</em>0<em>.</em>5<em>,</em>+)<em>,X</em><sub>3 </sub>= (0<em>,</em>1<em>,</em>−)<em>,X</em><sub>4 </sub>= (0<em>.</em>5<em>,</em>1<em>,</em>−)<em>, X</em><sub>5 </sub>= (1<em>,</em>0<em>,</em>+)<em>,X</em><sub>6 </sub>= (1<em>,</em>−1<em>,</em>+)<em>,X</em><sub>7 </sub>= (0<em>,</em>−1<em>,</em>−)<em>,X</em><sub>8 </sub>= (0<em>,</em>0<em>,</em>−)<em>.</em>

In this problem, you will run through <em>T </em>= 3 iterations of AdaBoost with decision stumps (axis-aligned half planes) as weak learners.

<ul>
<li>(20 points) For each iteration <em>t </em>= 1<em>,</em>2<em>,</em>3, compute by hand (i.e., show all the calculation steps) and draw the decision stumps on Figure 1. Recall that <em>Z<sub>t </sub></em>is the normalization factor to ensure that the weights <em>D<sub>t </sub></em>sum to one. (<em>Hint: At each iteration, you may specify any reasonable decision rule h<sub>t </sub>as you would like.</em>)</li>
<li>(20 points) What is the training error of AdaBoost? Give a one-sentence reason for why AdaBoostoutperforms a single decision stump.</li>
</ul>
<table width="496">
<tbody>
<tr>
<td width="23">t</td>
<td width="26"><em><sub>t</sub></em></td>
<td width="29"><em>α<sub>t</sub></em></td>
<td width="30"><em>Z<sub>t</sub></em></td>
<td width="49"><em>D<sub>t</sub></em>(1)</td>
<td width="49"><em>D<sub>t</sub></em>(2)</td>
<td width="49"><em>D<sub>t</sub></em>(3)</td>
<td width="49"><em>D<sub>t</sub></em>(4)</td>
<td width="49"><em>D<sub>t</sub></em>(5)</td>
<td width="49"><em>D<sub>t</sub></em>(6)</td>
<td width="49"><em>D<sub>t</sub></em>(7)</td>
<td width="49"><em>D<sub>t</sub></em>(8)</td>
</tr>
<tr>
<td width="23">1

2

3
</td>
<td width="26"></td>
<td width="29"></td>
<td width="30"></td>
<td width="49"></td>
<td width="49"></td>
<td width="49"></td>
<td width="49"></td>
<td width="49"></td>
<td width="49"></td>
<td width="49"></td>
<td width="49"></td>
</tr>
</tbody>
</table>
Figure 1: A small dataset, for binary classification with AdaBoost.

Table 1: Values of AdaBoost parameters at each timestep.
