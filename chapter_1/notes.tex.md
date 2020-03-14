
# Uncertainties in Measurements


## Notation

the sum of a series of measurements:


$\sum\limits_{i=1}^N x_i \equiv x_1 + x_2 + x_3 + ... + x_N$

as a shortcut:

$\sum x_i \equiv \sum\limits_{i=1}^N x_i $



## Median, Median, and Mode



### Mean
The discrete mean, $\bar{x}$, is defined as: $\bar{x} \equiv \frac{1}{N} \sum x_i $

and the mean, $\mu$ of the parent population is defined as the limit:

$ \[\mu \equiv \limits_{N \to \infty} \frac{1}{N}(\sum x_i)\]$

### Median

The median of the parent population, $\mu_{1/2}$, is defined as the value where (in an infinite number of values in a distribution) half the obseverations will be less than the median, and half will be greater:

$ P(x_i < \mu_{1/2}) = P(x_i > \mu_{1/2}) = 1/2 $

### Mode

The mode is the most probably value, $\mu_{max}$, is the value for which the parent distribution has the greatest value. In any given experimental measurment, this value is the one most likely to be observed. In the limit of many observations, this value will probably occur most often:

$ P(\mu_{max}) > P(x \ne \mu_{max})$

### Deviations


The deviation, $d_i$ of any measurment, $x_i$ from the mean $\mu$ of the parent distribution is defined a the difference between $x_i$ and $\mu$:

$ d_i \equiv x_i - \mu $


### Variance
The variance, $\sigma^2$, is defined as the limit of the average of the squares of the deviations from the mean $\mu$:

$ \sigma^2 \equiv \limits_{N \to \infty}[\frac{1}{N}\sum(x_i - \mu)^2] = \limits_{N \to \infty}(\frac{1}{N}\sum x_i^2) - \mu^2 $



##  Mean and standard deviation of Distribtutions

### Discrete Distributions

If there is a discrete function $P(x)$ representing the probability of a measurement $x$ with N observations, we'd expect each observable measurement to occur $N*P(x_i)$ times.

The average can be expressed in the following ways:


$ \mu =  \limits_{N \to \infty} \frac{1}{N} \sum\limits_{i=1}^N x_i =  \limits_{N \to \infty} \frac{1}{N} \sum\limits_{j=1}^N [ x_j NP(x_j)] = \limits_{N \to \infty} [ x_jP(j_j)]4

Note here that the index $j$ is between [1,n], with unique values, i.e. no two values of x_j equal.



We can show the same in terms of the variance:






