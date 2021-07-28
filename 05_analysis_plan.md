# [Analysis Plan]

[*In this section, you describe all confirmatory analyses you plan to conduct.
Be as specific as possible (e.g. assign each hypothesis to be tested to the
corresponding model in this section; specify the usage of covariates in
sensitivity analyses and the selection of regions of interest). If you plan to
include additional fMRI analyses techniques, check Appendix 3 for checklists.*]

## [Statistical modeling\*]

### [Behavioral analysis]

[Specify all analyses to test your hypotheses. Remember that all confirmatory
analyses specified below must be reported in the final article, and any
additional analyses must be noted as exploratory or hypothesis generating. For
each hypothesis, include the following information:]

+-----------------------------------+-----------------------------------+ | [\ |
[Statistical model (e.g., ANOVA, | | __] | multiple regression, etc.) and | its
specification (that includes | each variable that will be | included as
predictor/factor | (incl. its levels), outcome, or | covariate).] |
+===================================+===================================+ |
[__or NA] | [Specify any interactions that | will be tested] |
+-----------------------------------+-----------------------------------+ | [__]
| [Name assumptions that need to be | met and how they will be | tested] |
+-----------------------------------+-----------------------------------+ | [__]
| [Include a contingency plan in | case assumptions are not | met] |
+-----------------------------------+-----------------------------------+ | [__]
| [Include software and packages | used for each test] |
+-----------------------------------+-----------------------------------+ [What
criteria will you use to | make inferences? Please describe | | [__] | the
information you'll use (e.g. | p-values, Bayes factors, specific | model fit
indices), as well as | cut-off criterion, where | appropriate.] |
+-----------------------------------+-----------------------------------+ | [__]
| [Note whether you will adjust for | multiple comparisons and how | (e.g.
correction procedure, | number of tests included ...) or | explain why not.] |
+-----------------------------------+-----------------------------------+

### [fMRI analysis]

[Specify all analyses to test each hypothesis. Please include the type of model
and the specification of the model (this includes each variable that will be
included as predictors, outcomes, or covariates). Also specify any interactions
that will be tested. Remember that all confirmatory analyses specified below
must be reported in the final article, and any additional analyses must be noted
as exploratory or hypothesis generating.]

[Specify whether you plan to perform whole-brain or ROI-analysis. In case of
ROI, be specific (e.g. defined based on anatomical definition, prior study
cluster, Neurosynth definition, Parcellation definition). List regressors of
interest at the neural level and corresponding confirmatory hypothesis. If
applicable, describe covariate measures.]

[For necessary details regarding functional connectivity and decoding analysis,
please see **Appendix 4**.]

