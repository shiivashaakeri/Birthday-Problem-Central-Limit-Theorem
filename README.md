# Birthday Problem and Central Limit Theorem

This repository contains Python code for exploring two statistical concepts - the birthday problem and the central limit theorem.

## Birthday Problem

The birthday problem is a classic problem in probability theory that asks how many people need to be in a room before there is a 50% chance that two people share the same birthday. This code provides a simulation-based approach to answering this question.

The `genRandomBirthday` function generates a random birthday, while the `genBirthdays` function generates a list of random birthdays for a given number of people. The `uniqueBirthday` function checks if there are any coinciding birthdays in the list, and the `estimateUnique` function estimates the probability of at least one coincidence in a room with a given number of people.

The `estimate_p_aloc_for_range` function computes the probabilities of at least one coincidence for a range of values of k, the number of people in the room. The results are plotted using the matplotlib and seaborn libraries.


## Central Limit Theorem
The central limit theorem is a fundamental concept in statistics that states that, under certain conditions, the sum or average of a large number of independent and identically distributed random variables will be approximately normally distributed.

This code provides a simulation-based approach to understanding the central limit theorem. It includes functions for sampling from exponential and binomial distributions and plotting the resulting sampling distributions.

The `expSampling` function takes in the sample size and number of iterations, generates samples from an exponential distribution, and plots the resulting sampling distribution. It then estimates the mean and standard deviation of the sampling distribution and returns them.

The `binSampling` function takes in the sample size and number of iterations, generates samples from a binomial distribution, and plots the resulting sampling distribution. It then estimates the mean and standard deviation of the sampling distribution and returns them.

## Acknowledgments 
- [Birthday problem and the central limit theorem](https://www.youtube.com/watch?v=VdJf1yWpZ7M)
- [Central Limit Theorem and the Birthday Problem - Math with Mr. Barnes](https://www.youtube.com/watch?v=UvFMf0JNm8g)
- [Khan Academy: "The birthday problem"](https://www.youtube.com/watch?v=VXfHUrG_1vs)
- [Math Is Fun: "Birthday Problem"](https://www.mathsisfun.com/data/birthday-problem.html)
