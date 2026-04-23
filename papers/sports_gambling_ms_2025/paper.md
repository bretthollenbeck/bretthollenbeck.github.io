# The Financial Consequences of Legalized Sports Gambling
**Brett Hollenbeck, Poet Larsen, Davide Proserpio**

*Management Science.* Forthcoming.

---

# Introduction

In 2018, the U.S. Supreme Court ruled that the Professional and Amateur Sports Protection Act (PASPA), which prohibited states from authorizing and regulating sports gambling, was unconstitutional. Since the ruling, 38 states have legalized some form of sports gambling. Before this, almost all legal gambling in the U.S. came in the form of tribal casinos with limited gaming options, commercial casinos in a small number of jurisdictions, and state lotteries [@kearney_gambling]. The new availability of legal sports betting and growth in mobile accessibility represent a substantial increase in gambling accessibility. Between 2018 and 2023, nearly \$300 billion has been wagered via newly legalized sports gambling markets, with most bets flowing through online channels.[^4]

While for many, gambling is a relatively inexpensive and generally harmless form of recreation, there is a fraction of so-called "problem gamblers," for whom gambling is associated with a range of serious harms [@meyer_et_al_book]. These include financial stress, disruption of family life and relationships, health problems, worsening of job performance, criminal activity, and even suicide [@shaffer2002gambling; @gabellini_metastudy; @clarida2020empirical]. The bulk of prior research into the factors associated with problem gambling comes from the period before legalized sports gambling and, therefore, has focused on either commercial casino gambling or illegal gambling [@gabellini_metastudy]. In addition, it's unclear whether to view negative correlations between gambling and health from prior research as causal, as unobserved underlying factors, such as psychological or environmental factors, could drive both.

This paper studies the causal impact of legalized sports gambling on consumer financial health using variation in sports gambling introduction across states and over time following state-by-state legalization during 2018--2023. To do so, we leverage data from the University of California Consumer Credit Panel (UC CCP), which contains detailed financial information from a nationwide credit bureau for a sample of roughly 7 million U.S. adults. This data includes credit scores, credit card balances, loan delinquency information, and many other measures of financial health.

We study the impact of sports gambling on a set of key financial health indicators. We first test for changes in consumer credit scores, an overall summary indicator of a person's financial health or creditworthiness. Next, we measure changes in indicators associated with consumers taking on problematic levels of debt: bankruptcies, total debt collections, use of debt consolidation loans, credit card delinquencies, and auto loan delinquencies.

We consider two definitions of treatment. First, we focus on all states that implemented legal sports gambling, with the treatment date set to the first month in which any form of sports gambling became legal (online or offline). Next, we differentiate between sports gambling that occurs offline at designated retail locations, such as casinos, and that which occurs online, typically via mobile apps, and is available throughout a state. In doing so, we define an additional treatment that measures the incremental effect of legalizing online gambling (conditional on having legalized retail gambling). To do so, we consider states that implemented legal online gambling at some point (in addition to retail gambling) and use the first date on which statewide online betting was available as the treatment start date.

Our empirical strategy leverages the staggered state-by-state rollout of legal sports gambling. In doing so, we implement a staggered Difference-in-Differences (DD) and compare how financial outcomes evolve in treated states (before and after the policy) with those in states that did not implement legal sports gambling or did so at a later date. The primary challenge in isolating the causal effect on consumer financial outcomes is the possibility that the legalization of sports betting in certain states is correlated with unrelated state-level trends in economic conditions, budgetary conditions, or other policies that correlate with our financial outcomes of interest.[^5] To reduce this concern, we test first for cross-sectional differences across treated and control states in financial assistance levels or social insurance programs like unemployment insurance before, during, or after the 2020 COVID pandemic.

Second, we show that the timing of legalization is largely uncorrelated with factors that may be correlated with consumer financial health, including economic trends and state-level budget and debt measures. Finally, using the Oxford COVID dataset, we test for changes in COVID-19 economic policies across states at the time of treatment and find little variation.

Because treatment is staggered and treatment effects may be heterogeneous over time and across groups, we follow best practices in estimation by employing the staggered DD estimator proposed by [@CALLAWAY2021200]. This estimator is robust to treatment heterogeneity in time and by groups of treated states, and it allows us to easily estimate dynamic treatment effects and test for parallel trends across states in the pre-treatment period.

We find that across all states that implemented legal sports betting, there is a small but significant decrease in the average credit score. In states that additionally allow online gambling on top of retail sports gambling, the decrease is over ten times as large, suggesting that legal sports gambling worsens consumer financial health, especially when statewide mobile access is allowed. Next, we turn to signs of problematic debt loads. For the full set of states that legalize any form of sports gambling, we find that only one of our measures (auto loan delinquencies) increases by a statistically significant amount (8%). By contrast, when we focus on the effects of online access to sports gambling relative to retail, we find increases in bankruptcy rates (roughly 25%), credit card and auto loan delinquencies (roughly 25% and 27%, respectively), and collections on accounts (9%). The rise in bankruptcy rates translates to 1 more bankruptcy per $10,000$ financially active consumers, or roughly 30,000 more personal bankruptcies in the US per year.

We perform five robustness checks to reinforce the causal interpretation of these results. First, we re-estimate our models using a matched sample created using demographic and economic covariates. Second, we include pre-treatment economic controls correlated with treatment timing, such as the unemployment rate and the low-income rate. Third, we implement a border strategy similar to [@shapiro2018positive] and consider only counties at the borders of states that legalize sports gambling. Fourth, we use data from the University of Oxford COVID-19 Government Response Tracker (OxCGRT) [@hale2021global] to obtain time-varying indexes related to states' COVID-19 response policies to test for differences in states' COVID-19 response policies, such as the economic support index, government response index, and stringency index. We then estimate our DD using these indices as outcomes and find insignificant differences, alleviating concerns that differences in COVID-19 response policies could bias our estimates. Finally, we show that our results are not driven by the introduction of iGaming (online or mobile access to a broad range of gambling formats beyond betting on sporting events, including lotteries, slots, and casino games like poker). To do so, we exclude from estimation the six states that legalized iGaming during our observation period.

We conclude the paper by examining the heterogeneous impact of legalized online sports gambling. We test for heterogeneous treatment effects by credit score levels in the pre-treatment period. Specifically, we divide consumers into three categories: Sub-prime, Prime, and Super-prime using denominations from well-established credit score categories used by credit agencies. We find that the adverse effects on financial health are concentrated among Sub-prime and Prime borrowers, i.e., those who were already financially constrained before the implementation of online sports gambling.

Finally, while some effects on the average consumer seem relatively small, it is important to remember that we do not observe which members of the credit panel are actively engaged in sports betting. Therefore, we can only estimate the average effect across the overall population. Because most residents of treated states are unlikely to be problem gamblers,[^6] the average effect on the gambling population is much larger than the effects we document here.

While states benefit from sports gambling in the form of additional tax revenue, there is growing concern that easing access to sports gambling may come at the expense of some consumers whose financial health deteriorates.[^7] Our paper provides evidence that this concern is well-founded by quantifying the extent to which the recent expansion of sports gambling impacts consumer financial health.

# Literature: Sports Gambling and Financial Health

We contribute to the study of the causal effects of gambling on financial outcomes, as well as to the growing literature on the impact of the introduction of widespread legal sports betting in the United States.

