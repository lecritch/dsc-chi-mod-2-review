# Mod 2 Code Challenge Review

You've come a long way with this material

Close out strong

![](viz/mortal_kombat.gif)

### Examples

For each of the questions below:

- What is the null hypothesis?  What is the alternative?

- What level of alpha are we using?  


- What specific test are we using?
    - **why?**


- What is the critical statistic(s) at which we will designate evidence for rejecting the null?

- What is the test-statistic?

- What is the p-value?

- Should we accept or reject the null hypothesis?

- In English, what's the answer to the question?

### Z-test example

An SAT prep class of 25 students takes the SAT and gets the following scores:

434 694 457 534 720 400 484 478 610 641 425 636 454
514 563 370 499 640 501 625 612 471 598 509 531

We know the average for SAT scores as a whole is 500 with a standard deviation of 100

Did this SAT prep class result in a significantly greater mean of scores than average?
(use an alpha level of .05)

[z-table](https://www.z-table.com) to use for calculations if you wish


```python

```

### Example: T-test

#### T-test question 1

Samples of diastolic blood pressure were takin from a sample of 20 female doctors

128 127 118 115 144 142 133 140 132 131 111 132 149 122 139 119 136 129 126 128

The mean female population diastolic blood pressure is 120

Are female doctor diastolic blood pressures significantly higher than the female population's?


```python

```

#### T-test question 2

Tesla claims that they're miles-per-15min-of-charge average 31 

You are hired by an eccentric Silicon Valley entreprenuer to test his fleet of 8 Teslas and see if the claim holds up

You have a fair amount of driving around generating the data, and when you do you get these results:

30 28 32 26 33 25 28 30

Is Elon Musk a dirty liar?


```python

```

#### T-test question 3

You are an archeologist.  Not Indiana Jones, the boring kind.  And at two sites you come across a series of shards from pots.

You know from your boring archeologist training that different thicknesses at the lip of the pots indicate different ceremonial functions.  

You want to test the two samples of shard thickness to see if the thickness is due to chance at the two sites.

Sample 1 has slightly thicker shards overall, so you want to test if the mean of sample 1 lip thickness is higher than the mean of sample 2 lip thickness.  

Assume that the two sample variances are equal.

Sample 1 data:
19.7475 19.8387 12.6873 17.6973 19.0878 30.5562 14.5291 14.7627 14.3439 12.5745 11.0734 19.4998 18.3869 10.7374 18.0030 18.1730 18.8374 17.9287 15.3563 18.6004 11.7280 12.2898 21.0552 21.4184 25.5953

Sample 2 data:
17.4715 20.0386 12.6012 20.4401 22.4969 9.8613 19.6289 9.7741 15.1119 17.4448 23.4827 24.9357 19.9265 7.9955 17.6675 13.6029 17.8812 16.4178 5.1385 7.0984 18.1181 20.2681 14.7372 22.5915 16.7546


```python

```

### T-test question 4

Two sets of female rats were given a high- and low-protein diet, respectively, after giving birth.  Their weights were measured after 2 months.

Set 1 (high protein) = 134 146 104 119 124 161 107 83 113 129 97 123

Set 2 (low protein) = 70 118 101 85 107 132 94

Is there a difference in rat weight between high- and low-protein diets after giving birth in this experiment?
(Assume the sample variances are equal)


```python

```

#### T-test question 5

Get a wee bit of practice w/ pandas again, eh?

Back to the data about Seattle city service `hourly_rate` compensation

There's a national debate about whether construction workers or HR people account for more "bloat" in the system.  Construciton workers argue that there are a higher percentage of "junior" positions in their departments, while HR people have more "senior" positions.  

Let's test that with the Seattle data.

Create a dataframe of:
- jobs in the `Construction and Inspections` dept
- jobs in the `Human Services Dept` . . . dept
- that don't have `Sr` as the last two letters in their title

Sample 50 junior employees from each department (`random_state=33`)

Use those employees to provide evidence for the question: do junior employees in construction departments have different `hourly_rate` compensation than those in HR departments?


```python

```

[Welsh's t, ie ttest_ind(equal_var=False), has some proseltyzors](https://onlinelibrary.wiley.com/doi/abs/10.1348/000711004849222)


```python

```
