

# Smallest Effect Size of Interest {#sesoi}

## What would falsify your theory?

In the previous module, we talked about how to make riskier predictions. In this module, we'll focus on how your predictions can actually be falsified; first talking about this topic from a theoretical perspective, and then later about how to implement these ideas in practice. Let's start with a very simple question: Have you ever designed a study where the goal was to show that there was no effect? So your prediction was that there would be no difference between two conditions, not just as a possible outcome (i.e., a failure to confirm your prediction of an effect being present), but really as the main prediction that you were interested in. 

I've asked this question to quite a lot of scholars around the world and most people say they have never designed a study where their main prediction was that the effect size was 0. Researchers almost always predict there is a difference. Most scientific research questions are stated in a way that the prediction is that there will be some effect. Yet, it's very often the case that demonstrating the absence of an effect would be extremely interesting. For example, there might be an existing intervention that requires face-to-face contact with a therapist. People need to come in every week to get some treatment. This is effortful, and you are interested in whether moving this intervention completely online would work just as well. You do not predict it to do better, or worse, but you predict it will work just as well. Because the online only intervention will be much cheaper and easier to use, we might prefer it in the future as long as it works equally well. As an additional example, you might have a theoretically predicted absence of an effect. Your theory predicts that two things should not differ, and you want to be able to demonstrate that this prediction is supported. 

How would you design an experiment that can support the absence of an effect? Take a moment to think about this. Now you might think that you can support the absence of an effect whenever you observe a *p*-value that's larger than the alpha level that was chosen. However, as the saying goes, the absence of evidence is not evidence of absence. Just to give you a simple illustration why this is true, let's say that I'm going to examine how much people who read this text like chocolate. I compare their ratings with people who have not read this text. If I just take two people from each group, am I likely to find a statistically significant difference between these two groups of two people? The answer is clearly no. The sample size is much too small, and we are very likely to make a Type 2 error. We might just have a lack of power to detect real differences. 

<div class="figure" style="text-align: center">
<img src="images/nonsig1.png" alt="Non-significant results do not allow us to conclude an effect is absent." width="100%" />
<p class="caption">(\#fig:nonsig1)Non-significant results do not allow us to conclude an effect is absent.</p>
</div>

Assume we are interested in the difference between two groups. On the left of Figure \ref{fig:nonsig1}) we see the expected distribution if the difference is exactly zero. On the right we see the expected distribution if the difference is 0.5. We have observed a difference of 0.35, which is not extreme enough to be statistically different given this sample size. However, a difference of 0.35 is actually quite likely under the assumption that the true effect size is 0.5. So just observing a non-significant difference does not mean that there's no true effect in the population. 

Now take a look at your own scientific papers, or a paper that you want to build on in the future. Search in this work for a *p*-value that's larger than 0.05, and take a look at how people interpret this result. You'll very often see that a non-significant *p*-value is in practice interpreted as the absence of an effect even though this is a logical fallacy. Indeed, this is one of the most common misinterpretations of *p*-values. 

So, if a *p*-value larger than 0.05 is not enough to falsify a prediction, maybe you will consider a prediction falsified if you observe a significant result in the opposite direction of what you predicted. Now surely that must be a way to falsify our prediction. In practice most people would consider this a clear falsification. If you predict an effect in one direction and you observe an effect that is statistically significant in the opposite direction, well that seems to clearly falsify the prediction you had. However, if the null hypothesis is true, you shouldn't find significant results in any direction, very often, and if you would find a significant result in any direction, it is a Type 1 error. It's a fluke. So hoping to observe a significant result in the opposite direction is also no way to falsify a prediction. 

To get closer to an approach that allows us to falsify a prediction, we first need to ask ourselves if any effect in the predicted direction is actually support for the alternative hypothesis. We very often talk about our predictions as *any* effect in the predicted direction, but do we really think so? For example, would an effect size of a Cohen's d of 10, which means an effect as large as 10 standard deviations. Would such an immensely huge effect actually be support for your theory? Almost no effects in experimental psychology would ever be this big. So I would argue that this is an effect that's much too large to be support for your theory and if I would observe a Cohen's d 10 of in a study that I perform, I would highly suspect that I made a coding error because effects of this size are much too large to be in line with my theories about human behavior. If you read the scientific literature, you can find effects that are too large to be plausible, given the mechanisms a theory suggests. 