A large body of previous research finds that gambling is associated with adverse outcomes, including financial difficulties, debt accumulation, and mortgage delinquencies [@griffiths2009problem; @wardle2011defining; @clarida2020empirical]. Prior economic research on gambling has placed a particular emphasis on studying the relationship between gambling and personal bankruptcies. Using county-level bankruptcy results, existing economic literature has generally found that access to casinos and state lotteries lead to increasing bankruptcy rates [@barron2002impact; @goss2009have; @daraban2011estimating; @grote2014impact]. This research has also shown that the associations between gambling and adverse outcomes are more common among specific demographic groups, such as young adults and individuals with lower socioeconomic status [@binde2009exploring; @hing2015sports; @hahmann2021problem], as well as other risk factors like impulsivity and psychological distress [@wood2007problem; @hing2015maintaining]. Past research has also found that ease of access may exacerbate gambling-related financial harm, as individuals can place bets anytime and anywhere, leading to increased gambling frequency and expenditure [@wood2007problem; @gainsbury2015interaction; @laplante2011disordered; @nordmyr2014associations]. However, relatively little research has found causal associations between financial outcomes and gambling access. We contribute to the broad literature on gambling by studying causal links between access to gambling and a range of financial outcomes using the state-by-state rollout of legal sports betting.

Closely related to our work are two working papers studying different impacts of the spread of legal sports betting on financial outcomes.[^8] First, our work complements work by [@baker_et_al_gambling], who use customer-level credit and debit transactions provided by a financial institution to identify who is transferring money to sports gambling apps and how their credit card debt and consumption patterns change when they do so. In a sample of 230,000 households, they find that about 8% use sports betting apps, and that conditional on doing so, lose an average of \$1,100 per year. They find that those who bet on average invest less and experience an increase in credit card debt.

Second, a recent working paper [@taylor2024online] estimates the causal effect of sports gambling legalization on irresponsible gambling behavior. Using an individual-level credit card panel dataset, they find that legalization increases gambling and irresponsible gambling behavior, particularly among those who were previous gamblers. While, unlike these papers, our sample does not identify which specific individuals adopt gambling, we are able to use a much larger sample that is representative of financially active U.S. consumers to measure average effects in the population. We complement their findings on gambling adoption by studying the impacts on a broad range of financial health outcomes, such as excessive debt usage and bankruptcy.

# Background and Data {#sec:data}

This section provides an overview and history of state-level legal sports gambling regimes. We then introduce our primary data source, the University of California Consumer Credit Panel (UC-CCP), and provide some high-level summary statistics for this data.

## Background on Legal Gambling

In May 2018, the Supreme Court overturned the Professional and Amateur Sports Protection Act (PAPSA), deeming it unconstitutional and infringing on states' rights. This opened the door for individual states to legalize and regulate sports betting. Before this ruling, only Nevada offered legal sports betting. Within just one month of this ruling, Delaware and New Jersey launched retail sports betting at casinos and racetracks, with many states following in the years since. As of February 25, 2025, 39 states and the District of Columbia have legalized some form of sports betting.[^9]

