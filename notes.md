

### Introduction

---


#### Example
* Consider influenza epidemics for two parent heterosexual families. 
    * the probability is 17% that at least one of the parents has contracted the disease. 
    * The probability that the father has contracted influenza is 12% 
    * the probability that both the mother and father have contracted the disease is 6%. 
    * What is the probability that the mother has contracted influenza?

    * $P(P \cup B) = P(A) + P(B) - P(A \cap B)$
    * $P(A \cap B) = .17$
    * $P(A \cup B) = .06$
    * $P(A) = .12$
    * $P(B) = ??$
    * $.06 = .12 + .11 - .17$

####Example 
* you flip a coin and if it comes up heads you give her X dollars and 
    * if it comes up tails she gives you Y dollars. 
    * The probability that the coin is heads is p
    * What has to be true about X and Y to make so that both of your expected total earnings is 0. 
    * The game would then be called “fair”. 

    * d = odds of heads
    * -X heads
    * Y tails
    * w = earnings

w     	-X 	Y
P(w)	P 	1 - P

Expected value of a random variable is the values it can take times the probability that it takes them 

$E[w] = -Xp + Y(1 - P)$
$0 = -Xp + Y(1 - P)$
$0 = -Xp + Y - Yp$
$0 = -Xp + Y(1 - P)$
$0 / 1 - p = -Xp + Y / 1 - p$

#####
* home pregnancy tests: 
    * sensitivity was 75%. 
    * Specificity 52%
    * 30% of women taking pregnancy tests are actually pregnant
    * the probability of pregnancy given the positive test?

    * + and - are the positive and negative test results
    * D Dc (D complement) is the event that the person has the disease or not
    * Sensitivity = P(+ | D) = the probability the test is positive given that the person has the disease
    * Specificy = P(- | Dc) = the probability the is negative given the person does not have the disease


Odds
d = P / 1 - P
p = d / 1 + d

--------------------------

### test
variance of a random variable is E[x^2] - E[x]^2
Expected value of a random variable is the values it can take times the probability that it takes them 

x^2	x 	p
16	-4	.2
1	1 	.8

$E[x^2] = (16 * .2) + (1 * .8)$
	   $= 3.4 + .8$
	   $= 4$
$E[x] =  (-4 * .2) + (1 * .8)$
	 $= -.8 + .8$
	 $= 0$ 

$E[x^2] - E[x]^2$
	$4 - 0 = 4$


---

### more test
* density with mean = mu x
* variance = $\sigma^2$

* variance of $\bar{X}$ is $\sigma^2 / N$

* take the mean of N observations from this density 
	* this is a single observation from the density of the average of N draws from the original density
	* $\bar{X}$ = this new density 
	* $\bar{X}$ is centred at the same place as the original density
	* but it is more centred at the mean, not as dispersed 
	* $\bar{X}$ is a good estimator of $\mu$
	* relation of the variance of $\bar{X}$ to the variance of original population

* variance of original population = sigma squared
* variance of X bar is sigma square over N 

* $var(\bar{X} - \bar{Y}) = var(\bar{X}) + var(\bar{Y})$
* $var(\bar{X} - \bar{Y}) =  \sigma^2/N  + \sigma^2/N$ 
* $var(\bar{X} - \bar{Y}) = 2(\sigma^2)/ N$

----

var(x) = sig^2
sd(x) = sig


---
### Expected Values
* Expected values = the process of making conclusions about populations from noisy data that was drawn from it
* The expected value or mean of a random variable is the centre of the distribution
* variable is how spread out the distrubtion is 
* sample expected values estimate the population expected values
* sample(mean) will be estimate of the poplution mean
* same for sample variance and std dev

* Expected value of a random variable is the sum of the values it can take times the probability that it takes them 

* variance of a random variable is $E[x^2] - E[x]^2$

* and unbiased estimated or one where the sample mean = the population mean
* the population mean of two die rolls is the same as mean of a sample of the averages of two die rolls