<div class="figure" style="text-align: center">
<img src="images/hungryjudges.png" alt="The original Figure 1 from Extraneous factors in judicial decisions by Danziger and colleagues." width="100%" />
<p class="caption">(\#fig:hungryjudges)The original Figure 1 from Extraneous factors in judicial decisions by Danziger and colleagues.</p>
</div>

Let's take a look at the study that is mentioned in many popular science books that was interpreted as evidence that the decisions judges make are influenced by the time that has passed since they had a coffee or lunch break. We see a graphical representation of the proportion of favorable parole decisions that real-life judges are making as a function of the number of cases they process across the day in Figure \ref{fig:hungryjudges}). We see that early on in the day, judges start by giving about 65% of people parole, which basically means, "All right, you can go back into society." But then very quickly, the number of favorable decisions decreases to basically zero over the course of the day. Then it goes back up again after a quick break where they have something to eat, and relax a little bit, and replenish their energy. After this break, the parole decisions are back up at 65%, and then again quickly drop down to basically zero. They take another break, the percentage of positive decisions is back up to 65%, only to drop again over the course of the day. So these are very clearly noticeable effects, and the authors propose mental depletion as an underlying mechanism. 

If we calculate the effect size, we see it is a Cohen's d of approximately two, which is incredibly large. Almost no effects in psychology have an effect of this size. So this is a surprisingly huge effect, not just once, but we see the effect emerge three times over the course of the day. If mental depletion really had such a huge effect on real-life court cases that we would see this drop three times over the course of the day, then society would basically fall into complete chaos just before the lunch break every day. Our cognitive resources would be so depleted, we would get into all sorts of problems because many people would start to make mistakes and bad decisions. Under our theoretical predictions, we shouldn't be observing effects that are this large. 

Let's go back to the question whether we really predict *any* effect that is not zero. So a Cohen's d of 10 is probably too large. Would an effect size of Cohen's d of 1, one standard deviation, be support for your theory? It might be. There are some effects in psychology that are this large, such as the effect of social exclusion on negative affect. So effects of this size happen, and they are very noticeable on an individual level.

Would an effect size of 0.1 be suppot for your theory? This is a very small effect, almost not noticeable on an indiviudal level - but any effects in psychology are this small, so these effect sizes are surely likely. The question is if effects this small are too small to be predicted by your theory. If you are unsure, we can make the example more extreme. Would a Cohen's d of 0.01 be support for your theory, or is this effect really too close to zero to matter? What about an effect size of d = 0.001? I think we've reached the point where almost all people would say "Well, this is really too small to be something that my theory has predicted. This is basically zero in practice." 

However, when we make a directional prediction, we say that these types of effects all are part of our alternative hypothesis. Even though we would all agree these effects are too small to matter, these tiny effects are still officially support for our alternative hypothesis if we have a directional prediction. The problem is that if we include these tiny effects in our alternative hypothesis, we will never have enough resources in the world to falsify this alternative prediction. for any replication study that fails to find the effect, you will always be able to say 'well, I guess the effect is smaller than we though'. If you want your alternative hypothesis to be falsifiable, it is important to realize we can never prove that an effect is exactly equal to zero. There is always some random variation, and there are no statistical tools that allow us to conclude an effect is exactly 0. The only way to make a prediction falsifiable is to say "Okay, I'm going to make a theoretical prediction with some smallest effect size that I actually care about." 

De Groot @de_groot_methodology_1969 has suggested that "Authors of a theory should state what potential outcomes would lead them to regard the theory as disproven." He suggests that when you make a theoretical prediction, you should also state what would falsify the prediction. This is important, because if we do not have a process of replication and falsification, a scientific discipline risks a slide towards the unfalsifiable [@ferguson_vast_2012]. Klaus Fiedler [@fiedler_tools_2004] writes that only when theories are detached from individuals, and many different researchers working in different labs and driven by different motives participate in a pluralistic endeavor, can the full potential and the weaknesses of a theory be expected to unfold. So in essence, what we need is to collectively get together, think about the theories that we have, how we can actually test them, and how we could falsify them, what their weaknesses are, and then we can have theoretical progress in a sense that we might not end up with different theories, but maybe three that are really useful to test. So whenever possible, when you design an experiment or you have a theory and a theoretical prediction, carefully think about and clearly state, what would falsify your prediction. 

## What would falsify your theory in practice?

One of the main things that is needed to falsify our prediction is say to specify which values would be actually too small to be still predicted by our theory. We can never say that an effect is exactly zero, but we can examine whether the effects are too small to be theoretically or practically interesting. This requires that we specify the **smallest effect size of interest** (SESOI). 

Take a moment to think about this question for your own research, for the last study that you've done, or for the next study that you are designing. Now, this is probably quite a difficult question to think about. The question what the smallest effect size of interest is might be something you never really considered to begin with. However, determining your smallest effect size of interest has important practical benefits. 

If you, or even better, if all researchers in your field, are able to specify which effects would be too small to matter, it becomes very straightforward to power a study for the effects that you think are meaningful. Most often if researchers perform an a priori power analysis, they use the effect size they think is most likely, or maybe the effect size they optimistically hope is true, in their power calculation. The difficulty is that the effect size in the population which is always unknown. Ater all, this effect sizes is the thing that we want to know when we do the study. So there's always a large amount of uncertainty around the true effect size, and therefore, there is a large amount of uncertainty about which effect size you should enter in an a-priori power analysis, and thus which sample size you should collect. 

But if you can very accurately specify the smallest effect size you are interested in, you're able to design a study so that it has high power to detect effects that are as large or larger than the smallest effect size of interest. In this way, you can design a study such that you will always get an informative result. Remember that statistical power is a curve. So whenever you design a study, power will be low for tiny effects, but power might be high for very large effects. To make sure that it's large enough for effects that you actually care about, you have to specify what the smallest effect size of interest is. Having high power for the smallest effect size of interest basically guarantees that you design an informative study. 

The second benefit of specifying the smallest effect size of interest is that it makes your study falsifiable. Having your predictions falsified by someone else might not feel that great for you personally, for science overall this is actually a very good thing. Imagine that we would be doing scientific research, but that all our questions couldn't be wrong to begin with. In such an approach to science, where you can't be wrong, why would anyone be impressed if you are right? If we specify a smallest effect size of interest, we can use equivalence tests to falsify our predictions. 

## Specifying a SESOI based on theory or costs and benefits 

Let's think about how you can determine the smallest effect size of interest. There are two general approaches you might want to consider. The first is to base your SESOI on a prediction derived from your theoretical model. You might be working in a field where the theoretical models are developed enough so that your computational models are able to make quantifiable predictions. In these cases, you can actually use the range of values that are predicted to specify the smallest effect size of interest. Now, having a computational model is quite rare. If this is not the case, you might also be able to consider the practical implications of your research. 

If your research has real life practical consequences, you might be able to consider the practical significance of the finding: which effects would be large enough so that they would actually matter? 

### Example of a theoretically predicted SESOI

One example of a theoretically predicted smallest effect size of interest can be found in study by Burriss et al. (2015), who examined whether women displayed increased redness in the face during the fertile phase of their ovulatory cycle. The hypothesis was that a slightly redder skin signals greater attractiveness and physical health, and that sending this signal to men yields an evolutionary advantage. This hypothesis presupposes that men can detect the increase in redness with the naked eye. Burriss et al. collected data from 22 women and showed that the redness of their facial skin indeed increased during their fertile period. However, this increase was not large enough for men to detect with the naked eye, so the hypothesis was falsified. Because the just-noticeable difference in redness of the skin can be measured, it was possible to establish a theoretically motivated SESOI.

### Anchor based methods to set a SESOI

Psychologists are often interested in effects that are large enough to be noticed by single individuals. A commonly used procedure to estimate what constitutes a meaningful change on an individual level is the anchor-based method (Jaeschke et al., 1989; Norman et al., 2003, for a review, see King, 2011). Measurements are collected at two time points (e.g., a quality of life measure before and after treatment). At the second time point an independent measure (the anchor) is used to determine if individuals show no change compared to time point 1, or if they have improved, or worsened. Often, the patient is directly asked to answer the anchor question, and indicate if they subjectively feel the same, better, or worse at time point 2 compared to time point 1. Button et al (2015) used an anchor-based method to estimate that a minimal clinically important difference on the Beck Depression Inventory corresponded to a 17.5% reduction in scores from baseline.

Anvari and Lakens (2019) applied the anchor-based method to examine a smallest effect of interest for affect as measured by the widely used Positive and Negative Affect Scale (PANAS; Watson et al., 1988). Participants completed the 20 item PANAS on two time points several days apart (using a Likert scale going from 1 = “very slightly or not at all”, to 5 = “extremely”). At the second time point they were also asked to indicate if their affect had changed a little, a lot, or not at all. When people indicated their affect had changed “a little”, the average change in Likert units was 0.26 scale points for positive affect and 0.28 scale points for negative affect. Thus, an intervention to improve people’s affective state that should lead to what individuals subjectively consider at least a little improvement might set the SESOI at 0.3 units on the PANAS. 

### Cost benefit analysis

Another principled approach to justify a smallest effect size of interest is to perform a cost-benefit analysis. Research shows that cognitive training may improve mental abilities in older adults (Ball et al., 2002) which might benefit older drivers. Based on these findings, Viamonte, Ball, and Kilgore (2006) performed a cost-benefit analysis and concluded that based on the cost of the intervention ($247.50), the probability of an accident for drivers older than 75 (p = 0.0710), and the cost of an accident ($22.000), performing the intervention on all drivers aged 75 or older was more efficient than not intervening or only intervening after a screening test. Furthermore, sensitivity analyses revealed intervening for all drivers would remain beneficial as long as the reduction in collision risk is 25%. Therefore, a 25% reduction in the probability of elderly above 75 getting into a car accident could be set as the smallest effect size of interest. 
For another example, economists have examined the value of a statistical life, based on willingness to pay to reduce the risk of death, at $1.5 - $2.5 million (in the year 2000, in western countries, see Mrozek & Taylor, 2002). Building on this work, Abelson (2003) calculated the willingness to pay to prevent acute health issues such as eye irritation at about $40-$50 per day. A researcher may be examining a psychological intervention that reduces the amount of times people touch their face close to their eyes, thereby reducing eye irritations caused by bacteria. If the intervention costs $20 per year to administer, it therefore should reduce the average number of days with eye irritation in the population by at least 0.5 days for the intervention to be worth the cost. A cost-benefit analysis can also be based on the resources required to empirically study a very small effect when weighed against the value this knowledge would have for the scientific community.

### Setting the SESOI based on effects feasible to study

It might be possible that you're working in a field where the theories are not precise enough to make predictions, but where there are also no direct practical consequences of the research that is done. THis leaves little justifications for a smallest effect size of interest, beyond any effect sizes that you think are still worth your time and money. In those cases, you can think about setting the smallest effect size based on feasibility. Given typical resources in a field, which effect sizes can you actually reliably study? 

You make implicit choices about which affects are too small to matter all the time based on the feasibility or the resources that you're willing to invest in your next study. As explained earlier, the maximum number of observations that you're willing to collect determines the smallest effect that you can detect. We will discuss this topic further below.

Thinking about your smallest effect size of interest, shows how statistics and theory interact. If you make predictions, you need to be able to design studies that are informative for the theoretical predictions. So always think about the smallest effect size of interest when you're designing studies. 
 
## The small telescopes approach {#smalltelescopes}

Ideally, as De Groot (1969) mentioned, researchers who publish novel research would always specify which effects would disprove their theory. Regrettably, this is not yet common practice. This is particularly problematic when a researcher performs a close replication of earlier work. Because it is never possible to prove an effect is exactly zero, and the original authors seldom specify which range of effect sizes would falsify their hypotheses, it has proven to be very difficult to interpret the outcome of a replication study. When does the new data contradict the original finding?  

Consider a study in which you want to test the idea of the wisdom of crowds. You ask 20 people to estimate the number of coins in a jar, expecting the average to be very close to the true value. The research question is whether the people can on average correctly guess the number of coins, which is 500. The observed mean guess by 20 people is 550, with a standard deviation of 100. The observed difference from the true value is statistically significant, *t*(19)=2.37, *p* = 0.0375, with a Cohen’s d of 0.5. Can it really be that the group average is so far off? Is there no Wisdom of Crowds? Was there something special about the coins you used that make it especially difficult to guess their number? Or was it just a fluke? You set out to perform a close replication of this study.

You want your study to be informative, regardless of whether there is an effect or not. This means you need to design a replication study that will allow you to draw an informative conclusion, regardless of whether the alternative hypothesis is true (the crowd will not estimate the true number of coins accurately) or whether the null hypothesis is true (the crowd will guess 500 coins, and the original study was a fluke). But since the original researcher did not specify a smallest effect size of interest, when would a replication study allow you to conclude the original study is contradicted by the new data? Observing a mean of exactly 500 would perhaps by some be considered quite convincing, but due to random variation you will (almost) never find a mean score of exactly 500. A non-significant result can’t be interpreted as the absence of an effect, because your study might have too small a sample size to detect meaningful effects. So how can we move forward and define an effect size that is meaningful? How can you design a study that has the ability to disconfirm a previous finding?  

Uri Simonsohn (2015) defines a small effect as “**one that would give 33% power to the original study**”. In other words, the effect size that would give the original study odds of 2:1 *against* observing a statistically significant result if there was an effect. The idea is that if the original study had 33% power, the probability of observing a significant effect, if there was a true effect, is too low to reliably distinguish signal from noise (or situations where there is a true effect from situations where there is no true effect). Simonsohn (2015, p. 561) calls this the **small telescopes approach**, and writes: “Imagine an astronomer claiming to have found a new planet with a telescope. Another astronomer tries to replicate the discovery using a larger telescope and finds nothing. Although this does not prove that the planet does not exist, it does nevertheless contradict the original findings, because planets that are observable with the smaller telescope should also be observable with the larger one.”  
Although this approach to setting a smallest effect size of interest (SESOI) is arbitrary (why not 30% power, or 35%?) it suffices for practical purposes (and you are free to choose a power level you think is too low). The nice thing about this definition of a SESOI is that **if you know the sample size of the original study, you can always calculate the effect size that study had 33% power to detect**. You can thus always use this approach to set a smallest effect size of interest. If you fail to find support for an effect size the original study has 33% power to detect, it does not mean there is no true effect, and not even that the effect is too small to be of any theoretical or practical interest. But using the small telescopes approach is a good **first step**, since it will get the conversation started about which effects are meaningful and allows researchers who want to replicate a study to specify when they would consider the original claim falsified.

With the small telescopes approach, the SESOI is based **only on the sample size in the original study**. A smallest effect size of interest is set only for **effects in the same direction**. All effects smaller than this effect (including large effects in the opposite direction) are interpreted as a failure to replicate the original results. This makes the small telescopes approach formally an inferiority test, where we try to reject the hypothesis that the effect is as large or larger than the effect the original study has 33% power to detect. In this sense, it is a simple one-sided test, not against 0, but against a SESOI.

For example, consider our study above in which 20 guessers tried to estimate the number of coins. The results were analyzed with a two-sided one-sample *t*-test, using an alpha level of 0.05. To determine the effect size that this study had 33% power for, we can perform a sensitivity analysis. In a sensitivity analysis we compute the required effect size given the alpha, sample size, and desired statistical power. Note that Simonsohn uses a two-sided test in his power analyses, which we will follow here – if the original study reported a pre-registered directional prediction, the power analysis should be based on a one-sided test. In this case, the alpha level is 0.05, the total sample size is 20, and the desired power is 33%. We compute the effect size that gives us 33% power and see that it is a Cohen’s d of 0.358. This means we can set our smallest effect size of interest for the replication study to *d* = 0.358. If we can reject effects as large or larger than *d* = 0.358, we can conclude that the effect is smaller than anything the original study had 33% power for. The screenshot below illustrates the correct settings in G\*power, and the code in R is:  


```r
pwr::pwr.t.test(n = 20, sig.level = 0.05, power = 0.33, type = "one.sample", alternative = "two.sided")
```

```
## 
##      One-sample t test power calculation 
## 
##               n = 20
##               d = 0.3577466
##       sig.level = 0.05
##           power = 0.33
##     alternative = two.sided
```

<div class="figure" style="text-align: center">
<img src="images/gpower1.png" alt="GPower output to compute the SESOI based on 33% power." width="100%" />
<p class="caption">(\#fig:gpower1)GPower output to compute the SESOI based on 33% power.</p>
</div>

Determining the SESOI based on the effect size the original study had 33% power to detect has an additional convenient property. Imagine the true effect size is actually 0, and you perform a statistical test to see if the data is statistically smaller than the SESOI based on the small telescopes approach (which is called an inferiority test). If you increase the sample size by 2.5 times, you will have approximately 80% power for this inferiority test, assuming the true effect size is exactly 0 (e.g., d = 0). People who do a replication study can follow the small telescope recommendations, and very easily determine both the **smallest effect size of interest**, and the **sample size** needed to design an informative replication study.

The figure below, from Simonsohn (2015) illustrates the small telescopes approach using a real-life example. The original study by Zhong and Liljenquist (2006) had a tiny sample size of 30 participants in each condition and observed an effect size of d = 0.53, which was barely statistically different from zero. Given a sample size of 30 per condition, the study had 33% power to detect effects larger than d = 0.401. This “small effect” is indicated by the green dashed line. In R, the smallest effect size of interest is calculated using:  


```r
pwr::pwr.t.test(n = 30, sig.level = 0.05, power = 1/3, type = "two.sample", alternative = "two.sided")  
```

```
## 
##      Two-sample t test power calculation 
## 
##               n = 30
##               d = 0.401303
##       sig.level = 0.05
##           power = 0.3333333
##     alternative = two.sided
## 
## NOTE: n is number in *each* group
```

<div class="figure" style="text-align: center">
<img src="images/simonsohn.png" alt="Original figure from Simonsohn (2015) vizualizing the small telescopes approach." width="100%" />
<p class="caption">(\#fig:simonsohn)Original figure from Simonsohn (2015) vizualizing the small telescopes approach.</p>
</div>

We can see that the first replication by Gámez and colleagues also had a relatively small sample size (N = 47, compared to N = 60 in the original study), and was not designed to yield informative results when interpreted with a small telescopes approach. The confidence interval is very wide and includes the null effect (d = 0) and the smallest effect size of interest (d = 0.401). Thus, this study is inconclusive. We can’t reject the null, but we can also not reject effect sizes of 0.401 or larger that are still considered to be in line with the original result. The second replication has a much larger sample size, and tells us that we can’t reject the null, but we can reject the smallest effect size of interest, suggesting that the effect is smaller than what is considered an interesting effect based on the small telescopes approach.

Although the *small telescope* recommendations are easy to use, one should take care not to turn any statistical procedure into a heuristic. In our example above with the 20 referees, a Cohen’s d of 0.358 would be used as a smallest effect size of interest, and a sample size of 50 would be collected (2.5 times the original 20), but if someone would make the effort to perform a replication study, it would be relatively easy to collect a larger sample size. Alternatively, had the original study been extremely large, it would have had high power for effects that might not be practically significant, and we would not want to collect 2.5 times as many observations in a replication study. Indeed, as Simonsohn writes: “whether we need 2.5 times the original sample size or not depends on the question we wish to answer. If we are interested in testing whether the effect size is smaller than d33%, then, yes, we need about 2.5 times the original sample size no matter how big that original sample was. When samples are very large, however, that may not be the question of interest.” This nicely fits with the main theme of this course: Always think about the question you want to ask! Do not automatically follow a 2.5 times n heuristic, and always reflect on whether the use of a suggested procedure is appropriate in a given situation.  


As another example, let’s assume you are trying to replicate a previous result based on a correlation in a two-sided test. The study had 150 participants. The SESOI for a replication of this study that will use an alpha level of 0.05, based on the small telescopes approach, can be calculated using either G\*Power or R. In R, you need the code:  


```r
pwr::pwr.r.test(n = 150, sig.level = 0.05, power = 0.333, alternative = "two.sided")
```

```
## 
##      approximate correlation power calculation (arctangh transformation) 
## 
##               n = 150
##               r = 0.1249937
##       sig.level = 0.05
##           power = 0.333
##     alternative = two.sided
```

The SESOI would thus be set to *r* = 0.125. 

In the age of big data researchers often have access to large databases, and can run correlations on samples of thousands of observations. Let’s assume the original study in the previous question did not have 150 observations, but 15000 observations. We still use an alpha level of 0.05. What is the SESOI based on the small telescopes approach? 


```r
pwr::pwr.r.test(n = 15000, sig.level = 0.05, power = 0.333, alternative = "two.sided")
```

```
## 
##      approximate correlation power calculation (arctangh transformation) 
## 
##               n = 15000
##               r = 0.01250099
##       sig.level = 0.05
##           power = 0.333
##     alternative = two.sided
```

The SESOI is thus *r* = 0.0125. This might be much smaller than is practically relevant. Thus, the small telescope approach is useful to determine a SESOI, but we want to also keep other criteria in mind before settling on a final value. 

## Setting the SESOI based on resources.

When designing a study, you need to justify the sample size you aim to collect. If one of your goals is to observe a *p*-value lower than the alpha level (e.g., 0.05), a commonly used justification for the sample size is a power analysis. A power analysis tells you the probability of observing a statistically significant effect, based on a specific sample size, alpha level, and true effect size.

A power analysis is performed based on some assumption about the effect size you want to be able to detect with reasonably high probability. When you would like to be able to observe an effect with a standardized mean difference in Cohen’s d of 0.5 in an independent two-tailed *t*-test, and you use an alpha level of 0.05, you will have 90% power with 86 participants in each group. What this means, is that we can calculate the expected distribution of observed effect sizes when d = 0.5 and n = 86. In this case, only 10% of the distribution of effects sizes you can expect falls below the critical value required to get a *p* \< 0.05 in an independent *t*-test.  

In Figure \ref{fig:powersesoi}) a power analysis is visualized by plotting the distribution of Cohen’s d given 86 participants per group when the true effect size is 0 (or the null-hypothesis is true), and when d = 0.5. The blue area contains 10% of the distribution when the true effect size is 0.5, and visualizes the 10% of results you can expect to observe in the long run that would yield *p* \> .05. 

<div class="figure" style="text-align: center">
<img src="images/powersesoi.png" alt="Vizualization of a null and alternative distribution with error rates marked." width="100%" />
<p class="caption">(\#fig:powersesoi)Vizualization of a null and alternative distribution with error rates marked.</p>
</div>

You’ve probably seen such graphs before (indeed, G\*power, a widely used power analysis software, provides these graphs as output by default). The only thing I have done is transform the *t*-value distribution that is commonly used in these graphs, and calculated the distribution of Cohen’s d. This is a straightforward transformation (based on the *non-centrality parameter*). Given a test with 86 participants in each group, and an alpha level of 5%, only *t*-tests which yield a *t* ≥ 1.974 will be statistically significant. In other words, *t* = 1.974 is the **critical t-value** (you might have learned that as the sample size becomes large enough, the critical *t*-value goes to 1.96).

Because I find *t*-values are somewhat difficult to interpret, my figure does not show *t*-distributions, but the distribution of the effect size Cohen’s d. This means that instead of having a critical *t*-value, we can read off the **critical d-value**. With n = 86 in each group the critical d-value is 0.3. This means that only effects larger than 0.3 will yield a *p* \< α. You can see the vertical line at the critical d-value.

Let’s explore what this means in an interactive version of the figure above. Go to <http://shiny.ieis.tue.nl/d_p_power/> where you will be able to change the values such as the sample size, the effect size, and the alpha level, that generate the figure. The default values for the shiny app are a true effect of d = 0.5, 50 participants per group, and an alpha level of 0.05. If you reload the webpage, it will reset to these default values.  

The blue area in the figure is the **Type 2 error rate** (the probability of not finding *p* \< α, when there is a true effect), or **1 - power**. If the true effect size is d = 0.5, most of the observed effects will fall on the right of the critical d-value. To be precise, the statistical power based on an alpha of 0.05, 50 participants in each group, and assuming the true effect size is d = 0.5 is 69.69% (this number is provided in the text below the sliders). Thus, 30.31% of the effect sizes we will observe fall below d = 0.4 (our critical d-value) and will be non-significant.  
Move the slider for Cohen’s d to 0.79. You will now see that the blue area under the alternative distribution has the same size as the red area in the right tail of the null distribution. This distribution on the left is centered at 0 – it is the distribution of effect sizes that we can expect if the null hypothesis is true, and the effect size is exactly 0. The red areas in this distribution visualize Type 1 errors in a two-sided test. If the null-hypothesis is true, observing an effect larger than the critical d value is a Type 1 error in the positive direction. Because the figure illustrates a two-sided test, an equally extreme effect size in the negative direction (d \> -0.4) would also be a Type 1 error.

Three sliders influence what the figure looks like: The sample size per condition, the true effect size, and the alpha level. The critical d-value is influenced by the sample size per group, the alpha level, but **not** by the true effect size. Although it is common to talk about ‘the power’ of a study, statistical power is not a single value: It is a curve. When a study is designed, the alpha level and the sample size are chosen before the data is collected, and can thus be considered fixed when calculating power. But the true effect size is unknown, and therefore it makes more sense to think about power as a **power curve** across all possible effect sizes, as illustrated in the figure below.

<div class="figure" style="text-align: center">
<img src="images/powercurve1.png" alt="Power curve." width="100%" />
<p class="caption">(\#fig:powercurve1)Power curve.</p>
</div>

This figure (which is also available in the online Shiny app, in the bottom right) visualizes that power is low for small effect sizes close to 0, being low for effects up to d = 0.4, and generally considered sufficient (upwards of 80%) from d = 0.6. Therefore, a study never has high power, or low power. It has high power for specific effects, and low power for other effects. When the true effect size is 0, power is formally undefined, but in the power formula, it ends up at the Type 1 error rate (which you can check in the shiny app by moving the alpha level up or down).

It needs a little explanation how we can have low power for small effects (e.g., in the figure above, 17% power for a **true effect** of d = 0.2), while the critical d-value is 0.4, and **observed effects** smaller than d = 0.4 will never be statistically significant. Both these statements are true, and the difference between a ‘true’ population effect and an ‘observed’ sample effect is very important. To see why, move the slider of Cohen’s d to d = 0.2, which yields the figure below.

<div class="figure" style="text-align: center">
<img src="images/lowpower.png" alt="Visualization of lower power." width="100%" />
<p class="caption">(\#fig:lowpower)Visualization of lower power.</p>
</div>

We see that the critical d-value has not changed: It is still true that only effects larger than d = 0.4 will be statistically significant. However, we also see from the distribution that we can expect some *observed effect sizes* to be larger than 0.4 when the *true population effect size* is d = 0.2 – the text tells us that 16.77% of *observed effect sizes* will be larger than 0.4 in the long run. That is not a lot, but it is something. For example, the critical d-value is 0.4. The true effect size is 0.2 in the *population*. In your *sample*, you will in the long run sometimes observe effect sizes larger than d = 0.4, and these effects would be statistically significant. In the figure above, if we have extreme publication bias and only significant results are published, we would end up with effect size estimates that are all larger than d = 0.4, even though the true effect size is 0.2.

It is now (hopefully) clear that it is possible to have low power for a *true effect size* that is smaller than the critical d-value. Even when the true effect size is smaller than the critical d-value, some of the *observed effect sizes* of your samples will be larger than the critical d-value. However, only overestimated effect sizes (i.e., observed effect sizes that are larger than the true effect size) will be statistically significant. This is the reason why publication bias combined with underpowered research is problematic: It leads to a large **overestimation of the true effect size** when only observed effect sizes from statistically significant findings in underpowered studies end up in the scientific literature

In addition to some basic insights into statistical power, the Shiny app can be used to see what the smallest observed effect size is that can be detected in a study with a **specific sample size** and **alpha level**. Because this **critical d-value** is independent of the true effect size (which is typically unknown) it is a way to evaluate the observed effect sizes that could have been statistically significant in a study with a certain sample size and alpha level.

For example, imagine researchers performed a study with 18 observations in each condition, and performed a *t*-test using an alpha level of 0.01. The the smallest effect size that can be statistically significant in this study is a Cohen's d of 0.91. If you collect a small number of of observations, you can only expect large effects to become statistically significant. If you are interested in smaller effects, you need to collect more data.

## Setting the smallest effect size of interest in replication studies  

If you attempt to replicate a study, one justifiable option when choosing the smallest effect size of interest (SESOI) is to use the smallest observed effect size that could have been statistically significant in the study you are replicating. In other words, *you decide that effects that could not have yielded a p-value less than α in an original study will not be considered meaningful in the replication study*. **The assumption here is that the original authors were interested in observing a significant effect, and thus were not interested in observed effect sizes that could not have yielded a significant result**. It might be likely that the original authors did not consider which effect sizes their study had good statistical power to detect, or that they were interested in smaller effects but gambled on observing an especially large effect in the sample purely as a result of random variation. Even then, when building on earlier research that does not specify a SESOI, a justifiable starting point might be to set the SESOI to the smallest effect size that, when observed in the original study, **would have been statistically significant**. Not all researchers might agree with this (e.g., the original authors might say they actually cared just as much about an effect of d = 0.001). However, as we try to change the field from the current situation where no one specifies what would falsify their hypothesis, or what their smallest effect size of interest is, this approach is one way to get started. I see this approach as a tennis match. Original authors serve and hit the ball across the net, saying ‘look, something is going on’. The approach to set the SESOI to the effect size that could have been significant in the original study is a return volley which allows you to say ‘there does not seem to be anything large enough that could have been significant in your own original study’. This is never the end of the match – the original authors can attempt to return the ball with a more specific statement about effects their theory predicts, and demonstrate such a smaller effect size is present.

In practice, this will often mean setting the SESOI to the effect size the original study had approximately 50% power to detect (given the fact that in large studies where the main test is an independent *t*-test, a study with *p* = 0.05 has an observed power of 50%, see [Lenth, 2007](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.75.1246&rep=rep1&type=pdf)). This effect size can be calculated using a sensitivity power analysis (for example in G\*Power). In this sense, this approach is very similar to the small telescopes approach by Simonsohn (2015), except we calculate the effect size the original study had 50% power for, instead of 33% power.  

### Setting the SESOI based on theoretical predictions  

If you are not building on previous studies, the SESOI can be set based on **theoretical predictions**, or a **cost-benefit analysis** that specifies the smallest effect size that would be practically relevant. Sometimes, an intervention should have a specific effect size to be worthwhile (for example, financially). Testing against a SESOI based on cost-benefit analysis allows you to decide if an intervention is worth it, when weighed against the costs.  

Take a moment to think about whether the **theory** you are building on makes a quantifiable prediction that would allow you to set a smallest effect size of interest. then take a moment to think about whether the topic you study allows you to make a **cost-benefit analysis**, where an effect size needs to be large enough to be worthwhile.  

### Setting the smallest effect size of interest based on resources  

Not all experiments are designed to test quantifiable theoretical predictions, nor do they allow for a cost-benefit analysis. Researchers often have more precise ideas about the amount of data that they can afford to collect, or that **other researchers in their field commonly collect**, than about the effect size they predict or that would be worth studying. The amount of data that is collected limits the inferences one can make. Given the alpha level and the planned sample size for a study, researchers can **calculate the smallest effect size that they have sufficient resources to detect**.

Setting the smallest effect size of interest based on this approach does not answer any theoretical question (after all, the SESOI is not based on any theoretical prediction). Instead, it answers a **resource question**: Given an available sample size, or given a sample size common in a field, is the effect large enough so that we can reliably study it? If the answer is ‘NO’ **this does not mean that the effect is not interesting per se** – it is just not interesting given the resources researchers have available. If effects larger than a resource based SESOI are rejected, a field might decide that it is time to examine the research question collaboratively, by coordinating research lines, and collecting enough data in a team to reliably study it.

For example, imagine a line of research in which a hypothesis has almost always been tested by performing a one-sample t-test on a sample size smaller than 100 observations. A one-sample t test on 100 observations, using an alpha of .05 (two sided), has 80% power to detect an effect of d = 0.28 (as can be calculated in power software such as G\*Power, or using the R code below).


```r
pwr::pwr.t.test(n = 100, sig.level = 0.05, power = 0.80, type = "one.sample", alternative = "two.sided")$d  
```

```
## [1] 0.2829005
```

In a new study, concluding that one can reliably reject the presence of effects more extreme than d = 0.28 suggests that sample sizes of 100 might not be enough to detect effects in such research lines. Rejecting the presence of effects more extreme than d = 0.28 does not test a theoretical prediction, but it contributes to the literature by answering a **resource question**. It suggests that future studies need to collect data on samples larger than 100 observations to examine this hypothesis. Note that statisticians and theoreticians are likely not impressed by such resource questions, but they are, I think, very relevant for researchers who have to decide whether they can actually pursue a line of research in practice in individual labs given their resources. If smaller effects are deemed worthwhile to study, and each lab can realistically collect 100 observations per study, **it is time to collaborate**. An example of such a collaboration is the [Psychological Science Accelerator](https://psysciacc.org/).  

The example we have used above concerned an independent *t*-test, but the idea can be generalized. A shiny app for an F-test is available here: <http://shiny.ieis.tue.nl/f_p_power/>. The effect size associated to the power of an F-test is partial eta squared ($\eta_{p}^{2}$), which for a One-Way ANOVA (visualized in the Shiny app) equals eta-squared.  

The distribution for eta-squared looks slightly different from the distribution of Cohen’s d, primarily because an *F*-test is a one-directional test (and because of this, eta-squared values are all positive, while Cohen’s d can be positive or negative). The light grey line plots the expected distribution of eta-squared when the null is true, with the red area under the curve indicating Type 1 errors, and the black line plots the expected distribution of eta-squared when the true effect size is η = 0.059. The blue area indicates the expected effect sizes smaller that the critical $\eta$ of 0.04, which will not be statistically significant, and thus will be Type 2 errors.  

<div class="figure" style="text-align: center">
<img src="images/powerf.png" alt="Null and alternative distribution for partial eta squared." width="100%" />
<p class="caption">(\#fig:powerf)Null and alternative distribution for partial eta squared.</p>
</div>

Every sample size and alpha level implies observed effect sizes that can be statistically significant in your study. Looking at which observed effects you can detect is a useful way to make sure you could actually detect the smallest effect size you are interested in.
