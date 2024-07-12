# Introduction

We investigate the effect of contamination in randomized clinical trials. Contamination is said to have occured if subjects from one treatment group inadvantently receive treatment meant for the other group. In practice, patients in the control arm tend to cross into the intervention arm. 

A **statistical test** for the treatment effect tend to favor the null in the presence of contamination. In other words, contamination increases the risk of type II error. 

Suppose that only the control group is contaminated. Let $\omega$ be the contamination rate. Then the expected treatment effect for the control group is 

$$ (1-\omega)\mu_c - \omega\mu_t $$

and the difference in treatment effect between intervention and control group is 

$$
\begin{equation*} 
\begin{split}
&=\mu_t - \left[(1-\omega)\mu_c - \omega\mu_t\right] \\
&= (1-\omega)(\mu_t-\mu_c)\\
&=(1-\omega)\delta,  \text{ where } \delta=(\mu_t-\mu_c)
\end{split}
\end{equation*}
$$

[Add more notes]