+-----------------------+-----------------------+-----------------------+ |
[**Individual (first) | | level | | modeling**]{dir="ltr" | | } |
+=======================+=======================+=======================+ | [__]
| [Event­-related predictors (modeled duration (or zero), whether parametric
modulation is used)]
+-----------------------+-----------------------+-----------------------+ | [__]
| [Block Design predictors (note whether or not baseline will be explicitly
modeled)]
+-----------------------+-----------------------+-----------------------+ |
[**or | [Include design | NA] | matrix and efficiency/collineari ty measure
(recommended)]{dir="l tr"}
+-----------------------+-----------------------+-----------------------+ | [**]
| [HRF basis (e.g. canonical only, canonical with temporal derivative, or with
temporal and dispersion derivative, Finite Impulse Response model)]
+-----------------------+-----------------------+-----------------------+ | [__]
| [Movement regressors; specify if squares and/or temporal derivative used.]
+-----------------------+-----------------------+-----------------------+ | [__]
| [Any other nuisance regressors, and whether they were entered as interactions
(e.g. with a task effect in 1st level fMRI, or with group effect).]
+-----------------------+-----------------------+-----------------------+ | [__]
| [Any orthogonalization of regressors or parametric modulators, and set of
other regressors used to orthogonalize against.]
+-----------------------+-----------------------+-----------------------+ | [__]
| [Contrast construction (Exactly what terms are subtracted from what? Define
these in terms of task or stimulus conditions instead of underlying
psychological concepts.]
+-----------------------+-----------------------+-----------------------+ | [__]
| [Model settings]

- [For

  > _mass-­univaria te first level fMRI,_ these include drift regressors (e.g.
  > DCT basis in SPM, with specified cut­off) and autocorrelation model (e.g.,
  > global approximate AR(1) in SPM; locally recularized autocorrelation
  > function in FSL). Check your imaging toolbox to see default settings.]{dir=
  > "ltr"}
  > +-----------------------+-----------------------+-----------------------+ |
  > [**Group | | (second)-level | | modeling**]{dir="ltr" | | } |
  > +-----------------------+-----------------------+-----------------------+
  > [State and justify statistical model and estimation method, inference type |
  > [__] | (mixed/random effects or fixed), e.g., "Mixed effects inference with
  > one sample t-test on summary statistic" (SPM2/SPM5), e.g., "Mixed effects
  > inference with Bayesian 2-level model with fast approximation to posterior
  > probability of activation." (FSL).]
  > +-----------------------+-----------------------+-----------------------+ |
  > [**or | [If more than | NA] | 2-levels, describe the levels and assumptions
  > of the model (e.g., are variances assumed equal between groups)]
  > +-----------------------+-----------------------+-----------------------+ |
  > [\ | [If multiple | \ | measurements per | \ | subject, list method | **or
  > NA] | to account for within subject correlation, exact assumptions made
  > about correlation/variance, e.g., SPM: "Within-subject correlation estimated
  > at F-significant voxels (P \<0.001), then used globally over whole brain";
  > or, if variances for each measure are allowed to vary, "Within-subject
  > correlation and relative variance estimated..."]{dir="l tr"}
  > +-----------------------+-----------------------+-----------------------+ |
  > [\ | [For group model with | \ | repeated measures, | __or NA] | specify how
  > condition effects are modeled (e.g. as factors, or as linear trends), and
  > whether subject effects are modeled (i.e. as regressors, as opposed to with
  > a covariance structure).]{dir="ltr "}
  > +-----------------------+-----------------------+-----------------------+ |
  > [**or | [For group effects: | NA] | clearly state whether or not covariates
  > are split by group (i.e. fit as a group-by-­covariate interaction).]{dir="l
  > tr"}
  > +-----------------------+-----------------------+-----------------------+
  > [Model type (e.g., Mass Univariate, | [**] | Multivariate (e.g. ICA on whole
  > brain data), Local Multivariate (e.g. "searchlight"), Representational
  > Similarity Analysis, psychophysiological interaction (PPI))]
  > +-----------------------+-----------------------+-----------------------+
  > [Model settings]

- [For

  > _mass-­univaria te group level fMRI_ these include fixed effects (all
  > subjects' data in one model), or random or mixed ­effects model (implemented
  > with (1) Ordinary least squares (OLS, aka unweighted summary statistics |
  > [__] | > approach; SPM default, FSL FEAT's "Simple OLS"), (2) weighted least
  > squares (i.e. FSL FEAT's "FLAME 1") using voxel­wise estimate of between
  > subject variance, or (3) Global weighted least squares (i.e. SPM's
  > MFX)).]{dir="lt r"}

- [With \*any group

  > (multi­subject) model\*, indicate any specific variance structure, e.g.
  > Unequal variance between groups (and if globally pooled, as in SPM), or if
  > repeated measures, the specific covariance structure assumed (e.g. compound
  > symmetric, or arbitrary; if globally pooled).]{dir=" ltr"}

- [For \*local­
  > multivariate report,\* indicate the number of voxels in the local model, and
  > the Local model used (e.g. Canonical Correlation Analysis) with any
  > constraints (e.g. positive weights only).]{dir="lt r"}
  > +-----------------------+-----------------------+-----------------------+ |
  > [**ROI | | analysis**]{dir="ltr" | | } |
  > +-----------------------+-----------------------+-----------------------+ |
  > [**or | [Will you limit your | NA] | analysis to a specific ROI? (e.g.
  > unilateral, cerebellum)]{dir="ltr "}
  > +-----------------------+-----------------------+-----------------------+ |
  > [**or | [How will you define | NA] | your ROI (e.g., functional, anatomical,
  > meta-analysis, parcel localizer)?]{dir="ltr "}
  > +-----------------------+-----------------------+-----------------------+ |
  > [**or | [Justify definition | NA] | of ROI and analysis conducted with it:
  > (e.g., if your ROI is defined based on the cluster; how will you ensure your
  > ROI analyses are not circular?)]{dir="ltr" }
  > +-----------------------+-----------------------+-----------------------+ |
  > [**or | [How was signal | NA] | extracted within ROI?(e.g., average
  > parameter estimates, FIR deconvolution?)]{dir= "ltr"}
  > +-----------------------+-----------------------+-----------------------+ |
  > [\_\_or | [If percent signal | NA] | change reported, how was scaling factor
  > determined]{dir="ltr" }

[(e.g., height of block regressor or height of isolated event
regressor)?]{dir="ltr "}
+-----------------------+-----------------------+-----------------------+ |
**[Inference on | | statistic image | | (thresholding)]{dir=" | | ltr"}** |
+-----------------------+-----------------------+-----------------------+ | [__]
| [Whole brain or a specific search region? Specify type of search region
analysis, and the volume in voxels or mm^3^)]
+-----------------------+-----------------------+-----------------------+ |
[\_\_or | [If not whole brain, | NA] | state how the region will be determined;
method for constructing region should be independent of present statistic
image:]

- [Carefully

  > describe any small volume (SV) correction used for each contrast.]{dir=
  > "ltr"}

- [If the SV
  > correction mask will be defined anatomically, provide named anatomical
  > regions from a publicly available ROI atlas and, if probability-bas ed,
  > state selected threshold.]{dir ="ltr"}

> [● If the SV > correction mask > will be > functionally > defined, clearly >
> describe the > functional task and > identify any risk > of >
> circularity.]{dir=" ltr"}

- [All SV
  > corrections should be fully described in the methods section, not just
  > mentioned in passing in the results.]{dir=" ltr"}
  > +-----------------------+-----------------------+-----------------------+ |
  > [__] | [Statistical type, e.g., voxel-wise (aka peak­wise in SPM) or
  > cluster-wise (cluster size, cluster mass, threshold­free Cluster Enhancement
  > (TFCE)).]
  > +-----------------------+-----------------------+-----------------------+ |
  > [**or | [Statistical | NA] | threshold used to infer significance (e.g. p \<
  > 0.05)]
  > +-----------------------+-----------------------+-----------------------+ |
  > [**or | [If cluster-wise | NA] | (cluster size or mass) significance, state
  > cluster-defining threshold (e.g., P = 0.001).]
  > +-----------------------+-----------------------+-----------------------+ |
  > [\_\_or | [For all cluster­wise | NA] | methods, report neighborhood size
  > used to form clusters (e.g. 6, 18 or 26).]

+-----------------------+-----------------------+-----------------------+ |
[**or | [For TFCE, report use | NA] | of non­default TFCE parameters.]{dir="ltr
"} +-----------------------+-----------------------+-----------------------+ |
[\ | [P value computation. | **] | Report if anything but standard parametric
inference used to obtain (uncorrected) P­-values. If nonparametric method was
used, report method (e.g. permutation or bootstrap) and number of
permutations/samples used.]
+-----------------------+-----------------------+-----------------------+ | [\ |
[Multiple test | \ | correction. For | __] | mass­univariate, specify the type
of correction and how it is obtained, e.g., Familywise Error (Random Field
Theory (typical), Permutation, Monte Carlo, Bonferroni), False Discovery Rate
(Benjamini & Hochberg FDR (typical), Positive FDR, Local FDR, Cluster­level
FDR), or none/uncorrected.]{di r="ltr"}
+-----------------------+-----------------------+-----------------------+ |
[**or | [If permutation or | NA] | Monte Carlo, report the number of
permutations/samples. ]
+-----------------------+-----------------------+-----------------------+ |
[**or | [If Monte Carlo, note | NA] | brain mask and smoothness used, and how
smoothness was estimated.]{dir="ltr" }
+-----------------------+-----------------------+-----------------------+ |
[**or | [If FWE found by | NA] | random field theory, list smoothness in mm FWHM
and the RESEL count.]
+-----------------------+-----------------------+-----------------------+ |
[**or | [If FWE found by | NA] | simulation (e.g., AFNI AlphaSim), provide
details of parameters for simulation.]{dir="ltr "}
+-----------------------+-----------------------+-----------------------+ |
[**or | [If not a standard | NA] | method, specify the method for finding
significance (e.g., "Custom in-lab software was used to construct statistic maps
and thresholded at FDR\< 0.05 (Benjamini and Hochberg, 1995)"]
+-----------------------+-----------------------+-----------------------+ |
[**or | [False negative | NA] | discussion: Any discussion of failure to reject
the null hypothesis (e.g., lack of activation in a particular region) should be
accompanied by SNR or effect size of the actually observed effect (allows reader
to infer power to estimate an effect)]
+-----------------------+-----------------------+-----------------------+

_[Recommendations of fMRI details come from Nichols et al., 2016; Poldrack et
al., 2008.]_

[*For extended checklist guidelines for this section following data analysis,
see OHBM COBIDAS report Nichols et al., 2016.*]

## [Follow-up Analyses]

[If not specified previously, will you be conducting any confirmatory analyses
to follow up on effects in your statistical model, such as subgroup analyses,
pairwise or complex contrasts, or follow-up tests from interactions? Remember
that any analyses not specified in this research plan must be noted as
exploratory.]

## [Exploratory Analyses]

[If you plan to explore your data set to look for unexpected differences or
relationships, you may describe those tests here. An exploratory test is any
test where a prediction is not made up front, or there are multiple possible
tests that you are going to use. A statistically significant finding in an
exploratory test is a great way to form a new confirmatory hypothesis, which
could be registered at a later time.]
