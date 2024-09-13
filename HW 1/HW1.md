# HW1

## 1.1

Sample Average: 129.975 

Sample Standard Deviation: 8.914084217455962

## 1.2

![image-20231006095619705](C:\Users\moccc\AppData\Roaming\Typora\typora-user-images\image-20231006095619705.png)

## 1.3

Sample Median: 128.0 

Lower Quartile: 124.0 

Upper Quartile: 133.75

## 1.4

![image-20231006095709375](C:\Users\moccc\AppData\Roaming\Typora\typora-user-images\image-20231006095709375.png)

For the time-series plot, I find that there are a few points (like those around 150-160) that appear higher than the rest. These could be considered as  just a variation in the data. 



## 2

$$
P(x < 12) = \int_{11.75}^{12} 4(x - 11.75) \, dx = 0.125
$$



## 3.1

Given:
$$
\mu_0 = 0.5025 \\
\bar{x} = 0.5046 \\
\sigma = 0.0001 \\
n = 25
$$

Z, is given by:
$$
Z = \frac{\bar{x} - \mu_0}{\sigma / \sqrt{n}}
$$

Using the given values:
$$
Z = \frac{0.5046 - 0.5025}{0.0001 / \sqrt{25}} \\
\Rightarrow Z = 105
$$

For $\alpha = 0.05$, the critical value for a two-tailed test is $Z 1.96$. The computed z-value is much greater than this, so the null hypothesis is rejected.



## 3.2

Given the extremely large  Z -value 105, the p-value is essentially 0.

## 3.3

$$
CI = \bar{x} \pm Z_{\alpha/2} \times \frac{\sigma}{\sqrt{n}}
$$

Plugging in the values:

$$
CI = 0.5046 \pm 1.96 \times \frac{0.0001}{\sqrt{25}}
$$

Resulting in:

$$
CI \approx (0.5045608, 0.5046392) \text{ in.}
$$
