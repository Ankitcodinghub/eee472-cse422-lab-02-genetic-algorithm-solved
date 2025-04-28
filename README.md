# eee472-cse422-lab-02-genetic-algorithm-solved
**TO GET THIS SOLUTION VISIT:** [EEE472-CSE422 Lab 02-Genetic Algorithm Solved](https://www.ankitcodinghub.com/product/eee472-cse422-artificial-intelligence-lab-02-genetic-algorithm-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120340&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EEE472-CSE422 Lab 02-Genetic Algorithm Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
Run Chase Problem

Suppose, you have a run-predictor for cricket matches and the predictor can predict the target run for batting innings. Now you need to find out the match-winning combination of batsmen for your favorite team given the average runs of different batsmen. You need to find out a combination of batsmen where the total of average runs equals exactly the runs predicted as the target score by the predictor.

The input contains the number of batsmen available, the target run predicted by the predictor, and the names and average runs of the respective batsman.

Assume, the predictor predicted 300 runs as the target and there are 7 batsmen in your favorite team with their corresponding average scores, you need to find out the binary combination (1 denoting batsman selected, 0 denotes batsman not selected) of those 7 batsmen in order to find the winning combination.

Your task is to use a genetic algorithm to solve this Run-Chase problem.

Task Breakdown:

a) Model the selected batsman array in a way suitable for the problem.

b) Write a fitness function. Hint: It is the sum of the total runs of the selected batsmen.

c) Write the crossover function.

d) Write the mutation function.

e) Create a population of randomly generated selected-batsman-array.

f) Run genetic algorithms on the population until the highest fitness has been reached and/or the number of maximum iterations has been reached.

Input:

The first line has a number N and T denoting the number of batsmen available and target score respectively followed by N lines each starting with the batsman’s name and a number R denoting the average run of the batsman. Here:

N (1 ≤ N ≤ 18)

T (1 ≤ T ≤ 1000)

R (1 ≤ R ≤ 401)

Output:

The output contains a list of all the players and the following row contains a binary string denoting 1 for the selected batsmen and 0 for the not selected batsmen where average runs of selected batsmen sums up equal to the target or -1 if such a string cannot be formed.

Examples:

Sample Input 1

8 330

Tamim 68

Shoumyo 25

Shakib 70

Afif 53

Mushfiq 71

Liton 55

Mahmudullah 66

Shanto 29

Sample Output 1

[‘Tamim’, ‘Shoumyo’, ‘Shakib’, ‘Afif’, ‘Mushfiq’, ‘Liton’, ‘Mahmudullah’, ‘Shanto’] 10101110

Explanation: Here, the sum of the average runs of Tamim, Shakib, Mushfiq, Liton and Mahmudullah adds up to 68+70+71+55+66 = 330.

Sample Input 2

5 240 Bradman 120

Tendulkar 90

Sangakkara 70

Kallis 65

Lara 80

Sample Output 2

[‘Bradman’, ‘Tendulkar’, ‘Sangakkara’, ‘Kallis’, ‘Lara’]

01101

Sample Input 3

4 100

Ralph 80

John 70

Tom 40

Sample Output 3

-1
