Download Link: https://assignmentchef.com/product/solved-cse-5243-homework-3
<br>
<ul>

 <li>Please work on this assignment as an individual, not in a group.</li>

 <li>A 15% penalty all homework handed in up to 24 hours late; homework will not be accepted more than 24 hours late</li>

 <li>Show your work</li>

</ul>

<strong><em>Question #1</em></strong>: Given the below confusion matrix for classifier <em>C, </em>compute the accuracy rate, error rate, true positive, false positive, precision and F-measure.

<table width="277">

 <tbody>

  <tr>

   <td width="53"> </td>

   <td colspan="3" width="153"><strong>Predicted Class</strong></td>

   <td width="71"> </td>

  </tr>

  <tr>

   <td width="53"> </td>

   <td width="52"> </td>

   <td width="53">+</td>

   <td width="48">–</td>

   <td width="71">Total</td>

  </tr>

  <tr>

   <td width="53"><strong>Actual</strong></td>

   <td width="52">+</td>

   <td width="53">350</td>

   <td width="48">122</td>

   <td width="71">472</td>

  </tr>

  <tr>

   <td width="53"><strong>Class </strong></td>

   <td width="52">–</td>

   <td width="53">344</td>

   <td width="48">670</td>

   <td width="71">1014</td>

  </tr>

  <tr>

   <td width="53"> </td>

   <td width="52">Total</td>

   <td width="53">694</td>

   <td width="48">792</td>

   <td width="71">1486</td>

  </tr>

 </tbody>

</table>

<strong><em>Question #2</em></strong>: Consider the training examples shown in the following table for a binary classification problem and answer the following questions:

<table width="324">

 <tbody>

  <tr>

   <td width="65"> </td>

   <td width="65"><strong>a</strong><strong><sub>1</sub></strong></td>

   <td width="65"><strong>a</strong><strong>2</strong></td>

   <td width="65"><strong>a</strong><strong>3</strong></td>

   <td width="65"><strong>Class</strong></td>

  </tr>

  <tr>

   <td width="65"><strong>1</strong></td>

   <td width="65">T</td>

   <td width="65">T</td>

   <td width="65">1.0</td>

   <td width="65">+</td>

  </tr>

  <tr>

   <td width="65"><strong>2</strong></td>

   <td width="65">T</td>

   <td width="65">T</td>

   <td width="65">6.0</td>

   <td width="65">+</td>

  </tr>

  <tr>

   <td width="65"><strong>3</strong></td>

   <td width="65">T</td>

   <td width="65">F</td>

   <td width="65">5.0</td>

   <td width="65">–</td>

  </tr>

  <tr>

   <td width="65"><strong>4</strong></td>

   <td width="65">F</td>

   <td width="65">F</td>

   <td width="65">4.0</td>

   <td width="65">+</td>

  </tr>

  <tr>

   <td width="65"><strong>5</strong></td>

   <td width="65">F</td>

   <td width="65">T</td>

   <td width="65">7.0</td>

   <td width="65">–</td>

  </tr>

  <tr>

   <td width="65"><strong>6</strong></td>

   <td width="65">F</td>

   <td width="65">T</td>

   <td width="65">3.0</td>

   <td width="65">–</td>

  </tr>

  <tr>

   <td width="65"><strong>7</strong></td>

   <td width="65">F</td>

   <td width="65">F</td>

   <td width="65">8.0</td>

   <td width="65">–</td>

  </tr>

  <tr>

   <td width="65"><strong>8</strong></td>

   <td width="65">T</td>

   <td width="65">F</td>

   <td width="65">7.0</td>

   <td width="65">+</td>

  </tr>

  <tr>

   <td width="65"><strong>9</strong></td>

   <td width="65">F</td>

   <td width="65">T</td>

   <td width="65">5.0</td>

   <td width="65">–</td>

  </tr>

 </tbody>

</table>

