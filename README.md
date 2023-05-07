Download Link: https://assignmentchef.com/product/solved-introduction-to-simulation-and-modeling-csc432-632-project-1
<br>
*Tentative Version.




Description of the project:




This is a unified project and all groups require to work together and answer the questions at the end of each question. Some of the questions require exploring in different sources and conversation among team members. After collecting all the answers and explanations, you need to collect a unified summary and provide a report about your observations about the companies and organizations using operations management techniques and strategies. Only one copy by the group representative is required due to submission. Please submit one WORD copy for answering the questions and one .py file containing all Python codes. No page limit or format is imposed. Try your best to submit a professional and comprehensive report.




<strong><u>Problem 1: Weather Forecast:</u>  </strong>

Suppose that whether or not it rains today depends on previous weather conditions through the last two days. Specifically, suppose that if it has rained for the past two days, then it will rain tomorrow with probability 0.7; if it rained today but not yesterday, then it will rain tomorrow with probability 0.5; if it rained yesterday but not today, then it will rain tomorrow with probability 0.4; if it has not rained in the past two days, then it will rain tomorrow with probability 0.2.

If we let the state at time n depend only on whether or not it is raining at time n, then the preceding model is not a Markov chain (why not?). However, we can transform this model into a Markov chain by saying that the state at any time is determined by the weather conditions during both that day and the previous day. In other words, we can say that the process is in

<ul>

 <li>State 0            if it rained both today and yesterday,</li>

 <li>State 1            if it rained today but not yesterday,</li>

 <li>State 2            if it rained yesterday but not today, State 3             if it did not rain either yesterday or today.</li>

</ul>

The preceding would then represent a four-state Markov chain having a transition probability matrix




You should carefully check the matrix P, and make sure you understand how it was obtained.




Answer the following questions:




<ol>

 <li>Calculate the proportion of days that it rains.</li>

 <li>If it rains today, what is the probability that a it also rains tomorrow?</li>

 <li>If it rains on Monday, what is the probability that it is sunny on Wednesday?</li>

 <li>If it rains on Monday, what is the chance it also rains on three consecutive days (Tuesday, Wednesday, and Thursday)?</li>

</ol>




Discussion Questions:




<ol>

 <li>If you are a weather forecast manager, do you think the Markov Chains method alone is enough in predicting the weather? What other factors should have been taken into account for better predictions? How do you think the probability data in the matrix above (P) can be obtained?</li>

 <li>Provide some variations to extend this problem and create three additional questions for the variation you just introduced. You do not need to answer the questions at this time.</li>

</ol>










<strong>             </strong>

<strong><u>Problem 2: Random Walk:</u></strong><strong>  </strong>

Consider a Markov chain whose state space consists of the integers <em>i </em>= 0, ±1, ±2, . . ., and has transition probabilities given by

<em>Pi</em>,<em>i</em>+1 = <em>p </em>= 1 − <em>Pi</em>,<em>i</em>−1,     <em>i </em>= 0, ±1, ±2,…

where 0 &lt; <em>p </em>&lt; 1. In other words, on each transition the process either moves one step to the right (with probability <em>p</em>) or one step to the left (with probability 1 − <em>p</em>).

One colorful interpretation of this process is that it represents the wanderings of a drunken man as he walks along a straight line. Another is that it represents the winnings of a gambler who on each play of the game either wins or loses one dollar.

<ol>

 <li>consider a gambler who starts with $100 who receives $1 with p = 0.4 each time he plays the game and losses $1 with probability 1 – p = 0.6. assuming that p = 0.4. Using a simulation model (in Python), calculate the probability of coming back to $100 at least once after playing the game 10 times.</li>

 <li>Repeat part b) using p = 0.5.</li>

 <li>What is the probability that the gambler gets ruined (losing all $100) after 1000 games?</li>

 <li>What is the probability that the gambler gets ruined (losing all $100) at all?</li>

</ol>

Discussion Questions:

<ol>

 <li>Provide one more example of random walk in the real world. Add some variations to extending this problem and, accordingly, create three additional questions for the problem variation. You do not need to answer the questions at this time.</li>

</ol>











