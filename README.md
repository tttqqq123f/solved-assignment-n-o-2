Download Link: https://assignmentchef.com/product/solved-assignment-n-o-2
<br>
Applied Generalized Linear models

Task 1                                                                                                          3 points

The following table contains the estimates of a logistic regression model.

<table width="433">

 <tbody>

  <tr>

   <td width="43"></td>

   <td width="57"></td>

   <td width="51"></td>

   <td width="57"></td>

   <td width="65"></td>

   <td width="40"></td>

   <td width="120">95% C.I. for OR</td>

  </tr>

  <tr>

   <td width="43"></td>

   <td width="57">Est.</td>

   <td width="51">s.e.</td>

   <td width="57">z</td>

   <td width="65">p-value</td>

   <td width="40">OR</td>

   <td width="120">lower       higher</td>

  </tr>

  <tr>

   <td width="43"><em>X</em><sub>1</sub></td>

   <td width="57">-0.868</td>

   <td width="51"></td>

   <td width="57">-2.365</td>

   <td width="65">0.018</td>

   <td width="40"></td>

   <td width="120">0.205         0.865</td>

  </tr>

  <tr>

   <td width="43"><em>X</em><sub>2</sub></td>

   <td width="57">2.404</td>

   <td width="51">0.601</td>

   <td width="57">4.000</td>

   <td width="65"><em>&lt;</em>0.001</td>

   <td width="40"></td>

   <td width="120"></td>

  </tr>

  <tr>

   <td width="43"><em>X</em><sub>3</sub></td>

   <td width="57"></td>

   <td width="51"></td>

   <td width="57"></td>

   <td width="65"><em>&lt;</em>0.001</td>

   <td width="40"></td>

   <td width="120">0.010         0.074</td>

  </tr>

 </tbody>

</table>

Fill in the missing information

(Please report formulas and computation.)

<h2>Task 2                                                                                                          3 points</h2>

During the lecture, we have considered the three systems of hypotheses for the parameters of the MNRM:

– <em>H</em><sub>0 </sub>: <em>β<sub>jm </sub></em>= 0       vs.     <em>H</em><sub>1 </sub>: <em>β<sub>jm </sub></em>6= 0

<table width="459">

 <tbody>

  <tr>

   <td width="220">– <em>H</em>0 : <em>β</em><em>j</em>1 = <em>… </em>= <em>β</em><em>j</em>(<em>M</em>−1) = 0</td>

   <td width="34">vs.</td>

   <td width="205"><em>H</em><sub>1 </sub>: at least one <em>β<sub>jm </sub></em>6= 0<em>, </em>∀<em>m</em></td>

  </tr>

  <tr>

   <td width="220">– <em>H</em>0 : <em>β</em><em>j</em>1 = <em>… </em>= <em>β</em><em>j</em>(<em>M</em>−1) = 0</td>

   <td width="34">vs.</td>

   <td width="205"><em>H</em><sub>1 </sub>: at least one <em>β<sub>jm </sub></em>∀<em>j,m</em></td>

  </tr>

 </tbody>

</table>

Could you specify another pair of hypotheses <em>H</em><sub>0 </sub>and <em>H</em><sub>1 </sub>for the parameters of the MNRM that we might want to test? Justify the answer.

(You have only to define <em>H</em><sub>0 </sub>and <em>H</em><sub>1</sub>. Defining the statistic and the rejection region of the test is not required!)

<h2>Task 3                                                                                                          8 points</h2>

The website <em>blablabla.com </em>sells magazine subscriptions. The related company is going to plan a large e-mail marketing campaign. All of the e-mails that will be sent will go to customers that have previously bought a magazine subscription at <em>blablabla.com </em>and who have not opted out of receiving e-mails.

The magazines advertised in each e-mail will be automatically selected for each customer when the e-mail is generated in order to maximize the probability that the customer will buy. The website <em>blablabla.com </em>will only include ads for three magazines in each e-mail in a row at the top of the message so that it is likely that the ads will appear in the e-mail preview (and therefore actually be viewed without the receiver actually having to open the e-mail). Moreover, the managers believe that including more ads is ineffective.

To evaluate the efficacy of the campaign, the company run an experiment. They sent 673 e-mails to customers containing the ad for the “Art with you” magazine and recorded whether or not the customer purchased this magazine.

The company has also collected data on the customers by matching the information provided by third party data (which can be purchased from data sources such as the credit scoring agencies) and the recipient of the e-mails when he/she made a purchase at <em>blablabla.com</em>.

The data set magazine.cvs contains the following information:

<ul>

 <li>Purchased “Art with you” magazine (Buy = 1 if purchased “Art with you”, 0 otherwise)</li>

 <li>Household Income (Income; rounded to the nearest 1<em>,</em>000<em>.</em>00)</li>

 <li>Gender (IsFemale = 1 if the person is female, 0 otherwise)</li>

 <li>Marital Status (IsMarried = 1 if married, 0 otherwise)</li>

 <li>College Educated (HasCollege = 1 if has one or more years of college education, 0 otherwise)</li>

 <li>Employed in a Profession (IsProfessional = 1 if employed in a profession, 0 otherwise)</li>

 <li>Retired (IsRetired = 1 if retired, 0 otherwise)</li>

 <li>Not employed (Unemployed = 1 if not employed, 0 otherwise)</li>

 <li>Length of Residency in Current City (ResLength; in years)</li>

 <li>Dual Income if Married (Dual = 1 if dual income, 0 otherwise)</li>

 <li>Children (Minors = 1 if children under 18 are in the household, 0 otherwise)</li>

 <li>Home ownership (Own = 1 if own residence, 0 otherwise)</li>

 <li>Resident type (House = 1 if residence is a single family house, 0 otherwise)</li>

 <li>Race (White = 1 if race is white, 0 otherwise)</li>

 <li>Language (English = 1 if language is English, 0 otherwise)</li>

 <li>Previously purchased an art magazine (PrevArt = 1 if previously purchased an art magazine, 0 otherwise).</li>

 <li>Previously purchased a cinema magazine (PrevCin = 1 if previously purchased a cinema magazine)</li>

 <li>Estimate a logistic regression model, with Buy as the dependent variable and Gender, Not Employed, Income and Own as explanatory variables. Is there any explanatory variable you would remove from the model? On the basis of which test? Remove the variable(s) and named the resulting model as Model 1.</li>

 <li>Add to Model 1 the variables PrevArt and PrevCinema. Name the resulting model as Model2. Compare Model 1 and Model 2 using an appropriate test and comment on the results.</li>

 <li>The data set includes many potential explanatory variables. Automatic procedures to select the “best” model are implemented in any software. One of this procedure is called “backward elimination” and performs the following steps:</li>

</ul>

Step 0 The binary logistic regression model including all the potential explanatory variables is fitted and the likelihood <em>L</em><sup>0 </sup>of the full model is computed.

Step 1 i) All the possible <em>p </em>models obtained by excluding one of the possible <em>p </em>variables are estimated and the model with the lowest AIC (or BIC) is considered.

<ol>

 <li>ii) Let <em>X<sub>j </sub></em>be the variable that is excluded and <em>L</em><sup>(1)</sup><em><sub>j </sub></em>be the likelihood of the model without <em>X<sub>j</sub></em>. The significance of <em>X<sub>j </sub></em>is tested using the G statistic</li>

</ol>

If <em>X<sub>j </sub></em>is not significant i.e., , the considered model is selected, otherwise the full model is selected and the selection procedure ends.

Step 1 is repeated until the variable that is dropped at the generic step <em>k </em>is significant.

Use the commands:

fullmodel&lt;- glm(Buy .,family=’binomial’, data=advertisement)~ mod.fin &lt;- step(fullmodel, direction = ’backward’) summary(mod.fin)

to select the “best” model. Interpret the parameters describing the relation between Buy and all the selected explanatory variables.

<h2>Task 4                                                                                                          6 points</h2>

The dataset alligator.csv contains aggregated data concerning the primary food choice of 219 alligators captured in four Florida lakes. The variables in the dataset are:

<ul>

 <li>lake: lake of capture (Hancock, Oklawaha, Trafford, and George)</li>

 <li>size: size of the alligator (small= ≤ 2<em>.</em>3 meters, large=<em>&gt; </em>2<em>.</em>3 meters)</li>

 <li>sex: gender of the alligator (0=male, 1=female)</li>

 <li>food: primary food choice (fish, invertebrate, reptile, bird, and other)</li>

 <li>count: number of alligators for each combination of the variables lake, size and sex</li>

</ul>

A biologist is interested in determining if there is a statistical association between the primary food choice of the alligators and their gender, size and the lake in which they live. Since food is a nominal variable, he would like to estimate a MNRM.

<ul>

 <li>Write down the formulation of the MNRM assuming “fish” as reference category.</li>

 <li>Estimate the model using R. Interpret the parameters of the log-odds of reptile vs. fish.</li>

 <li>What is the odds ratio of bird versus other for an alligator of small size relative to an alligator of large size? Interpret this odds ratio.</li>

 <li>Test the global significance of the variable lake.</li>

 <li>Test the fit of the model.</li>

</ul>