There is a wide variety of different state-level regulations and tax structures for sports betting. The most notable decision is whether to allow online (typically mobile) betting or require bets to be placed in person at a qualified location. During our sample period, 23 states and DC chose to allow some form of online betting. As shown in Table [3](#tab:treat-start) in Appendix [8](#apx:tables), many states in our data implemented legal retail betting before mobile betting, a variation that we exploit to measure the impact of online gambling conditional on having legalized retail gambling.

Other policy choices states face include the market licensing structure, the tax rate levied, and the tax base. For a more in-depth discussion about these policies, see Appendix [9](#sec:sports-policy-variation). In Figure [1](#fig:sports-handle-state-legalization), we show how the total amount bet on sporting events (dark series) has grown over time along with the number of states with legal sports gambling (gray series).[^10] In Table [5](#tab:handles-by-state) in Appendix [8](#apx:tables), we report the total amount bet by state and for both online and retail channels during our data period (2018 to June 2023).

<figure id="fig:sports-handle-state-legalization" data-latex-placement="ht">
<embed src="figures/descriptive-plots/monthly_handle_state_legalization.pdf" style="width:60.0%" />
<figcaption>Monthly sports handle in billions and the number of states with legal sports gambling. The left-hand axis shows the sports handle, and the right-hand axis shows the number of legalized states. Our data do not include handles for states in which tribal lands offer sports gambling.</figcaption>
</figure>

## Consumer Credit Data

Our primary dataset is the University of California Consumer Credit Panel (UC-CCP). It contains anonymized individual-level records of a nationally representative 2% sample of U.S. adults with a credit report (i.e., roughly 7 million panelists). Data is tracked from 2004 to the present day. For each year, we observe records from March, June, September, and December.[^11] We observe demographic characteristics for nearly all individuals. This includes information such as age, gender, and ethnicity. The panel also contains modeled and/or self-reported information such as occupation, if the individual owns a home, marital status, and if the individual has children.[^12]

We observe account information across all open and closed accounts for each individual-month combination. This includes mortgages, student loans, auto loans, credit cards, secured and unsecured loans, debt consolidation loans, debt buyer accounts, and collections. Information includes when the account was opened, the most recent account balance, the most recent payment amount, the amount past due, if the account is delinquent, what type of business the account is associated with, and, in the case of loans, various loan categories such as personal or medical.

We restrict our panel to individuals who maintain at least one active account and are not deceased. We also remove any individual who moved across state lines to prevent treatment-control spillovers, and any individual whose demographic information is missing, particularly location and gender. Our final dataset contains observations for $4,382,529$ unique individuals and 90 million quarterly observations over seven years, from March 2016 to June 2023.

## Types of Gambling Access

We study the causal impact of gambling access on financial health using the potential outcomes framework to measure treatment effects, and consider two types of treatment definitions.

#### General Access.

The first treatment definition is meant to capture the overall effect of any gambling legalization. It defines a state as treated after the first month a state begins reporting state tax revenue from any sports gambling operations. In our analysis, we refer to this treatment as "General Access." Note that states may offer online, offline, or both forms of gambling. The rollout of channels may occur at different times. For example, in Pennsylvania, casinos began accepting offline wagers in November 2018, with online gambling beginning in May 2019. In the "General Access" category, we define Pennsylvania's treatment start time as November 2018. This model captures the shift from no access to sports gambling to some form of access. The estimated effect is an average across retail-only, retail-and-online, and online-only periods, compared to periods in which gambling is not implemented. In Table [4](#tab:treatment-status-by-state) of Appendix [8](#apx:tables), we report the list of states included in this treatment and their treatment status. All 33 states that implemented any form of legal sports gambling before June 2023 are considered treated, while the rest are controls.

#### Retail-to-Online Access.

Our second treatment captures the incremental effect of online sports gambling relative to retail sports gambling. We refer to this group as "Retail-to-Online Access". To isolate the incremental impact of online sports gambling, we restrict the sample to (i) states that offer retail sports gambling and eventually offer online gambling, (ii) states that implemented only legal retail sports gambling, and (iii) the periods after the implementation of retail sports gambling. Therefore, we exclude states that never implemented any form of sports gambling, as well as those that implemented only online gambling (Tennessee and Wyoming) or implemented online gambling before retail gambling (Virginia, New Hampshire, and Washington, D.C.). In Table [4](#tab:treatment-status-by-state) of Appendix [8](#apx:tables), we report the list of states included in this treatment and their treatment status. The sample consists of 28 states, of which 19 are eventually treated (i.e., introduced online sports gambling).

With this sample restriction, the model identifies the incremental effect of online gambling (conditional on retail availability) by comparing changes in outcomes before and after the introduction of online gambling in retail-first states with changes observed in retail-only states and in states with retail access that have not yet implemented legal online gambling.[^13]

This ATT is particularly relevant from a policy standpoint because the vast majority of states with legalized sports gambling have already established retail operations. As such, the policy debate now centers not on whether to introduce sports gambling, but on whether to expand existing retail markets to include online access. Studying the transition from retail access to online access, therefore, captures the most common and policy-salient form of market expansion. In contrast, transitions from no gambling to online-only access are relatively rare and represent a less typical policy pathway. By focusing on the shift from retail to online, our analysis aligns with the prevailing policy environment.

## Primary Outcomes of Interest

Our analysis focuses on six outcomes designed to capture overall financial health and the presence of excessive debt.

#### Overall financial health

Our data includes consumer VantageScore credit scores, which range from 300 to 850. A credit score is a numerical expression based on a level analysis of an individual's credit files, representing their creditworthiness. Credit reporting agencies use predictive models that incorporate information, including consumers' spending history, depth of credit, length of credit, and existing balances, to calculate credit scores.[^14] These scores are then used by lenders to evaluate the risk of lending money to consumers and to mitigate losses due to bad debt. Decreases in consumer credit scores represent lower consumer creditworthiness. Our data observes a consumer's credit score in a given quarter.

#### Indicators of excessive debt

Next, we consider five measures of excessive debt. The first is bankruptcy, which captures instances in which consumers do not believe they can reasonably repay outstanding debts and need to manage or restructure their finances to pay off debts over time. Filing for bankruptcy is a serious financial decision that requires a consumer to go to bankruptcy court. It harms a consumer's credit score and is a significant indicator of financial stress.

In our data, bankruptcy filings are tracked monthly. To align it with our quarterly data, we count the number of bankruptcies by individual over the three months between quarters. For example, for the March quarterly observation, we sum up bankruptcies by individual during January, February, and March. We then create a binary indicator that equals 1 if a consumer has filed any bankruptcy (Chapter 7, 11, 12, or 13) in the quarter, and 0 otherwise.

The second is the total amount of debt on an account that has been sent to collections. This is a measure of the amount of unpaid debt that the consumer's creditors have assigned to collection agencies. When a consumer misses payments, or a lender does not expect to receive payment on a debt, the lender may sell the debt to a collections agency or coordinate with a collections agency to manage the collection process. Any missed debts can be sent to collections. A debt going to collections can seriously harm a consumer's credit score. For each individual in our data, we observe all debts sent to collections on file and their amounts. Unfortunately, we do not know which specific debts the collections originate from (e.g., medical or credit cards). We only know the collection amount and whether it is on the consumer's account. We also do not know the reason for a dropped collection's debt from a consumer's record. It could be because the individual pays off the debt, restructures in a bankruptcy, or takes some other action to remove the debt from their account.[^15]

The third is the use of debt consolidation loans, a financial strategy for managing and reducing debt by combining multiple debts into a single, more manageable loan. This approach is often used by individuals with high debt levels and multiple creditors, particularly if they face high interest rates on loans or credit cards. Prior survey and observation work finds that gamblers with high levels of debt may use debt consolidation loans [@downs2009gambling]. In our data, we observe when a consumer takes out a debt consolidation loan. To measure changes in consolidation loan usage, we create a binary indicator variable equal to one if a consumer has an open debt consolidation loan.

Finally, we study credit card and auto loan delinquencies, which indicate missed payments and are strong indicators of financial distress. Delinquencies on credit cards and auto loans are typically reported when a consumer has missed 1-2 monthly payments. In our data, we observe when a consumer's credit card or auto loan is flagged as delinquent. We analyze changes in the likelihood that a consumer has any delinquent credit card or auto loan on file. For each separate outcome, we create a binary variable indicating whether a consumer has at least one actively delinquent account in a given quarter.

Table [1](#tab:parameters-pre-period-ss) presents summary statistics at the county level from the pre-legalization period for our six dependent variables across all states.[^16]

::: {#tab:parameters-pre-period-ss}
  ----------------------- ------- ---------- --------- ----------- --------- ------------

  Dependent Variable         Min.    1st Qu.    Median        Mean   3rd Qu.         Max.

  Credit Score              $580$    $695.4$   $714.3$     $712.9$   $732.1$      $800.3$
  Pr(Bankruptcy)                0          0         0   $0.00058$         0        $0.1$
  Collections                 $0$    $167.5$   $313.9$     $391.2$   $522.2$   $10,338.9$
  Pr(CC Delinquency)          $0$   $0.0125$   $0.022$     $0.025$   $0.033$        $0.5$
  Pr(Auto Loan Delinq.)       $0$    $0.017$   $0.034$     $0.039$   $0.053$          $1$
  Pr(Consol. Loan)              0          0         0   $0.00086$         0      $0.072$

  ----------------------- ------- ---------- --------- ----------- --------- ------------

  : Pre-treatment summary statistics.
:::



## Additional data

To perform some of the identification and robustness checks, we collected economic and demographic county-level variables from the US Census Bureau. Specifically, we collected county-level population, the proportion of men under age 45, the unemployment rate, the poverty rate, household income, and the share of the population with a bachelor's degree or higher. We also collected information about each state's budget and debt from 2012 to 2022 from the Annual Survey of State and Local Government Finances (ALFIN).

# Empirical Strategy {#sec:strategy}

We exploit the staggered legalization of sports gambling across states to measure its impact on consumer financial health. We do so by implementing a difference-in-differences (DD) identification strategy that compares changes in average outcomes before and after legalization relative to the changes in these outcomes for states that did not yet implement legal sports gambling or that never implemented it over the same period. While DD is typically implemented using a Two-Way Fixed Effect (TWFE)---county and year-quarter in our case---recent literature has pointed out some shortcomings of this estimator [@borusyak2024revisiting]. In particular, in cases where there is treatment heterogeneity by treatment group (in our case, groups of states treated at the same time) or over time, TWFE can yield biased estimates. To avoid this issue, econometricians have developed a set of alternative estimators [@CALLAWAY2021200; @gardner2022two; @borusyak2024revisiting]. In this paper, we rely on the proposed method by [@CALLAWAY2021200], which we refer to as the CS estimator. For computational tractability, we aggregate our data to the county level and weight county-level observations by the average number of individuals present in the data in 2015. The estimated Average Treatment on the Treated (ATT) can be interpreted as the average change in financial outcomes for individuals in states that implemented legal sports gambling.

## Identification Checks {#sec:id-checks}

Since states decide whether to legalize sports gambling, the primary concern is that unrelated trends in consumer financial outcomes correlate with state-level decisions to legalize it. One particular concern is that states that choose to legalize sports betting to generate revenue do so because of budgetary problems and, consequently, are less able to provide social assistance during economic shocks such as the COVID pandemic.

We test for this possibility in two ways. First, we test for cross-sectional differences between treated and control states across various social assistance programs and COVID-19 fiscal responses. We compare states across 13 policies. As shown in Table [2](#tab:legal_nonlegal_diff_truncated), we find no significant differences in these policies.

::: {#tab:legal_nonlegal_diff_truncated}
  Policy                                                         Treated     Control      t
  -------------------------------------------------------------- ---------- ---------- --------
  2020 UI maximum amount (\$)                                    490.152     459.235    -0.744
  COVID Expanded eligibility for UI (high-risk individuals)      0.242        0.176     -0.542
  COVID Expanded eligibility for UI (lost childcare/school)      0.424        0.294     -0.906
  COVID Expanded eligibility for UI (quarantined or caregiver)   0.848        0.824     -0.218
  COVID Extended UI duration (indicator)                         0.061        0.059     -0.025
  2021 UI maximum duration (weeks)                               25.455       23.941    -1.551
  January 2020 UI maximum duration (weeks)                       24.848       22.706    -1.567
  July 2020 UI maximum duration (weeks)                          25.333       23.765    -1.293
  Reinstated one week waiting period for UI                      0.515        0.647     0.888
  Reinstated work search requirement for UI                      0.485        0.647     1.092
  Stopped Participating in Federal UI Programs                   0.364        0.588     1.502
  Waived work search requirement for UI                          0.939        0.941     0.025
  Weekly UI maximum amount with extra stimulus (\$)              1090.152    1059.235   -0.744
  Cumulative State Fiscal Debt 2015--2017 log(\$)                17.561       17.332    -0.702

  : Fiscal policies of treated and control states.
:::



The second test we perform relates to the timing of gambling accessibility. We estimate the relationship between the timing of policy implementation at the state level and local economic indicators that likely affect our dependent variables. These variables come from the US Census and ALFIN and include state-level number of COVID-19 cases, proportion of the population with a college education, poverty rates, unemployment rates, median household income, state-level population, young men population, and measures of state fiscal capacity, namely the one-year and three-year net budget position and the log of cumulative state debt. We use a Cox Hazard model to test whether these variables correlate with the timing of a state's first introduction of retail or online sports gambling.

Any significant effects suggest that those variables correlate with the timing of sports gambling implementation. However, it is unlikely that a significant correlation in this hazard model reflects a causal relationship between the independent variable and the timing of sports gambling implementation, as the implementation date was often set well in advance of legalization. The estimates also don't indicate whether there are differences between the treated and control states; the model only shows that, when treatment occurred, the independent variables were higher or lower.

We estimate one model with all states for General Access and another model for Retail-to-Online Access. All results can be found in Table [\[tab:treatment_likelihood\]](#tab:treatment_likelihood). For General Access, we find little evidence that these variables correlate with the timing of introduction. For Retail-to-Online Access, we find that unemployment rates are higher when states introduce online sports gambling, and poverty rates are lower. These observations are consistent with the fact that many US states introduced online sports gambling around the time of COVID-19, a period when unemployment rates were higher, and poverty rates declined.[^17] Following this result, we complete several robustness checks directly addressing potential COVID-19 effects and shifts in unemployment and poverty rates, and find results consistent with our primary model. These tests and results are presented in Appendix [\[sec:robustness\]](#sec:robustness).

# Results {#sec:aggregated-effects}

This section presents aggregated event studies and Average Treatment Effects (ATTs) covering eight quarters before and 16 quarters after the policy implementation. By presenting event studies, we can partially validate the assumption of parallel counterfactual trends. In addition, we can observe the evolution of the treatment over time, which provides insights into how rapidly outcomes change.

## Overall Consumers' Financial Health

#### Credit score

The first outcome we study is the average consumer credit score. As discussed above, a credit score is a measure of a consumer's overall financial health, designed to summarize their creditworthiness by predicting future default risk based on all data observed in credit reports. In Figure [2](#fig:credit-score-es), we present the event study estimates for changes in the average credit score for the two treatments, General Access (red bars) and Retail-to-Online Access (blue bars).

First, we note that, among General Access, pre-trends are essentially zero. For Retail-to-Online, we observe some non-zero differences between treated and control units, which pose a threat to identification. In Appendix [\[sec:robustness\]](#sec:robustness), we show that coarsened exact matching (CEM) on observables substantially improves pre-trends. Ultimately, results are consistent across methods, suggesting that observable differences between treated/control units may introduce noise but not meaningfully affect our estimates.

<figure id="fig:credit-score-es" data-latex-placement="ht">
<embed src="figures/ga-rto-es-plots/general_access_with_online_es_cs.pdf" style="width:50.0%" />
<figcaption>The effect of sports gambling legalization on consumer credit score.</figcaption>
</figure>

In the post-treatment period, we observe a decrease in credit scores for both treatments. We report the ATT for each treatment in Table [\[tab:overall-att-estimates\]](#tab:overall-att-estimates). We observe a modest decline in credit score with General Access (0.68 points). However, as shown in the event study plot, the effect is much more pronounced for Retail-to-Online Access. ATT effect estimates translate into a significantly larger 12.04-point decline (1.7% decline relative to pre-treatment credit score averages) for Retail-to-Online Access, suggesting that access to online gambling significantly harms consumer financial health.

Larger effects due to online gambling access could be attributable to several factors. These include lower costs of accessing gambling products, greater marketing and personalization opportunities for online sportsbook customers, and expanded player options, such as in-play/micro-bets or same-game parlays. Our data do not allow us to identify these factors separately, and all likely contribute to the differences in effects on credit score and the financial excessive debt outcomes shown below.

## Indicators of Excessive Debt

In this section, we analyze changes in indicators of excessive debt. This analysis help us better understand the reasons behind the decrease in the average credit score we documented.

#### Bankruptcies

First, we consider changes to bankruptcy filing rates. In our data, bankruptcy filings are tracked monthly. To align it with our quarterly data, we count the number of bankruptcies by individual over the three months between quarters. For example, for the March quarterly observation, we sum up bankruptcies by individual during January, February, and March. We then create a binary indicator that equals 1 if a consumer has filed any bankruptcy (Chapter 7, 11, 12, or 13) in the quarter, and 0 otherwise. We then aggregate this variable at the county-quarter level by taking the mean. Therefore, for each county, this variable represents the quarterly probability of bankruptcy for a randomly drawn individual in that county.

As we did for the credit score, we present the event study estimates for bankruptcies for both treatments in Figure [3](#fig:bankruptcy-es). While General Access does not lead to an increase in bankruptcy filings, Retail-to-Online Access does. In addition, this increase occurs only after a lag of roughly two years. This is expected, given that bankruptcies are often a last resort for consumers and would likely happen only after they experience significant financial stress.

We report the ATT estimates in Table [\[tab:overall-att-estimates\]](#tab:overall-att-estimates). The estimated ATT for Retail-to-Online Access of 0.0001 corresponds to a 0.01 percentage point increase in quarterly bankruptcy probability, or about one additional bankruptcy per 10,000 at-risk adults per quarter.[^18] While it may seem a small effect, bankruptcies are rare events. Compared to pre-treatment bankruptcy likelihoods, a jump of $0.01\%$ translates to a roughly 25% increase in the probability an individual files for bankruptcy.[^19]

<figure data-latex-placement="ht!">
<figure id="fig:bankruptcy-es">
<embed src="figures/ga-rto-es-plots/general_access_with_online_es_filed_bankruptcy.pdf" />
<figcaption>Changes in the likelihood of bankruptcy filing.</figcaption>
</figure>
<figure id="fig:collections-es">
<embed src="figures/ga-rto-es-plots/general_access_with_online_es_collection_on_acct.pdf" />
<figcaption>Changes in the amount of debt in collection on account.</figcaption>
</figure>
<figure id="fig:cc-delinquency-es">
<embed src="figures/ga-rto-es-plots/general_access_with_online_es_has_cc_delinq.pdf" />
<figcaption>Changes in the likelihood of credit card delinquencies.</figcaption>
</figure>
<figure id="fig:auto-loan-delinquency-es">
<embed src="figures/ga-rto-es-plots/general_access_with_online_es_has_auto_loan_delinq.pdf" />
<figcaption>Changes in the likelihood of auto loan delinquencies.</figcaption>
</figure>
<figure id="fig:debt-consol-overall">
<embed src="figures/ga-rto-es-plots/general_access_with_online_es_mean_num_i_dc.pdf" />
<figcaption>Changes in the likelihood of having an open debt consolidation loan.</figcaption>
</figure>
<figcaption>Changes in indicators of excessive debt</figcaption>
</figure>

#### Collections

In Figure [4](#fig:collections-es), we present the event study estimates for percentage changes in the amount of debt in collections on account. Because this value is zero for many panelists, to express the ATT in percentages, we first follow the commonly used practice of setting the dependent variable to log(Collections + 1). However, [@chen_roth] has shown that this approach is not invariant to the units used (dollars of debt, in this case) because the percentage change for individuals transitioning from zero debt to a positive amount is not defined. Because of this, we also calculate the effects separately for the intensive and extensive margins.

For the ATT measuring percentage changes in dollars of debt in collections, we observe no significant changes when we focus on General Access. With Retail-to-Online Access, we observe a significant increase of roughly 9% (ATT) in the average collections on account amount.

Given that the pre-treatment (Retail-to-Online Access) period average collection amounts are about $\$283$, our estimate translates to a roughly $\$25$ increase in the average amount of debt in collections per consumer due to online sports betting.

We then test whether the increase in collections on account with online accessibility is primarily due to more individuals having collections on account (extensive margins) or due to individuals having more debt, conditional on having collection debt (intensive margins).

To test for extensive margins, we analyze the binary likelihood that an individual has a collection on file. We find that there is a statistically significant increase $(p < 0.01, SE = 0.004)$ of about 1.8% in the likelihood that an individual has a collection on file. This suggests that more consumers are having debts sent to collections in states with online sports gambling access relative to states that don't.

To test for intensive margins, we condition our data on consumers with debt in collections and re-estimate our Collections model. We find that, conditional on having collections on file, there is a marginally significant decline in the amount of collections on file (ATT = -0.042, SE = 0.022; $p < 0.1$) post online sports gambling legalization. Combined with our existing results, this implies that online sports gambling could be leading to more people having smaller debts sent to collections (higher extensive margins and lower intensive margins). Additionally, the increase in bankruptcies described above could also lead to lower amounts of debt in collections.[^20]

#### Credit card delinquency

In Figure [5](#fig:cc-delinquency-es), we present the event study estimates for changes in the probability of an individual having a credit card delinquency on file. We observe no significant effects after General Access, but do observe a significant increase after a shift from Retail-to-Online Access. Consistent with this figure, the ATT for credit card delinquencies is roughly 0.6% (27% increase relative to pre-treatment averages) for Retail-to-Online Access (see Table [\[tab:overall-att-estimates\]](#tab:overall-att-estimates)). This suggests that sports gambling does affect consumers' financial health by increasing credit card debt. This complements the work by [@baker_et_al_gambling], who find that financially constrained households increase their credit card balances by about \$368 relative to less constrained households, corresponding to an 8% increase in credit card debt among constrained households.

#### Auto loan delinquency

In Figure [6](#fig:auto-loan-delinquency-es), we present the event study estimates for changes in the probability of an individual having an auto loan delinquency on file. We observe an increase for both treatments. Consistent with this figure, the ATT for General Access is $0.3\%$ and $1\%$ for Online Access (see Table [\[tab:overall-att-estimates\]](#tab:overall-att-estimates)). Compared to pre-treatment average delinquency rates, the ATT for General Access translates to a $8\%$ increase in auto loan delinquency likelihood. In contrast, the ATT for Retail-to-Online Access translates to a roughly $25\%$ increase in auto loan delinquency likelihood relative to pre-treatment delinquency rates.

#### Debt consolidation

Finally, we measure the impact of legal sports gambling on the use of debt consolidation loans. To measure this, we create a binary indicator variable that indicates when a consumer has an open debt-consolidation loan. These loans are often used to consolidate and manage high-interest debt (e.g., credit card debt). Given that these loans are typically last-resort measures to manage debt, similar to bankruptcy, we expect a delayed effect after the introduction of sports gambling. We present the event study estimates of the likelihood that an individual has an open debt-consolidation loan in Figure [7](#fig:debt-consol-overall). We observe a delayed increase for General Access and insignificant changes for Retail-to-Online Access. For General Access, the positive effect begins to manifest after two years. However, unlike in bankruptcies, where estimates are tighter, the confidence intervals for this measure are quite large. Due to this, we estimate ATTs that are insignificant under our main specification for both treatments (see Table [\[tab:overall-att-estimates\]](#tab:overall-att-estimates)).

## Summary of Results

We find that General Access to legal sports betting is associated with a modest decrease in average consumer financial health. The shifts in consumer financial health are stronger when a state moves from retail-only access to retail with online gambling, suggesting that the ability to bet on sports via online websites and mobile apps leads to greater financial harm.

Turning to the magnitude of the effects, while some of the effects we measure seem small, it is important to remember that we do not observe which members of the credit panel are actively engaged in sports betting. Therefore, we can only estimate the average effect across the overall population. Because most residents of treated states are unlikely to be problem gamblers,[^21] the average effect on the gambling population is much larger than the effects we document.

In Appendix [\[sec:robustness\]](#sec:robustness), we discuss a set of five robustness checks aimed at reducing endogeneity concerns, particularly those related to changes in economic conditions at the state or regional level that can drive our results. First, we re-estimate our models using a matched sample created using demographic and economic covariates. Second, we include pre-treatment economic controls correlated with treatment timing, such as the unemployment rate and the low-income rate. Third, we implement a border strategy similar to [@shapiro2018positive] and consider only counties at the borders of states that legalize sports gambling. Fourth, we use data from the University of Oxford COVID-19 Government Response Tracker (OxCGRT) [@hale2021global] to obtain time-varying indexes related to states' COVID-19 response policies to test for differences in states' COVID-19 response policies, such as the economic support index, government response index, and stringency index. We then estimate our DD using these indices as outcomes and find insignificant differences, alleviating concerns that differences in COVID-19 response policies could bias our estimates. Finally, we show that our results are not driven by the introduction of iGaming (online or mobile access to a broad range of gambling formats beyond betting on sporting events, including lotteries, slots, and casino games like poker). To do so, we exclude from estimation the six states that legalized iGaming during our observation period.

# Heterogeneity Analysis {#apx:hete}

In this section, we estimate heterogeneous effects across consumer types based on pre-treatment credit scores.

As a primary form of heterogeneity analysis, we consider how access to online sports gambling affects consumers across credit categories. Credit scores can generally be bucketed into three groups: Sub-prime (credit score $\leq 600$), Prime ($601 \leq$ credit score $\leq$ 780), and Super-prime (credit score $\geq 781$). Super-prime captures low-risk individuals, Prime captures average risk, and Sub-prime captures high-risk individuals.[^22] Sub-prime individuals are financially riskier in the eyes of the lender. Individuals in this category may have historically missed payments, defaulted, gone bankrupt, taken on significant debt, or have limited historical credit information.

We identify people as being Sub-prime, Prime, or Super-prime in the pre-legalization period by looking at their credit category in the first quarter of 2018 (just before the Supreme Court ruling, and treatment can potentially begin).[^23] We identify 1.3 million borrowers: 176,362 Sub-prime (13.4%), 637,288 Prime (48.8%), and 493,456 (37.7%) Super-prime.[^24] We present results in Table [\[tab:credit-score-heterogeneity\]](#tab:credit-score-heterogeneity). We then subset our data to include only individuals within each credit score category and re-estimate each CS model for each variable.

Consistent with other papers analyzing the consequences of sports gambling [@baker_et_al_gambling], we find larger drops in financial health among riskier borrowers (Sub-prime and Prime). Among Sub-prime consumers, we see a roughly 3.2-point drop in average credit scores, increased auto loan delinquencies by approximately 1.3 percentage points, and higher credit card delinquencies close to 1.68%. We observe that Prime borrowers also experience increasing auto loan and credit card delinquency rates, but these effects are smaller. Among Super-prime borrowers, we observe modest declines in credit scores and slight increases in credit card delinquencies, though these effects are noticeably smaller than among Prime and Sub-prime consumers. Overall, these results suggest that the adverse effects of online sports gambling implementation on financial health are primarily concentrated among the financially less secure.

# Conclusion

In this paper, we estimate the causal effect of sports gambling accessibility on consumer financial health by exploiting the recent legalization of sports gambling across U.S. states. We focus on changes in consumer credit risk and indicators of excessive debt across general sports betting accessibility and online accessibility.

Overall, the legalization of sports gambling decreased consumer financial health. These results seem to be particularly pronounced when states legalize online betting, suggesting that online or mobile access to gambling increases the problems associated with it.

Our paper provides a better understanding of how the legalization of sports gambling negatively affects consumer financial health. While many states may have opted for legalization to increase tax revenue, the adverse effect we document can partially offset tax revenue benefits as more consumers' financial health deteriorates.

While many consumers get real enjoyment from legal gambling, and states benefit in the form of additional tax revenue, there is a corresponding concern that the introduction of sports gambling and the ease with which consumers can now bet online are negatively harming consumer financial health. Our paper provides evidence that this concern is well-founded by quantifying the extent to which the recent aggressive expansion of gambling accessibility impacts consumer financial health.

# Appendix {#appendix .unnumbered}

# Treatment Type and Handles {#apx:tables}

In Table [5](#tab:handles-by-state), we present cumulative handle amounts (total amount wagered) by state and channel. On average, our data show that roughly 91% of betting is done online.

In Table [3](#tab:treat-start), we report legalization dates by state.

::::: threeparttable
::: {#tab:treat-start}
  ---- ---------------------- ----------- ----------

       State                    Retail      Online

     1 Delaware                Jun 2018       --
     2 New Jersey              Jun 2018    Aug 2018
     3 Mississippi             Aug 2018       --
     4 West Virginia           Aug 2018    Aug 2018
     5 New Mexico              Oct 2018       --
     6 Pennsylvania            Nov 2018    May 2019
     7 Rhode Island            Nov 2018    Sep 2019
     8 Arkansas                Jul 2019    Mar 2022
     9 New York                Jul 2019    Jan 2022
    10 Iowa                    Aug 2019    Aug 2019
    11 Indiana                 Sep 2019    Oct 2019
    12 Oregon                  Oct 2019    Oct 2019
    13 New Hampshire           Aug 2020    Dec 2019
    14 Illinois                Mar 2020    Jun 2020
    15 Michigan                Mar 2020    Jan 2021
    16 Montana                 Mar 2020       --
    17 Colorado                May 2020    May 2020
    18 District of Columbia    July 2020   May 2020
    19 Tennessee                  --       Nov 2020
    20 North Carolina          Mar 2021       --
    21 North Dakota            Jun 2021       --
    22 Arizona                 Sep 2021    Sep 2021
    23 South Dakota            Sep 2021       --
    24 Washington              Sep 2021       --
    25 Wyoming                    --       Sep 2021
    26 Connecticut             Oct 2021    Oct 2021
    27 Louisiana               Nov 2021    Jan 2022
    28 Wisconsin               Nov 2021       --
    29 Maryland                Dec 2021    Nov 2022
    30 Kansas                  Sep 2022    Sep 2022
    31 Virginia                July 2022   Jan 2021
    32 Massachusetts           Jan 2023    Mar 2023
    33 Ohio                    Jan 2023    Jan 2023

  ---- ---------------------- ----------- ----------

  : Treatment start dates in our dataset.
:::

::: tablenotes
*Note:* This table reports the month and year in which each state first implemented Retail and/or Online sports gambling. States without a start date did not implement that form of gambling during the sample period. States are ordered by the earliest adoption date.
:::


:::::

::::: threeparttable
::: {#tab:treatment-status-by-state}
  ---- ------------------------------- ---------------- ------------------

       State                            General Access   Retail-to-Online

     1 Arkansas                            Treated           Treated
     2 Arizona                             Treated           Treated
     3 Colorado                            Treated           Treated
     4 Connecticut                         Treated           Treated
     5 District of Columbia                Treated              --
     6 Delaware                            Treated           Control
     7 Iowa                                Treated           Treated
     8 Illinois                            Treated           Treated
     9 Indiana                             Treated           Treated
    10 Kansas                              Treated           Treated
    11 Louisiana                           Treated           Treated
    12 Massachusetts                       Treated           Treated
    13 Maryland                            Treated           Treated
    14 Michigan                            Treated           Treated
    15 Mississippi                         Treated           Control
    16 Montana                             Treated           Control
    17 North Carolina                      Treated           Control
    18 North Dakota                        Treated           Control
    19 New Hampshire                       Treated              --
    20 New Jersey                          Treated           Treated
    21 New Mexico                          Treated           Control
    22 New York                            Treated           Treated
    23 Ohio                                Treated           Treated
    24 Oregon                              Treated           Treated
    25 Pennsylvania                        Treated           Treated
    26 Rhode Island                        Treated           Treated
    27 South Dakota                        Treated           Control
    28 Tennessee                           Treated              --
    29 Virginia                            Treated              --
    30 Washington                          Treated           Control
    31 Wisconsin                           Treated           Control
    32 West Virginia                       Treated           Treated
    33 Wyoming                             Treated              --
       States without sports betting       Control              --

  ---- ------------------------------- ---------------- ------------------

  : States part of each treatment definition.
:::

::: tablenotes
*Note:* For General Access, Treated indicates a state that eventually implemented any form of sports gambling during the sample period, while Control indicates a state that never implemented any form of sports gambling. In the Retail-to-Online Access column, Treated indicates a state that eventually implemented online sports gambling after implementing retail, while Control indicates a state that implemented only retail sports gambling. "--" denotes states excluded from the Retail-to-Online Access treatment. States with implemented sports betting are ordered alphabetically.
:::


:::::

::::: threeparttable
::: {#tab:handles-by-state}
  ---- ---------------- ------------------ ----------------- ------------------ -------------

       State                         Total            Retail             Online   Pct. Online

     1 New Jersey         $38,283,170,776$   $3,713,428,792$   $34,569,741,984$        $0.90$
     2 New York           $23,407,473,632$     $494,149,829$   $22,913,323,803$        $0.98$
     3 Illinois           $22,572,379,238$     $897,187,635$   $21,675,191,603$        $0.96$
     4 Pennsylvania       $22,055,260,187$   $2,017,121,329$   $20,038,138,857$        $0.91$
     5 Colorado           $12,099,626,879$     $148,645,515$   $11,950,981,364$        $0.99$
     6 Indiana            $12,323,826,902$   $1,342,513,286$   $10,981,313,615$        $0.89$
     7 Michigan           $10,823,894,438$     $778,801,244$   $10,045,093,194$        $0.93$
     8 Virginia           $10,019,131,704$                NA                 NA            NA
     9 Arizona             $9,625,357,452$      $87,268,559$    $9,538,088,892$        $0.99$
    10 Tennessee           $8,622,329,752$               $0$    $8,622,329,752$           $1$
    11 Iowa                $6,169,666,538$     $834,747,402$    $5,334,919,136$        $0.86$
    12 Louisiana           $3,505,908,703$     $531,448,026$    $2,974,460,677$        $0.85$
    13 Ohio                $3,014,214,051$      $81,894,000$    $2,932,320,051$        $0.97$
    14 Maryland            $2,811,661,852$     $410,743,480$    $2,400,918,372$        $0.85$
    15 Connecticut         $2,556,619,323$     $155,720,243$    $2,400,899,080$        $0.94$
    16 New Hampshire       $2,293,312,508$     $444,716,787$    $1,848,595,721$        $0.81$
    17 West Virginia       $2,005,714,813$     $593,207,201$    $1,412,507,612$        $0.70$
    18 Massachusetts       $1,642,068,843$      $70,122,644$    $1,571,946,198$        $0.96$
    19 Kansas              $1,578,464,600$      $71,935,725$    $1,506,528,875$        $0.95$
    20 Rhode Island        $1,652,992,206$     $835,880,558$      $817,111,648$        $0.49$
    21 Oregon              $1,254,314,057$                NA                 NA            NA
    22 Arkansas              $445,931,327$     $198,623,807$      $247,307,519$        $0.55$
    23 DC                    $579,436,981$     $419,702,471$      $159,734,511$        $0.28$
    24 Wyoming               $238,202,106$               $0$      $238,202,106$           $1$
    25 Mississippi         $2,211,473,311$   $2,211,473,311$                $0$           $0$
    26 Delaware              $562,446,621$     $562,446,621$                $0$           $0$
    27 Montana               $143,854,952$     $143,854,952$                $0$           $0$
    28 South Dakota           $12,888,714$      $12,888,714$                $0$           $0$
    29 New Mexico                       NA                NA                $0$           $0$
    30 North Carolina                   NA                NA                $0$           $0$
    31 North Dakota                     NA                NA                $0$           $0$
    32 Washington                       NA                NA                $0$           $0$
    33 Wisconsin                        NA                NA                $0$           $0$

  ---- ---------------- ------------------ ----------------- ------------------ -------------

  : Cumulative handle by state.
:::

::: tablenotes
*Note:* This table reports the total, retail, and online sports betting cumulative handle (consumer wagers) by state over our sample period. "NA" indicates where sports handles are unobservable because they fall under tribal jurisdiction.
:::


:::::

# Variation in Sports Gambling Policies {#sec:sports-policy-variation}

Between 2018 and 2023, dozens of U.S. states legalized sports gambling, ushering in a patchwork of regulations with many similarities and some differences. In most states, sports betting is overseen by the same entity that regulates other gambling (e.g., lotteries and casinos). Most states have a minimum age of 21 to wager, though a few, like New Hampshire, maintain a minimum age of 18. Consumers cannot bet on youth sports. Some states allow for college betting, and all states allow for betting on professional sports.

All states in our Retail-to-Online Access treatment definition allow for statewide online sports gambling. A few states (Mississippi, Montana, and Washington) allow for online gambling, but only within specific casino locations. In our analysis, we treat these states as offline only, as consumers must be in a physical location and cannot bet throughout the state.

State policies primarily differ in their market licensing structures and tax policies. Most states permit a competitive market structure, allowing multiple sportsbooks, such as FanDuel and DraftKings, to compete for customers. However, D.C., New Hampshire, Oregon, and Rhode Island have opted for a monopoly structure, with a single primary licensee (e.g., only DraftKings).

Licensing agreements also generally depend on state laws regarding tribal rights. During our time window, some states, including Wisconsin, Washington, New Mexico, North Dakota, and North Carolina, only offer sports gambling through Native American tribal casinos. In Florida, legal battles involving the Seminole tribe and other online betting platforms led to delays in app rollout, with access eventually beginning in November 2023.

Licensing fees, tax rates, and what taxes are levied on vary across states. Licensing fees can be high or low and one-time or annual. In New York, commercial licensees pay a one-time fee of \$25 million. Alternatively, Tennessee levies a yearly licensing fee of \$750 thousand while Iowa levies an initial \$45 thousand one-time fee plus an annual \$10 thousand renewal fee.

Most state policies tax gross game revenue (GGR), or net sportsbook revenue. Notable exceptions include: 1) Tennessee, where in July 2023, taxes were shifted to a per-handle (i.e., spend) rate, not a GGR rate, and 2) Illinois, where in July 2025, they introduced a 25-cent tax on each wager for the first 20 million online wagers per year, increasing to 50 cents for each additional wager after that. (These policies are outside our analysis window). There is meaningful variation in GGR-based tax rates across states. For example, New York levies a 51% tax on all sportsbook taxes. Similarly, New Hampshire and Rhode Island, both states that maintain monopoly market structures, both employ 51% (50%) revenue share models across online (retail) channels.[^25] On the other hand, Indiana levies a much smaller 9.5% GGR-based tax rate. Finally, some states levy varying tax rates across online and retail channels, with online taxes generally being higher. For example, in Massachusetts, online GGR is taxed at 20% and retail GGR is taxed at 15%.[^26]

## Robustness Checks

#### Coarsened Exact Matching

While our hazard model in Table [\[tab:treatment_likelihood\]](#tab:treatment_likelihood) does not show that various economic and demographic measures correlate with the timing of sports betting legalization, we may still worry that they could correlate with some confound that impacts both adoption and our dependent variables. For example, if Covid-19 affects states and counties at particular income thresholds, and this impacts both sports betting adoption and our outcome variables, then our results could be confounded by the interaction between income and Covid-19. To strengthen the causal interpretation of our results, we consider matching counties on the economic and demographic characteristics captured in our hazard model.

Because of the inherent staggered setting and the lack of a post period for never-treated units, we elect to match on pre-period observations that exist for all counties. Specifically, we take 2015-2017 (inclusive) observations for each of our economic and demographic variables and take the average for each county. A county is defined as treated if it is eventually treated, otherwise it is deemed a control unit (i.e., never treated). We then use coarsened exact matching [@iacus2012causal] with one-to-one restriction within bins to match control counties to (eventually) treated counties based on 2015-2017 average observable characteristics. Since we drop states with only retail access to sports betting for the Online Access treatment, we run two separate matching procedures for each treatment status (General Access and Online Access). In Table [\[tab:cem-matching-observables\]](#tab:cem-matching-observables), we present differences in observable characteristics between treated (General Access) and control counties before and after matching for the 2015-2017 time period. Matching leaves us with 696 eventually treated counties and 696 never treated control counties. (1141 treated counties and 571 control counties are dropped).

Similarly, in Table [\[tab:cem-matching-observables-online\]](#tab:cem-matching-observables-online), we present differences in observable characteristics between treated (Online Access) and control units for the 2015-2017 time period. This leaves us with 509 treated and 509 control counties. (758 control counties are dropped and 830 treated counties are dropped).

The challenge with matching using only 2015-2017 observable characteristics is that it does not necessarily guarantee similar observable characteristics in the periods just before treatment.[^27] One can view our matching as a "light" matching.

This strategy works if county observable characteristics evolve similarly and do not "drift" apart after the 2015-2017 time periods. If this holds, then we should observe that the matched counties share similar observable characteristics just before treatment occurs. This is testable with our data. Taking the period just before treatment (-1), we can look at the differences in observable characteristics between the matched counties. In Table [\[tab:all-counties-just-before-treatment\]](#tab:all-counties-just-before-treatment) we show that without matching counties do show observable differences right before treatment. However, once matched, these differences are insignificant, as shown in Table [\[tab:matched-counties-just-before-treatment\]](#tab:matched-counties-just-before-treatment). We find insignificant differences across variables, suggesting that counties do not "drift" apart from one another with our given matching strategy.

After matching, we re-run our primary CS estimator using this subset of counties. Results are presented in Table [\[tab:cem-matching\]](#tab:cem-matching). We find results that are consistent with our main, unmatched specification.

#### CS Border counties

As an additional robustness check, we restrict our analysis to counties along the border and re-estimate our CS model. By restricting our analysis to border counties, we assume that individuals in these counties along the border are similar, some counties happen to be eventually treated while others are not. If this is the case, there should not be significant differences across counties prior to treatment. Like with matching, this is testable with our data. Using the period just before treatment (-1). In Table [9.1.0.3](#), we see that there aren't observable differences across eventually treated and never treated counties.

In Table [\[tab:cs-border\]](#tab:cs-border), we then present results using the CS estimator with the border county units. We find results that are consistent with our primary model specification.

#### iGaming

Lastly, one potential concern could be that the results of online access are driven by the introduction of iGaming, not sports betting. iGaming is other forms of online gambling, including lotteries, slots, and casino games like poker. In our time window, six states had some form of legalized iGaming accessibility (Pennsylvania, West Virginia, New Jersey, Michigan, Delaware, and Connecticut). The market for iGaming is smaller than online sports betting but still generates substantial revenue. In November 2024, iGaming company revenue was over \$800 million. [^28] To test the robustness of our Online Access results, we drop the six states with iGaming accessibility and re-estimate the same models used to generate results in Table [\[tab:overall-att-estimates\]](#tab:overall-att-estimates). In Table [\[tab:igaming-exclusion\]](#tab:igaming-exclusion) we present ATT estimates over the time period. We find that our Online Access results continue to hold, which suggest these findings are not driven by iGaming accessibility, but by online sports gambling.

# Heterogeneity Analysis {#apx:hete}

In this section, we estimate heterogeneous effects across consumer types based on pre-treatment credit scores.

As a primary form of heterogeneity analysis, we consider how access to online sports gambling affects consumers across credit categories. Credit scores can generally be bucketed into three groups: Sub-prime (credit score $\leq 600$), Prime ($601 \leq$ credit score $\leq$ 780), and Super-prime (credit score $\geq 781$). Super-prime captures low-risk individuals, Prime captures average risk, and Sub-prime captures high-risk individuals.[^29] Sub-prime individuals are financially riskier in the eyes of the lender. Individuals in this category may have historically missed payments, defaulted, gone bankrupt, taken on significant debt, or have limited historical credit information.

We identify people as being Sub-prime, Prime, or Super-prime in the pre-legalization period by looking at their credit category in the first quarter of 2018 (just before the Supreme Court ruling, and treatment can potentially begin).[^30] We identify 1.3 million borrowers: 176,362 Sub-prime (13.4%), 637,288 Prime (48.8%), and 493,456 (37.7%) Super-prime.[^31] We present results in Table [\[tab:credit-score-heterogeneity\]](#tab:credit-score-heterogeneity). We then subset our data to include only individuals within each credit score category and re-estimate each CS model for each variable.

Consistent with other papers analyzing the consequences of sports gambling [@baker_et_al_gambling], we find larger drops in financial health among riskier borrowers (Sub-prime and Prime). Among Sub-prime consumers, we see a roughly 3.2-point drop in average credit scores, increased auto loan delinquencies by approximately 1.3 percentage points, and higher credit card delinquencies close to 1.68%. We observe that Prime borrowers also experience increasing auto loan and credit card delinquency rates, but these effects are smaller. Among Super-prime borrowers, we observe modest declines in credit scores and slight increases in credit card delinquencies, though these effects are noticeably smaller than among Prime and Sub-prime consumers. Overall, these results suggest that the adverse effects of online sports gambling implementation on financial health are primarily concentrated among the financially less secure.

[^1]: UCLA Anderson School of Management; brett.hollenbeck@anderson.ucla.edu

[^2]: Harvard University, Harvard Business School; plarsen@hbs.edu

[^3]: University of Southern California, Marshall School of Business; proserpi@usc.edu

[^4]: See: <https://www.legalsportsreport.com/sports-betting/revenue/>

[^5]: For example, a state may implement legal sports betting because of revenue shortfalls and a need for the additional tax revenue it may generate, and these states may also be more susceptible to economic shocks.

[^6]: Different data sources find that the proportion of the population who adopt sports betting is in the range of 13-20% [@baker_et_al_gambling]. A survey by Siena finds 19% adoption in 2024 (see <https://scri.siena.edu/2025/02/18/22-of-all-americans-half-of-men-18-49-have-active-online-sports-betting-account/>).

[^7]: Using reported state tax revenue from 2022, back-of-the-envelope estimates suggest that states are generating about \$$44,000$ in net tax revenue from sportsbooks per new bankruptcy.

[^8]: Other research explores the impact of the rollout of sports betting in the U.S. on intimate partner violence [@arnesen_violence] and mental health outcomes [@counture_gambling].

[^9]: See: <https://www.americangaming.org/research/state-gaming-map/>.

[^10]: We obtained sports betting handles data in June 2023 from <https://www.legalsportsreport.com/sports-betting/revenue/>.

[^11]: We refer to these observations as quarterly observations or quarters.

[^12]: See <https://www.capolicylab.org/data-resources/university-of-california-consumer-credit-panel/> for additional discussion of data.

[^13]: In an earlier draft of this paper, we used states that never introduced online sports betting as controls, allowing for both pre-online periods that contained retail gambling or no gambling. This did not create a homogeneous baseline, making the interpretation of ATT estimates difficult, and may have allowed lagged retail effects to confound our online measure. This new treatment measure, 1) homogenizes the baseline to retail sports gambling access, and 2) differences out lagged retail effects through the use of retail-only states as controls.

[^14]: <https://www.chase.com/personal/credit-cards/education/credit-score/vantagescore-ranges-explained>

[^15]: Collections can stay on a consumer's account for up to seven years. Consumers can negotiate to have the report dropped from their account. We do not observe this behavior.

[^16]: Pre-legalization is based on the "General Access" category. We present county-level summary statistics to align with our county-level aggregation for model estimation.

[^17]: See <https://www.census.gov/library/stories/2021/09/did-unemployment-insurance-lower-official-poverty-rates-in-2020.html> as well as <https://www.bls.gov/opub/mlr/2021/article/unemployment-rises-in-2020-as-the-country-battles-the-covid-19-pandemic.htm>.

[^18]: We define the at-risk population as adults in states with legalized online sports gambling (conditional on having legalized retail) who are financially active and carry some form of debt.

[^19]: We can also try to translate the effect of Retail-to-Online access on bankruptcies to the overall at-risk population in the states part of the retail-to-online treatment. We estimate the at-risk population in these states to be roughly 77 million. This is calculated by multiplying the adult population in these states (about 100 million) by the proportion of households that maintain any form of debt (77.4% from the 2022 Survey of Consumer Finances). Multiplying our ATT by this at-risk population implies approximately $7,700$ additional bankruptcy filings per quarter, or about $30,000$ additional filings per year if the effect persists across quarters. Given that personal bankruptcies in the US are around $400,000-500,000$ per year, back-of-the-envelope estimates imply that roughly 6-7.5% bankruptcies are due to online sports gambling. See <https://www.federalreserve.gov/publications/october-2023-changes-in-us-family-finances-from-2019-to-2022.htm> for the 2022 Survey of Consumer Finances and <https://www.uscourts.gov/data-news/judiciary-news/2024/11/07/bankruptcy-filings-rise-162-percent> for bankruptcy amounts in the US.

[^20]: We do not observe whether collection debts are paid off or cleared due to bankruptcy.

[^21]: Different data sources find that the proportion of the population who adopt sports betting is in the range of 13-20% [@baker_et_al_gambling]. A survey by Siena finds 19% adoption in 2024 (see <https://scri.siena.edu/2025/02/18/22-of-all-americans-half-of-men-18-49-have-active-online-sports-betting-account/>).

[^22]: Vantage also considers a Near-prime category from $600$ to $660$. We group these scores with Prime to create three classes.

[^23]: We choose only the quarter before because the VantageScore credit score model meaningfully changed in 2017, so we did not want to delegate credit categories using credit scores from different models.

[^24]: These proportions are consistent with industry reports <https://newsroom.transunion.com/q3-2025-ciir/>

[^25]: <https://www.americangaming.org/wp-content/uploads/2019/07/AGA-Gaming-Regulatory-Fact-Sheet_NH.pdf>

[^26]: <https://massgaming.com/about/sports-wagering-in-massachusetts/sports-wagering-licensees/>

[^27]: We elect to match on only the 2015-2017 observable characteristics due to the staggered setting varying the underlying post-period for treated and control units, making traditional pre-treatment matching infeasible.

[^28]: <https://www.americangaming.org/resources/aga-commercial-gaming-revenue-tracker/>

[^29]: Vantage also considers a Near-prime category from $600$ to $660$. We group these scores with Prime to create three classes.

[^30]: We choose only the quarter before because the VantageScore credit score model meaningfully changed in 2017, so we did not want to delegate credit categories using credit scores from different models.

[^31]: These proportions are consistent with industry reports <https://newsroom.transunion.com/q3-2025-ciir/>
