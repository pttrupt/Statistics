# **Statistics** 



###  **What is Statistics ?** 

The art and science of answering questions and exploring ideas through the process of <u>gathering data,</u> <u>describing data</u> and <u>making generalizations</u> about a <u>*population*</u> on the basis of a smaller <u>*sample*</u>.



### Gathering Data

***

Collecting data is an important first step in statistical analysis. The goal of statistics is to make <u>inferences</u> about a population based on sample.

##### Types of methods for collecting data: 

![Sampling method in statistics probabilistic Vector Image](https://cdn4.vectorstock.com/i/1000x1000/54/03/sampling-method-in-statistics-probabilistic-vector-28835403.jpg)



1.  Non-probability Methods

   * **Convenience Sample:** Collecting data from subjects who are conveniently obtained.

   * **Gathering Volunteers:** Collecting data from subjects who volunteer to provide data.

2. Probability Methods 

   * **Simple Random Sample:**  Every member and set of members has an <u>equal chance of being included</u> in the sample. Technology, random number generators, or some other sort of chance process is needed to get a simple random sample. 
   * **Stratified Random Sample:** Identified the population of interest then divide population into strata or <u>groups based on some characteristic</u> (e.g. sex, geographic region), then perform simple <u>random sample from each strata.</u> 
   * **Cluster Random Sample:** The population is first split into groups. The overall sample consists of every member from some of the groups. The <u>groups are selected at random</u>. 

Whenever data is collected, there is a risk that the sample is biased. Here are some potential types of bias.

##### Types of Bias 



#### Data:

---



##### Types of Data: 

![Data types in DS - Blog | luminousmen](https://luminousmen.com/media/data-types-in-ds.jpeg)

​																Source : [luminousmen.com](https://luminousmen.com/post/data-types-in-ds)





### Describing Data

---

#### **Population:** 

Any large collection of objects and individuals.

**Parameter**:

> Any summary number, like an average or percentage, that describe the entire population.

For example: 

- Population Mean  $ \mu $ 
- Population proportion  $ p $
- Population Variance , ...

The issue is that almost all of the time, we don't -- or can't -- know the real value of a population parameter. The best we can do is estimate the parameter! This is where samples and statistics come in to play. 



#### **Sample:**

Representative group drawn from the population.

**Statistics**:

> Any summary number, like an average or percentage, that describes the sample 

For example: 

- Sample Mean  $ \overline{X} $
- Sample proportion  $ \widehat{p} $ 
- Sample Variance  $ \sigma $, ...

Samples are manageable in size, so that we can determine the actual value of any statistics and use the known value of the sample statistics to learn about the unknown value of the population parameter.



#### Describing Univariant Data

---



1.  **Central Tendency**

   *  **Mean (Arithmetic Mean)** : Average of data.

     * **Population Mean** : **$ \mu $** 
       $$
       \mu = \dfrac{1}{N} {\sum X}
       $$

     * **Sample Mean**: $ \overline{x}$

       Let $x_1$, $x_2$ , ... , $x_n$ be our sample. 

     $$
     \overline{x} = \dfrac{1}{n}\left( \sum_{i=1}^{n} x_i\right) = \dfrac{x_1 + x_2 + ... + x_n}{n}
     $$

     ​		Where $n$ is the sample size.

     

   * **Median** : Middle value of the ordered data

     Steps to find the median for set of data:

     1. Arrange the data in increasing order 

     2. If sample size n is odd then median = $ \dfrac{n+1}{2}th$ value.

        If $n$ is even then median is the mean of $\dfrac{n}{2} th$ and $\dfrac{n+1}{2} th$ value.

        

   * **Mode**: Value that occurs most often in the data. 

     It is important to note that there may be <u>more than one mode</u> in the dataset.

     

   * **Relation Between Mean, Median and Mode**:

​				For moderately skewed distribution 
$$
3(\mbox{Median}) = \mbox{Mode} + 2(\mbox{Mean})
$$


2. **Spread** 

   * **Range**: Difference between the largest value and smallest value.

     However, it is very sensitive to extreme scores since it is based on only two values.

     

   * **Interquartile Range**: Difference between the 75th and 25th percentiles of data.

     Quartiles are denoted by $Q_1$ (also called the lower quartile or 25th percentile), $Q_2$ (the median) and $Q_3$ (also called the upper quartile or 75th percentile).
     $$
     IQR = Q_3 - Q_1
     $$
     

   * **Variance**: Measure of how much spread there is in the data. 

     Informally, the variance describes what fraction of the values are close to the mean.

     * **Population Variance** : $ \sigma^2 $
       $$
       \sigma^2 = \dfrac{\sum(X - \mu)^2}{N}
       $$

     * **Sample Variance** : $ s^2 $ 
       $$
       s^2 = \dfrac{\sum_{i=1}^{n}(x_i - \mu)^2}{n-1}
       $$
       There is particular why we use $ n-1 $ rather than $n$.

       

   * **Standard Variance**: Square root of the variance.

     While it contains exactly the same information as the variance, the standard deviation is easier to interpret because it is in the same units as the original data.

     The standard deviation <u>should always be viewed in the context of the mean</u>. If the mean were a billion and the standard deviation 100, we would view the dispersion the data as small. 

     * **Population Standard Variance** : $\sigma $​
       $$
       \sigma = \sqrt {\sigma ^2}
       $$
       

     * **Sample Standard Variance** : $s$
       $$
       s = \sqrt {s ^2}
       $$

3. **Shape**

   The shape of the data helps us do determine the most appropriate measure of central tendency. The three most important descriptions of shape are <u>Symmetric</u>, <u>Left-skewed</u> and <u>Right-skewed</u>.

   Skewness is a measure of the degree of asymmetry of the distribution.

   * Symmetric :

     <img src="C:\Users\patel\OneDrive\Pictures\symmetric.png" style="zoom:60%;" />

   * Left Symmetric :

   <img src="C:\Users\patel\OneDrive\Pictures\left skewed .png" alt="left skewed" style="zoom:60%;" />

   * Right Symmetric :

   <img src="C:\Users\patel\OneDrive\Pictures\right skewed .png" style="zoom:60%;" />

   



#### Describing Bivariate Data

---































### Types of Statistics 

---



![Types of Statistics](https://media.geeksforgeeks.org/wp-content/uploads/20200625233042/Untitled-Diagram-918.png)

​																		Source : [Geeksforgeeks.org](https://www.geeksforgeeks.org/introduction-of-statistics-and-its-types/)

#### Descriptive Statistics:

---

Techniques of describing data in ways to capture the essence of the information in the data are called **descriptive statistics**.

For example, the sample mean is a descriptive statistics. 



#### Inferential Statistics:

---

To draw conclusions from data about the population is called **inferential statistics**.

##### <u>**Types of Statistical Inference**</u>

1. **Estimation:** 

   > Use information from the sample to estimate the parameter of interest.

   Two common estimation methods are point and interval estimates.

   - *Point Estimates* :  An estimate for a parameter that is one numerical value.

   - *Interval Estimates* : Interval Estimates give an interval as the estimate for a parameter. Such a Interval are built around point estimates.

2. **Statistical Tests:**

   > Use information from the sample to determine whether a certain statement about the parameter of interest is true.