<ol>

 <li>What is the entropy of this collection of training examples with respect to the class attribute?</li>

 <li>What are the information gains for attributes a<sub>1</sub> and a<sub>2</sub> relative to these training examples?</li>

 <li>For a<sub>3</sub>, which is a continuous attribute, find the binary split which maximizes the information gain.</li>

 <li>If you were building a decision tree with a single (binary) split, using the <em>information gain</em> measure, which attribute would you split on? Draw the decision tree and show the number of positive and negative examples in each leaf node.</li>

 <li>Would your choice of optimal split in part d) change if you used the <em>gain ratio</em> instead of the information gain?</li>

</ol>

<strong><em>Question #3</em></strong>: Using the dataset given in the table below, build a 2-level decision tree [one split from the root node, followed by 1 additional split from each child node] using the Gini index as the splitting criteria. You should use multiway splits for each attribute. Draw the decision tree and show the number of class C0 and C1 records in each leaf node. Show your work by computing the Gini index of the possible splits. You do not need to worry about pruning the tree that you’ve built.

<strong><em>Question #4</em></strong>: You have built a decision tree model and would like to estimate the generalization performance of the model. Before building the model, you set aside a test dataset with 1200 records. The predicted class label for each of the 1200 records is calculated, and the results are summarized in the table below. The number of actual positive and negative class examples are aggregated for each score range based on the posterior probability P(+ | x). For example, there are a total of 131 test records with P(+ | x) &gt;= 0.9,  118 of which are actually positive and 13 are actually negative.

<ol>

 <li>Given a decision threshold of 0.5, write the confusion matrix and calculate the accuracy of the model.</li>

 <li>Change the decision threshold to 0.7, write the confusion matrix and calculate the accuracy. Compare the TPR and FPR of this choice to those obtained in part a.</li>

 <li>Using the data in the table, draw the ROC curve. The curve should have 10 points, one for each row in the table.</li>

</ol>

Table for Exercise #4

<table width="537">

 <tbody>

  <tr>

   <td width="110"><strong>Score Range</strong><strong>P(+ | x)</strong></td>

   <td width="142"># + Class Examples in the score range</td>

   <td width="135"># – Class Examples in the score range</td>

   <td width="150">Total Examples in each score range</td>

  </tr>

  <tr>

   <td width="110"><strong>[0.9 – 1]</strong></td>

   <td width="142">118</td>

   <td width="135">13</td>

   <td width="150">131</td>

  </tr>

  <tr>

   <td width="110"><strong>[0.8 – 0.9)</strong></td>

   <td width="142">94</td>

   <td width="135">24</td>

   <td width="150">118</td>

  </tr>

  <tr>

   <td width="110"><strong>[0.7 – 0.8)</strong></td>

   <td width="142">81</td>

   <td width="135">35</td>

   <td width="150">116</td>

  </tr>

  <tr>

   <td width="110"><strong>[0.6 – 0.7)</strong></td>

   <td width="142">74</td>

   <td width="135">42</td>

   <td width="150">116</td>

  </tr>

  <tr>

   <td width="110"><strong>[0.5 – 0.6)</strong></td>

   <td width="142">51</td>

   <td width="135">48</td>

   <td width="150">99</td>

  </tr>

  <tr>

   <td width="110"><strong>[0.4 – 0.5)</strong></td>

   <td width="142">34</td>

   <td width="135">62</td>

   <td width="150">96</td>

  </tr>

  <tr>

   <td width="110"><strong>[0.3 – 0.4)</strong></td>

   <td width="142">25</td>

   <td width="135">99</td>

   <td width="150">124</td>

  </tr>

  <tr>

   <td width="110"><strong>[0.2 – 0.3)</strong></td>

   <td width="142">11</td>

   <td width="135">105</td>

   <td width="150">116</td>

  </tr>

  <tr>

   <td width="110"><strong>[0.1 – 0.2)</strong></td>

   <td width="142">9</td>

   <td width="135">122</td>

   <td width="150">131</td>

  </tr>

  <tr>

   <td width="110"><strong>[0 – 0.1)</strong></td>

   <td width="142">3</td>

   <td width="135">150</td>

   <td width="150">153</td>

  </tr>

  <tr>

   <td width="110"><strong>Total</strong></td>

   <td width="142">500</td>

   <td width="135">700</td>

   <td width="150">1200</td>

  </tr>

 </tbody>

</table>

Note that some problems are taken from the textbook <em>Introduction to Data Mining.</em>