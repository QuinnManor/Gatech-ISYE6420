## ISyE 6420 "Bayesian Statistics", Spring 2019
## Homework 1 / Solutions
January 29, 2019

### 1 Circuit

Assume that:
X : e5 works
Y : e5 does not work

we have:
P(S|X)=1 − (1 − P(e1))(1 − P(e4)) = 1 − 0.6 ∗ 0.5=0.7
P(S|Y ) = P(e1)(1 − (1 − P(e2))(1 − P(e3))) = 0.4 ∗ (1 − 0.2 ∗ 0.4) = 0.368

(a) To calculate the probability that the circuit is operational P(S), we have
P(S) = P(S|X)P(X) + P(S|Y )P(Y )=0.7 ∗ 0.9+0.368 ∗ 0.1=0.6668

(b) To calculate P(X|S), by Bayes’ rule, we have
P(X|S) =P(S|X)P(X)P(S)=0.7 ∗ 0.90.6668= 0.9448

### 2 Multiple Choice
We define the following events:

H : The student knows the answer to the question
A : The student answers the question correctly

and use Hc to denote the complement event of H, i.e. the student does not know the answer to the question.

Based on the description of the problem, we know that 
P(H)=0.7,P(Hc)=0.3 and P(A|H) =1,P(A|Hc)=0.25.

(a) To calculate P(A), we have
P(A) = P(A|H)P(H) + P(A|Hc)P(Hc) = (1)(0.7) + (0.25)(0.3) = 0.775.

(b) To calculate P(H|A), by Bayes’ rule, we have
P(H|A) =P(A|H)P(H)P(A)=(1)(0.7)0.775= 0.90321
