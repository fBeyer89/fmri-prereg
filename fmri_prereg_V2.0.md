---
title: '{#_gjdgxs .anchor}[The fMRI preregistration template]'
---


<!-- **[Discussion points]**

- [detailed vs. concise description of elements, or support both?]

 - [template might be too overwhelming if detailed -\> rather break down by using mandatory/optional, maybe have "defaults" of programs in supplements/methods part to make sure they are reported]

 - [lots of details about things that you cannot change after you have conducted your experiment (fmri sequence), most people preregister after they have acquired their task]

 - [move acquisition parameters and other parts which are important for manuscript but not for preregistration to appendix]

- [mark recommended and essential labels (e.g., relating to the choice of going with a detailed vs. concise description)]

- [other modalities (to be added after publishing the fMRI specific template)]

- [incorporate fmriprep's defaults]

- [align structure with structure of a manuscript: decision: keep current order (OSF template) and move into a more concise version]

- [use tables as list of check boxes when writing methods section]

- [power analysis: unknown effect sizes and practical limitations in fMRI studies rather than a-priori power analysis which are rarely done. Exploratory vs. confirmatory analyses,] -->

 [Table of contents]
==============================

[**[Usage Notes to the template](#usage-notes-to-the-template)
1**]

[**[Study Information](#study-information) 1**]

> [[Working title\*](#working-title) 1]
>
> [[Authors\*](#authors) 1]
>
> [[Description](#description) 1]
>
> [[Hypotheses\*](#hypotheses) 1]

[**[Design Plan](#design-plan) 2**]

> [[Study Type\*](#study-type) 2]
>
> [[Study Design\*](#study-design) 2]
>
> [[Experimental design\*](#experimental-design) 3]
>
> [[Blinding\*](#blinding) 4]
>
> [[Randomization\*](#randomization) 4]

[**[Sampling Plan](#sampling-plan) 5**]

> [[Details of Larger Project\*](#details-of-larger-project)
> 5]
>
> [[Existing data\*](#existing-data) 5]
>
> [[Data collection\*](#data-collection) 6]
>
> [[Sample Size\*](#sample-size) 7]

[**[Variables](#variables) 8**]

> [[Manipulated variables](#manipulated-variables) 8]
>
> [[Measured variables\*](#measured-variables) 8]

[**[Analysis Plan](#analysis-plan) 12**]

> [[Statistical modeling\*](#statistical-modeling) 12]
>
> [[Follow-up Analyses](#follow-up-analyses) 16]
>
> [[Exploratory Analyses](#exploratory-analyses) 16]

[**[Appendices](#appendices) 1**]

> [[Appendix 1: Examples of fMRI study
> pre-registrations](#appendix-1-examples-of-fmri-study-pre-registrations)
> 1]
>
> [[Appendix 2: fMRI data acquisition
> checklists](#appendix-2-fmri-data-acquisition-checklists)
> 2]
>
> [[Appendix 3: Additional fMRI
> analyses](#appendix-3-additional-fmri-analyses) 5]



[Usage Notes to the template]
========================================

*[The goal of this template is to provide sufficient information in
preregistration of fMRI studies to increase
reproducibility.]*



*[A \* indicates you should fill out this section, all other sections
are optional.]*

[*You can use the tables to fill in your design specifications, or use
them as checklists of information you include in the text for in
attached files (e.g., json file of scan parameters). If a certain
table/section does not apply, just state "NA." Tip: Using it as a
checklist will allow you to write these sections as they will appear in
your future paper.*]


[Sampling Plan]
==========================

*[Describe how you plan to collect samples, as well as the number of
samples you plan to collect and your rationale for this decision. Please
keep in mind that the data described in this section should be the
actual data used for analysis, so if you are using a subset of a larger
dataset, please describe the subset that will actually be used in your
study.]*

[Details of Larger Project\*]
----------------------------------------

[Is your preregistration part of a larger project?]

- [No]

- [Yes\
 > If yes, provide a brief description of the larger study or, if
 > applicable, link to the OSF project page, a related
 > preregistration, a poster, etc. You may also include a figure
 > detailing the protocol of the project. Note, this is meant to
 > provide context for the larger scope of the project.]

[Existing data\*]
----------------------------

[Preregistration is designed to emphasize the distinction between
confirmatory tests, specified prior to seeing the data, and exploratory
analyses conducted without specific hypothesis or after observing the
data. Therefore, creating a research plan in which existing data will be
used presents unique challenges. For research that uses existing
datasets (e.g. Human Connectome Project, UK biobank, etc.), we also
refer to the OSF preregistration template for secondary data analysis,
which was designed specifically for this type of analytical research
([[https://osf.io/x4gzt/]{.underline}](https://osf.io/x4gzt/)). Please
select the description that best describes your situation:]

- [Registration prior to creation of data]

- [Registration prior to accessing the data]

- [Registration prior to any human observation of the data]

- [Registration prior to analysis of the data]

- [Registration following analysis of the data]



[Explanation of Existing Data]

[If you indicate that you will be using some data that already exists in
this study, please describe your prior knowledge of any patterns or
summary statistics in the data. This may include an explanation of how
access to the data has been limited, who has observed the data, and
if/what is already known about the sample you investigate (e.g., links
to prior papers, osf project page, prior posters or talks, or
descriptions). The purpose of this question is to assure that the line
between confirmatory and exploratory analysis is clear.]





[Data collection\*]
------------------------------

[Is this preregistration done before data collection?\
]

- [No\
 > There is no need to describe the data collection in complete
 > detail in your preregistration. Nonetheless, it is strongly
 > recommended to include information on your sample (see checklist
 > below), behavioral and fMRI data acquisition (**Appendix 2**) in a
 > short paragraph as it would appear in the Methods section of a
 > publication. Especially mention details important for your choices
 > in **Variables** and **Analysis Plan** (e.g. temporal/spatial
 > resolution of fMRI which may motivate certain preprocessing or
 > analysis procedures).]

- [Yes\
 > Describe all steps of data collection including your sample
 > description (see checklist below). Make sure to detail procedures
 > of all relevant behavioral and fMRI data acquisition steps. Other
 > measurements relevant to address your hypotheses or that are
 > included for different purposes (e.g., characterizing groups,
 > sensitivity analysis, exploratory analysis) may also be detailed
 > here. For the task-based fMRI measurements you can use the table
 > in **Appendix 2** as a checklist of topics to cover in this
 > description.]

> 

[*Note: There may be some overlap between this and other sections.
Again, that is OK, as long as sufficient detail is given in one of the
areas to provide all of the requested information.*]

 [Sample description] 
 --------------------------------- ---------------------------------------------------------------------------------
 [__] [Population]
 [__] [Recruitment efforts]
 [__] [Inclusion criteria]
 [__] [Exclusion criteria]
 [__] [Reimbursement for participation]
 [__] [Information on ethics approval and informed consent]
 [__] [Number of participants tested and analyzed]
 [__] [Age]
 [__] [Sex / Gender]
 [__] [Handedness]
 [__or NA] [Clinical criteria]
 [__or NA] [Matching strategy]
 [__or NA] [Other relevant participant or group characteristics for your study]
 [__] [Study timeline including all measures]



[Other Measures]

[Please specify all additional measures you plan to investigate, for
example:]

- [**Experimental tasks outside the scanner:** For each additional
 > behavioral task, give a short description and specify the design
 > and task. You may use the table for the design of scanner tasks in
 > the section **Design Plan** as a checklist.]

- [**Questionnaires and standardized assessments:** For each
 > questionnaire and standardized assessment, mention the name and
 > version.]

- [**Additional neuroimaging measures:** Give a description and brief
 > purpose statement of any other imaging modalities that will be
 > included in your study (e.g., EEG, Neuromodulation (TMS, tDCS,
 > ...)).]

- [**Physiological recordings:** Give a description and brief purpose
 > statement of any physiological data that will be collected from
 > the participants before/during/after fMRI (e.g. eye-tracking,
 > pulse, electrocardiography, plethysmography (pulse oximetry),
 > respiration, blood pressure, blood samples, skin conductance
 > (SCR), electromyography, etc.). For each measure, mention the
 > device.]



[*Note that parts of this section may be covered in the Design Plan
section instead.*]

[Sample Size\*]
--------------------------

[State your target sample size and, if applicable, your stopping rule.
Justify your choices.]

[Justification of sample size or stopping rule:]



 [__or NA] [Power Analysis for fMRI or behavioral analysis. Please provide all details on your calculation. (strongly recommended, no standard procedures for fMRI power analysis but see [[https://brainpower.readthedocs.io/en/latest/index.html]{.underline}](https://brainpower.readthedocs.io/en/latest/index.html) for available tools)]
 ------------------------ ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 [__or NA] [Time constraints (e.g., will recruit for one year or until X date)]
 [__or NA] [Money constraints (e.g., monetary support will support up to X subjects)]
 [__or NA] [Personnel constraints (e.g., will recruit for time period in which personnel support is available)]
 [__] [Other: ___________________]

[If possible, include contingencies for if your target sample size is
not met. E.g., how will hypotheses be adopted to better powered
question?]

[Variables]
======================

[*In this section you can describe all variables (both manipulated and
measured variables) that will later be used in your analysis plan. In
your analysis plan, you will have the opportunity to describe how each
variable will be used. If you have variables which you are measuring for
exploratory analyses, you are not required to list them, though you are
permitted to do so.*]

[Manipulated variables]
----------------------------------

[Describe all variables you plan to manipulate and the levels or
treatment arms of each variable. This is not applicable to an
observational study.]

[Measured variables\*]
---------------------------------

[Behavioral data]

[Describe each variable that you will measure and indicate the
corresponding confirmatory hypothesis. You can use the checklist
below.]

+-----------------------------------+-----------------------------------+
| **[Measured | |
| variables]** | |
+===================================+===================================+
| [\ | [**Outcome** measures/dependent |
| \ | variables (specify whether |
| __] | confirmatory or exploratory |
| | outcome, how variable was |
| | measured, scale/range of measure, |
| | which subscale/component of |
| | measure you will |
| | use).] |
+-----------------------------------+-----------------------------------+
| [\ | [**Predictor** |
| __] | measures/independent variables |
| | (specific measure, scale/range of |
| | measure, which subscale/component |
| | of measure you will |
| | use).] |
+-----------------------------------+-----------------------------------+
| [\ | [**Covariate** measures (specific |
| __or NA] | measure, scale/range of measure, |
| | which subscale/component of |
| | measure you will |
| | use).] |
+-----------------------------------+-----------------------------------+
| **[Quality control]** | |
+-----------------------------------+-----------------------------------+
| [\ | [Any outcome-neutral criteria |
| \ | that must be met for successful |
| \ | testing of the stated hypotheses. |
| __] | Such quality checks might include |
| | the absence of floor or ceiling |
| | effects in data distributions, |
| | positive controls, or other |
| | quality checks that are |
| | orthogonal to the experimental |
| | hypotheses.] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [How will you determine which |
| | subjects, data points or measures |
| | (if any) to **exclude** from your |
| | analyses? If possible, specify |
| | objective exclusion criteria (due |
| | to technical errors, slow |
| | reactions, instructions not |
| | understood, accuracy below a |
| | certain threshold, or for any |
| | other reasons).] |
+-----------------------------------+-----------------------------------+
| | [How will you deal with |
| | incomplete or missing data (e.g., |
| [__or NA] | missing timepoints or |
| | missing/incomplete data within or |
| | between runs; what percent |
| | missing will be included)? Under |
| | what conditions would data be |
| | replaced and how?] |
+-----------------------------------+-----------------------------------+
| [\ | [If possible, define contingency |
| \ | plans how to proceed in such |
| \ | cases, (e.g., plans if x% of |
| __or NA] | behavioral data is missing; if |
| | the X questionnaire is missing |
| | for more than 10% of participants |
| | we will not use it or if X does |
| | not show variability in response |
| | (either ceiling or floor effects) |
| | in which we cannot look at |
| | behavioral pattern of interest, |
| | we will not use that |
| | questionnaire and use Y |
| | questionnaire |
| | instead).] |
+-----------------------------------+-----------------------------------+
| **[Transformations]** | |
+-----------------------------------+-----------------------------------+
| | [If you plan on transforming, |
| | centering, recoding the data, or |
| | will require a coding scheme for |
| | categorical variables, please |
| | describe that |
| | process.] |
| [__or NA] | |
| | [Include contingency plans for |
| | transformation: (e.g., |
| | transformations that will occur |
| | if data are skewed or for model |
| | convergence/multicollinearity)]{d |
| | ir="ltr"} |
+-----------------------------------+-----------------------------------+
| **[Code]** | |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Link to shared code for scoring |
| | behavioral data.] |
+-----------------------------------+-----------------------------------+





[fMRI data]

[Describe what variable will be measured (e.g., BOLD response) and
detail all preprocessing steps. You can fill in the table or write
paragraph below as you would for paper and use the table as checklist of
topics covered.]

[For each piece of software used, give the version number. Also indicate
which platform you ran the software on.]

+-----------------------+-----------------------+-----------------------+
| [**Quality | **[software, | |
| control**] | version]** | |
+=======================+=======================+=======================+
| [\ | [incidental findings | |
| \ | (Protocol for review | |
| __or NA] | of any incidental | |
| | findings, and how | |
| | they are handled in | |
| | particular with | |
| | respect to possible | |
| | exclusion of a | |
| | subject's | |
| | data.)] | |
+-----------------------+-----------------------+-----------------------+
| [\ | [motion monitoring | |
| \ | (For functional | |
| \ | acquisitions, any | |
| __] | visual or qualitative | |
| | checks for severe | |
| | motion; likewise, for | |
| | structural images, | |
| | checks on motion or | |
| | general image | |
| | quality.) Including | |
| | prospective | |
| | quantitative motion | |
| | monitoring and/or | |
| | correction?]{dir="ltr | |
| | "} | |
+-----------------------+-----------------------+-----------------------+
| | [How will you | |
| | determine which data | |
| | points or samples (if | |
| | any) to exclude from | |
| | your analyses? How | |
| | will outliers be | |
| | defined and | |
| | handled?] | |
| | | |
| | [If possible, specify | |
| [__] | objective exclusion | |
| | criteria, | |
| | e.g.] | |
| | | |
| | - [a participant | |
| | has X percentage | |
| | of volumes with | |
| | motion or exceeds | |
| | pre-defined | |
| | motion | |
| | threshold?]{dir=" | |
| | ltr"} | |
| | | |
| | - [general | |
| | artifacts | |
| | qualitatively or | |
| | quantitatively | |
| | defined (multi | |
| | band stripes, | |
| | respiration-relat | |
| | ed | |
| | ... )] | |
| | | |
| | - [registration | |
| | fails because of | |
| | atrophy, brain | |
| | lesion | |
| | ...] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [How will you deal | |
| NA] | with incomplete or | |
| | missing data (e.g., | |
| | missing timepoints or | |
| | missing/incomplete | |
| | data within or | |
| | between runs; what | |
| | percent missing will | |
| | be included)? Under | |
| | what conditions would | |
| | data be | |
| | replaced?] | |
+-----------------------+-----------------------+-----------------------+
| [\ | [Other quantitative | |
| \ | quality control | |
| __or NA] | metrics | |
| | (signal-to-noise | |
| | ratio, | |
| | contrast-to-noise | |
| | ratio, motion | |
| | parameters, outliers, | |
| | etc)? How will these | |
| | be assessed (e.g. | |
| | which software, | |
| | version, etc)? Will | |
| | any of these metrics | |
| | factor into the | |
| | decision to exclude | |
| | subjects? If so, | |
| | how?] | |
+-----------------------+-----------------------+-----------------------+
| [**Anatomical | | |
| preprocessing** (e.g. | | |
| which steps are taken | | |
| before coregistration | | |
| of anatomical & | | |
| functional)]{dir="ltr | | |
| "} | | |
+-----------------------+-----------------------+-----------------------+
| [__or | [Intensity | |
| NA] | non-uniformity | |
| | correction]{dir="ltr" | |
| | } | |
+-----------------------+-----------------------+-----------------------+
| [__or | [brain | |
| NA] | extraction]{dir="ltr" | |
| | } | |
+-----------------------+-----------------------+-----------------------+
| [__or | [tissue | |
| NA] | segmentation]{dir="lt | |
| | r"} | |
+-----------------------+-----------------------+-----------------------+
| **[Functional | | |
| preprocessing]{dir="l | | |
| tr"}** | | |
+-----------------------+-----------------------+-----------------------+
| [\ | [Remove first volumes | |
| __or NA] | to reach steady-state | |
| | (during acquisition | |
| | or preprocessing)? | |
| | How many volumes were | |
| | discarded?]{dir="ltr" | |
| | } | |
+-----------------------+-----------------------+-----------------------+
| [__or | [**Distortion | |
| NA] | correction** | |
| | (fieldmap, ap-pa | |
| | acquisitions)]{dir="l | |
| | tr"} | |
+-----------------------+-----------------------+-----------------------+
| [__or | [**Intensity | |
| NA] | normalization**]{dir= | |
| | "ltr"} | |
+-----------------------+-----------------------+-----------------------+
| [**\ | [**Slice timing | |
| **__or | correction** (specify | |
| NA] | reference slice, | |
| | e.g., first slice, | |
| | and interpolation, | |
| | e.g., Fourier phase | |
| | shift | |
| | interpolation)]{dir=" | |
| | ltr"} | |
+-----------------------+-----------------------+-----------------------+
| [**\ | [**Primary motion | |
| \ | correction | |
| **__or | (realignment)** | |
| NA] | (reference scan for | |
| | realignment, image | |
| | similarity metric, | |
| | type of interpolation | |
| | used, | |
| | degrees-of-freedom | |
| | and optimization | |
| | method)] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [**Intrasubject | |
| NA] | registration (e.g. | |
| | anatomical to | |
| | functional)**]{dir="l | |
| | tr"} | |
+-----------------------+-----------------------+-----------------------+
| [**\ | [Directionality (e.g. | |
| **__or | anatomical to | |
| NA] | functional, | |
| | functional session 1 | |
| | to functional session | |
| | 2, etc)] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [Transformation model | |
| NA] | (linear or | |
| | nonlinear)]{dir="ltr" | |
| | } | |
+-----------------------+-----------------------+-----------------------+
| [__or | [Degrees of | |
| NA] | freedom] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [Interpolation | |
| NA] | method] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [Image similarity | |
| NA] | metric] | |
+-----------------------+-----------------------+-----------------------+
| [\ | **[Intersubject | |
| __or NA] | registration (e.g. | |
| | anatomical/functional | |
| | to | |
| | template)] | |
| | ** | |
+-----------------------+-----------------------+-----------------------+
| [**\ | [Brain image template | |
| **__or | space, name, modality | |
| NA] | and resolution (e.g., | |
| | MNI Avg152, T1 2 × 2 | |
| | × 2 mm; customized | |
| | sample | |
| | template)] | |
+-----------------------+-----------------------+-----------------------+
| [**\ | [Directionality (e.g. | |
| **__or | anatomical to | |
| NA] | functional, | |
| | functional session 1 | |
| | to functional session | |
| | 2, etc)] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [Transformation model | |
| NA] | (linear or | |
| | nonlinear)]{dir="ltr" | |
| | } | |
+-----------------------+-----------------------+-----------------------+
| [__or | [Degrees of | |
| NA] | freedom] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [Interpolation | |
| NA] | method] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [Image similarity | |
| NA] | metric] | |
+-----------------------+-----------------------+-----------------------+
| [**\ | **[Smoothing]{dir="lt | |
| \ | r"}** | |
| \ | | |
| \ | [Size and type of | |
| \ | smoothing kernel | |
| **__or | (provide | |
| NA] | justification for | |
| | size; e.g., for a | |
| | group study, "12 mm | |
| | FHWM Gaussian | |
| | smoothing applied to | |
| | ameliorate | |
| | differences in | |
| | intersubject | |
| | localization"; for | |
| | single subject fMRI | |
| | "6 mm FWHM Gaussian | |
| | smoothing used to | |
| | reduce | |
| | noise")] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [**Temporal | |
| NA] | filtering** (type of | |
| | filter, frequency | |
| | band)] | |
+-----------------------+-----------------------+-----------------------+
| [**Flowchart**]{dir=" | | |
| ltr"} | | |
+-----------------------+-----------------------+-----------------------+
| [\ | [A flowchart can be | |
| __or NA] | attached that depicts | |
| | the order of the | |
| | preprocessing steps | |
| | for each acquisition | |
| | type (anatomical and | |
| | functional).]{dir="lt | |
| | r"} | |
+-----------------------+-----------------------+-----------------------+
| **[Code]** | | |
+-----------------------+-----------------------+-----------------------+
| [__or | [Link to shared code | |
| NA] | for preprocessing | |
| | data] | |
+-----------------------+-----------------------+-----------------------+

[Analysis Plan]
==========================

[*In this section, you describe all confirmatory analyses you plan to
conduct. Be as specific as possible (e.g. assign each hypothesis to be
tested to the corresponding model in this section; specify the usage of
covariates in sensitivity analyses and the selection of regions of
interest). If you plan to include additional fMRI analyses techniques,
check Appendix 3 for checklists.*]

[Statistical modeling\*]
-----------------------------------

[Behavioral analysis]

[Specify all analyses to test your hypotheses. Remember that all
confirmatory analyses specified below must be reported in the final
article, and any additional analyses must be noted as exploratory or
hypothesis generating. For each hypothesis, include the following
information:]

+-----------------------------------+-----------------------------------+
| [\ | [Statistical model (e.g., ANOVA, |
| __] | multiple regression, etc.) and |
| | its specification (that includes |
| | each variable that will be |
| | included as predictor/factor |
| | (incl. its levels), outcome, or |
| | covariate).] |
+===================================+===================================+
| [__or NA] | [Specify any interactions that |
| | will be tested] |
+-----------------------------------+-----------------------------------+
| [__] | [Name assumptions that need to be |
| | met and how they will be |
| | tested] |
+-----------------------------------+-----------------------------------+
| [__] | [Include a contingency plan in |
| | case assumptions are not |
| | met] |
+-----------------------------------+-----------------------------------+
| [__] | [Include software and packages |
| | used for each test] |
+-----------------------------------+-----------------------------------+
| | [What criteria will you use to |
| | make inferences? Please describe |
| [__] | the information you'll use (e.g. |
| | p-values, Bayes factors, specific |
| | model fit indices), as well as |
| | cut-off criterion, where |
| | appropriate.] |
+-----------------------------------+-----------------------------------+
| [__] | [Note whether you will adjust for |
| | multiple comparisons and how |
| | (e.g. correction procedure, |
| | number of tests included ...) or |
| | explain why not.] |
+-----------------------------------+-----------------------------------+



[fMRI analysis]

[Specify all analyses to test each hypothesis. Please include the type
of model and the specification of the model (this includes each variable
that will be included as predictors, outcomes, or covariates). Also
specify any interactions that will be tested. Remember that all
confirmatory analyses specified below must be reported in the final
article, and any additional analyses must be noted as exploratory or
hypothesis generating.]

[Specify whether you plan to perform whole-brain or ROI-analysis. In
case of ROI, be specific (e.g. defined based on anatomical definition,
prior study cluster, Neurosynth definition, Parcellation definition).
List regressors of interest at the neural level and corresponding
confirmatory hypothesis. If applicable, describe covariate
measures.]

[For necessary details regarding functional connectivity and decoding
analysis, please see **Appendix 4**.]





+-----------------------+-----------------------+-----------------------+
| [**Individual (first) | | |
| level | | |
| modeling**]{dir="ltr" | | |
| } | | |
+=======================+=======================+=======================+
| [__] | [Event­-related | |
| | predictors (modeled | |
| | duration (or zero), | |
| | whether parametric | |
| | modulation is | |
| | used)] | |
+-----------------------+-----------------------+-----------------------+
| [__] | [Block Design | |
| | predictors (note | |
| | whether or not | |
| | baseline will be | |
| | explicitly | |
| | modeled)] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [Include design | |
| NA] | matrix and | |
| | efficiency/collineari | |
| | ty | |
| | measure | |
| | (recommended)]{dir="l | |
| | tr"} | |
+-----------------------+-----------------------+-----------------------+
| [__] | [HRF basis (e.g. | |
| | canonical only, | |
| | canonical with | |
| | temporal derivative, | |
| | or with temporal and | |
| | dispersion | |
| | derivative, Finite | |
| | Impulse Response | |
| | model)] | |
+-----------------------+-----------------------+-----------------------+
| [__] | [Movement regressors; | |
| | specify if squares | |
| | and/or temporal | |
| | derivative | |
| | used.] | |
+-----------------------+-----------------------+-----------------------+
| [__] | [Any other nuisance | |
| | regressors, and | |
| | whether they were | |
| | entered as | |
| | interactions (e.g. | |
| | with a task effect in | |
| | 1st level fMRI, or | |
| | with group | |
| | effect).] | |
+-----------------------+-----------------------+-----------------------+
| [__] | [Any | |
| | orthogonalization of | |
| | regressors or | |
| | parametric | |
| | modulators, and set | |
| | of other regressors | |
| | used to orthogonalize | |
| | against.] | |
+-----------------------+-----------------------+-----------------------+
| [__] | [Contrast | |
| | construction (Exactly | |
| | what terms are | |
| | subtracted from what? | |
| | Define these in terms | |
| | of task or stimulus | |
| | conditions instead of | |
| | underlying | |
| | psychological | |
| | concepts.] | |
+-----------------------+-----------------------+-----------------------+
| [__] | [Model | |
| | settings] | |
| | | |
| | - [For | |
| | > *mass-­univaria | |
| | te | |
| | > first level | |
| | > fMRI,* these | |
| | > include drift | |
| | > regressors | |
| | > (e.g. DCT basis | |
| | > in SPM, with | |
| | > specified | |
| | > cut­off) and | |
| | > autocorrelation | |
| | > model (e.g., | |
| | > global | |
| | > approximate | |
| | > AR(1) in SPM; | |
| | > locally | |
| | > recularized | |
| | > autocorrelation | |
| | > function in | |
| | > FSL). Check | |
| | > your imaging | |
| | > toolbox to see | |
| | > default | |
| | > settings.]{dir= | |
| | "ltr"} | |
+-----------------------+-----------------------+-----------------------+
| [**Group | | |
| (second)-level | | |
| modeling**]{dir="ltr" | | |
| } | | |
+-----------------------+-----------------------+-----------------------+
| | [State and justify | |
| | statistical model and | |
| | estimation method, | |
| | inference type | |
| [__] | (mixed/random effects | |
| | or fixed), e.g., | |
| | "Mixed effects | |
| | inference with one | |
| | sample t-test on | |
| | summary statistic" | |
| | (SPM2/SPM5), e.g., | |
| | "Mixed effects | |
| | inference with | |
| | Bayesian 2-level | |
| | model with fast | |
| | approximation to | |
| | posterior probability | |
| | of activation." | |
| | (FSL).] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [If more than | |
| NA] | 2-levels, describe | |
| | the levels and | |
| | assumptions of the | |
| | model (e.g., are | |
| | variances assumed | |
| | equal between | |
| | groups)] | |
+-----------------------+-----------------------+-----------------------+
| [\ | [If multiple | |
| \ | measurements per | |
| \ | subject, list method | |
| __or NA] | to account for within | |
| | subject correlation, | |
| | exact assumptions | |
| | made about | |
| | correlation/variance, | |
| | e.g., SPM: | |
| | "Within-subject | |
| | correlation estimated | |
| | at F-significant | |
| | voxels (P \<0.001), | |
| | then used globally | |
| | over whole brain"; | |
| | or, if variances for | |
| | each measure are | |
| | allowed to vary, | |
| | "Within-subject | |
| | correlation and | |
| | relative variance | |
| | estimated..."]{dir="l | |
| | tr"} | |
+-----------------------+-----------------------+-----------------------+
| [\ | [For group model with | |
| \ | repeated measures, | |
| __or NA] | specify how condition | |
| | effects are modeled | |
| | (e.g. as factors, or | |
| | as linear trends), | |
| | and whether subject | |
| | effects are modeled | |
| | (i.e. as regressors, | |
| | as opposed to with a | |
| | covariance | |
| | structure).]{dir="ltr | |
| | "} | |
+-----------------------+-----------------------+-----------------------+
| [__or | [For group effects: | |
| NA] | clearly state whether | |
| | or not covariates are | |
| | split by group (i.e. | |
| | fit as a | |
| | group-by-­covariate | |
| | interaction).]{dir="l | |
| | tr"} | |
+-----------------------+-----------------------+-----------------------+
| | [Model type (e.g., | |
| | Mass Univariate, | |
| [__] | Multivariate (e.g. | |
| | ICA on whole brain | |
| | data), Local | |
| | Multivariate (e.g. | |
| | "searchlight"), | |
| | Representational | |
| | Similarity Analysis, | |
| | psychophysiological | |
| | interaction | |
| | (PPI))] | |
+-----------------------+-----------------------+-----------------------+
| | [Model | |
| | settings] | |
| | | |
| | - [For | |
| | > *mass-­univaria | |
| | te | |
| | > group level | |
| | > fMRI* these | |
| | > include fixed | |
| | > effects (all | |
| | > subjects' data | |
| | > in one model), | |
| | > or random or | |
| | > mixed ­effects | |
| | > model | |
| | > (implemented | |
| | > with (1) | |
| | > Ordinary least | |
| | > squares (OLS, | |
| | > aka unweighted | |
| | > summary | |
| | > statistics | |
| [__] | > approach; SPM | |
| | > default, FSL | |
| | > FEAT's "Simple | |
| | > OLS"), (2) | |
| | > weighted least | |
| | > squares (i.e. | |
| | > FSL FEAT's | |
| | > "FLAME 1") | |
| | > using | |
| | > voxel­wise | |
| | > estimate of | |
| | > between subject | |
| | > variance, | |
| | > or (3) Global | |
| | > weighted least | |
| | > squares (i.e. | |
| | > SPM's | |
| | > MFX)).]{dir="lt | |
| | r"} | |
| | | |
| | - [With *any group | |
| | > (multi­subject) | |
| | > model*, | |
| | > indicate any | |
| | > specific | |
| | > variance | |
| | > structure, e.g. | |
| | > Unequal | |
| | > variance | |
| | > between groups | |
| | > (and if | |
| | > globally | |
| | > pooled, as in | |
| | > SPM), or if | |
| | > repeated | |
| | > measures, the | |
| | > specific | |
| | > covariance | |
| | > structure | |
| | > assumed (e.g. | |
| | > compound | |
| | > symmetric, or | |
| | > arbitrary; if | |
| | > globally | |
| | > pooled).]{dir=" | |
| | ltr"} | |
| | | |
| | - [For *local­ | |
| | > multivariate | |
| | > report,* | |
| | > indicate the | |
| | > number of | |
| | > voxels in the | |
| | > local model, | |
| | > and the Local | |
| | > model used | |
| | > (e.g. Canonical | |
| | > Correlation | |
| | > Analysis) with | |
| | > any constraints | |
| | > (e.g. positive | |
| | > weights | |
| | > only).]{dir="lt | |
| | r"} | |
+-----------------------+-----------------------+-----------------------+
| [**ROI | | |
| analysis**]{dir="ltr" | | |
| } | | |
+-----------------------+-----------------------+-----------------------+
| [__or | [Will you limit your | |
| NA] | analysis to a | |
| | specific ROI? (e.g. | |
| | unilateral, | |
| | cerebellum)]{dir="ltr | |
| | "} | |
+-----------------------+-----------------------+-----------------------+
| [__or | [How will you define | |
| NA] | your ROI (e.g., | |
| | functional, | |
| | anatomical, | |
| | meta-analysis, parcel | |
| | localizer)?]{dir="ltr | |
| | "} | |
+-----------------------+-----------------------+-----------------------+
| [__or | [Justify definition | |
| NA] | of ROI and analysis | |
| | conducted with it: | |
| | (e.g., if your ROI is | |
| | defined based on the | |
| | cluster; how will you | |
| | ensure your ROI | |
| | analyses are not | |
| | circular?)]{dir="ltr" | |
| | } | |
+-----------------------+-----------------------+-----------------------+
| [__or | [How was signal | |
| NA] | extracted within | |
| | ROI?(e.g., average | |
| | parameter estimates, | |
| | FIR | |
| | deconvolution?)]{dir= | |
| | "ltr"} | |
+-----------------------+-----------------------+-----------------------+
| [__or | [If percent signal | |
| NA] | change reported, how | |
| | was scaling factor | |
| | determined]{dir="ltr" | |
| | } | |
| | | |
| | [(e.g., height of | |
| | block regressor or | |
| | height of isolated | |
| | event | |
| | regressor)?]{dir="ltr | |
| | "} | |
+-----------------------+-----------------------+-----------------------+
| **[Inference on | | |
| statistic image | | |
| (thresholding)]{dir=" | | |
| ltr"}** | | |
+-----------------------+-----------------------+-----------------------+
| [__] | [Whole brain or a | |
| | specific search | |
| | region? Specify type | |
| | of search region | |
| | analysis, and the | |
| | volume in voxels or | |
| | mm^3^)] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [If not whole brain, | |
| NA] | state how the region | |
| | will be determined; | |
| | method for | |
| | constructing region | |
| | should be independent | |
| | of present statistic | |
| | image:] | |
| | | |
| | - [Carefully | |
| | > describe any | |
| | > small volume | |
| | > (SV) correction | |
| | > used for each | |
| | > contrast.]{dir= | |
| | "ltr"} | |
| | | |
| | - [If the SV | |
| | > correction mask | |
| | > will be defined | |
| | > anatomically, | |
| | > provide named | |
| | > anatomical | |
| | > regions from a | |
| | > publicly | |
| | > available ROI | |
| | > atlas and, if | |
| | > probability-bas | |
| | ed, | |
| | > state selected | |
| | > threshold.]{dir | |
| | ="ltr"} | |
| | | |
| | > [● If the SV | |
| | > correction mask | |
| | > will be | |
| | > functionally | |
| | > defined, clearly | |
| | > describe the | |
| | > functional task and | |
| | > identify any risk | |
| | > of | |
| | > circularity.]{dir=" | |
| | ltr"} | |
| | | |
| | - [All SV | |
| | > corrections | |
| | > should be fully | |
| | > described in | |
| | > the methods | |
| | > section, not | |
| | > just mentioned | |
| | > in passing in | |
| | > the | |
| | > results.]{dir=" | |
| | ltr"} | |
+-----------------------+-----------------------+-----------------------+
| [__] | [Statistical type, | |
| | e.g., voxel-wise (aka | |
| | peak­wise in SPM) or | |
| | cluster-wise (cluster | |
| | size, cluster mass, | |
| | threshold­free | |
| | Cluster Enhancement | |
| | (TFCE)).] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [Statistical | |
| NA] | threshold used to | |
| | infer significance | |
| | (e.g. p \< | |
| | 0.05)] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [If cluster-wise | |
| NA] | (cluster size or | |
| | mass) significance, | |
| | state | |
| | cluster-defining | |
| | threshold (e.g., P = | |
| | 0.001).] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [For all cluster­wise | |
| NA] | methods, report | |
| | neighborhood size | |
| | used to form clusters | |
| | (e.g. 6, 18 or | |
| | 26).] | |
| | | |
| | | |
+-----------------------+-----------------------+-----------------------+
| [__or | [For TFCE, report use | |
| NA] | of non­default TFCE | |
| | parameters.]{dir="ltr | |
| | "} | |
+-----------------------+-----------------------+-----------------------+
| [\ | [P value computation. | |
| __] | Report if anything | |
| | but standard | |
| | parametric inference | |
| | used to obtain | |
| | (uncorrected) | |
| | P­-values. If | |
| | nonparametric method | |
| | was used, report | |
| | method (e.g. | |
| | permutation or | |
| | bootstrap) and number | |
| | of | |
| | permutations/samples | |
| | used.] | |
+-----------------------+-----------------------+-----------------------+
| [\ | [Multiple test | |
| \ | correction. For | |
| __] | mass­univariate, | |
| | specify the type of | |
| | correction and how it | |
| | is obtained, e.g., | |
| | Familywise Error | |
| | (Random Field Theory | |
| | (typical), | |
| | Permutation, Monte | |
| | Carlo, Bonferroni), | |
| | False Discovery Rate | |
| | (Benjamini & Hochberg | |
| | FDR (typical), | |
| | Positive FDR, Local | |
| | FDR, Cluster­level | |
| | FDR), or | |
| | none/uncorrected.]{di | |
| | r="ltr"} | |
+-----------------------+-----------------------+-----------------------+
| [__or | [If permutation or | |
| NA] | Monte Carlo, report | |
| | the number of | |
| | permutations/samples. | |
| | ] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [If Monte Carlo, note | |
| NA] | brain mask and | |
| | smoothness used, and | |
| | how smoothness was | |
| | estimated.]{dir="ltr" | |
| | } | |
+-----------------------+-----------------------+-----------------------+
| [__or | [If FWE found by | |
| NA] | random field theory, | |
| | list smoothness in mm | |
| | FWHM and the RESEL | |
| | count.] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [If FWE found by | |
| NA] | simulation (e.g., | |
| | AFNI AlphaSim), | |
| | provide details of | |
| | parameters for | |
| | simulation.]{dir="ltr | |
| | "} | |
+-----------------------+-----------------------+-----------------------+
| [__or | [If not a standard | |
| NA] | method, specify the | |
| | method for finding | |
| | significance (e.g., | |
| | "Custom in-lab | |
| | software was used to | |
| | construct statistic | |
| | maps and thresholded | |
| | at FDR\< 0.05 | |
| | (Benjamini and | |
| | Hochberg, | |
| | 1995)"] | |
+-----------------------+-----------------------+-----------------------+
| [__or | [False negative | |
| NA] | discussion: Any | |
| | discussion of failure | |
| | to reject the null | |
| | hypothesis (e.g., | |
| | lack of activation in | |
| | a particular region) | |
| | should be accompanied | |
| | by SNR or effect size | |
| | of the actually | |
| | observed effect | |
| | (allows reader to | |
| | infer power to | |
| | estimate an | |
| | effect)] | |
+-----------------------+-----------------------+-----------------------+



*[Recommendations of fMRI details come from Nichols et al., 2016;
Poldrack et al., 2008.]*

[*For extended checklist guidelines for this section following data
analysis, see OHBM COBIDAS report Nichols et al., 2016.*]



[Follow-up Analyses]
-------------------------------

[If not specified previously, will you be conducting any confirmatory
analyses to follow up on effects in your statistical model, such as
subgroup analyses, pairwise or complex contrasts, or follow-up tests
from interactions? Remember that any analyses not specified in this
research plan must be noted as exploratory.]



[Exploratory Analyses] 
----------------------------------

[If you plan to explore your data set to look for unexpected differences
or relationships, you may describe those tests here. An exploratory test
is any test where a prediction is not made up front, or there are
multiple possible tests that you are going to use. A statistically
significant finding in an exploratory test is a great way to form a new
confirmatory hypothesis, which could be registered at a later
time.]

[Appendices]
=======================

[Appendix 1: Examples of fMRI study pre-registrations]
-----------------------------------------------------------------

- [Pre data collection preregistration following a structure similar
 > to the present template with extensive detail:
 > [[https://osf.io/2zhve]{.underline}](https://osf.io/2zhve)]

- [Pre data collection preregistration with extensive detail in
 > flow-text:
 > [[https://osf.io/7q68p/]{.underline}](https://osf.io/7q68p/)]

- [studies with standard preprocessing approaches (SPM, fMRIprep):
 > [[https://osf.io/5mx3w]{.underline}](https://osf.io/5mx3w);
 > [[https://osf.io/hndbq]{.underline}](https://osf.io/hndbq)
 > \[previously collected data\]]

- [concise preregistration of functional connectivity analyses of
 > existing data:
 > [[https://osf.io/utqq2]{.underline}](https://osf.io/utqq2)]

- [methods analysis on publicly available datasets:
 > [[https://osf.io/2jxdk/]{.underline}](https://osf.io/2jxdk/)]

- [Example of a multi-study pre-registration:
 > [[https://osf.io/wzd8a]{.underline}](https://osf.io/wzd8a)]

 
-------------

[Appendix 2: fMRI data acquisition checklists]
---------------------------------------------------------

[*If your study includes multiple different scanners, or if multiple
different sequences of the same category are used (e.g. multiple
functional MRI sequences), please fill out a separate table for each
scanner and sequence. *]



**[Participant preparation]**

 [Test scanning (Report type of (mock) scanner and protocol; i.e. duration, types of simulated scans, experiments).] [__or NA]
 -------------------------------------------------------------------------------------------------------------------------------- ------------------------
 [Special equipment to reduce/monitor head motion (head cases, prospective motion tracking ...)] [__or NA]
 [Specific accommodations (e.g., pediatric, parent present, asleep)] [__or NA]
 [Experimental personnel (number of planned personnel to interact with participants)] [__or NA]



***[MRI system]***

 [Manufacturer] [__]
 ---------------------------------------- -------------------
 [Model name] [__]
 [Software version] [__]
 [Field strength (in Tesla)] [__]
 [Transmission coil] [__]
 [Receiving head coil] [__]



[***MRI acquisition***]

*[If this is a study using multiple different scanners, or if multiple
different sequences of the same category are used (e.g. multiple
functional MRI sequences), please fill out a separate table for each
scanner and sequence.]*

+-----------------------+-----------------------+-----------------------+
| **[For all | [Pulse sequence | [__] |
| acquisitions:]{dir="l | (gradient/spin echo | |
| tr"}** | etc.)] | |
+=======================+=======================+=======================+
| | [Readout (EPI, | [__] |
| | spiral, 3D, partial | |
| | Fourier, | |
| | etc.)] | |
+-----------------------+-----------------------+-----------------------+
| | [Echo time | [__] |
| | (TE)] | |
+-----------------------+-----------------------+-----------------------+
| | [Repetition time | [__] |
| | (TR)] | |
| | | |
| | - [For multi­shot | |
| | > acquisitions, | |
| | > additionally | |
| | > the time per | |
| | > volume.]{dir="l | |
| | tr"} | |
+-----------------------+-----------------------+-----------------------+
| | [Flip angle | [__] |
| | (FA)] | |
+-----------------------+-----------------------+-----------------------+
| | [Acquisition time | [__] |
| | (duration of | |
| | acquisition)]{dir="lt | |
| | r"} | |
+-----------------------+-----------------------+-----------------------+
| | [Field of view | [__] |
| | (FOV)] | |
+-----------------------+-----------------------+-----------------------+
| | [FOV | [__] |
| | position?] | |
| | | |
| | - [Full or partial | |
| | > brain | |
| | > coverage?]{dir= | |
| | "ltr"} | |
| | | |
| | - [Guided by | |
| | > anatomical | |
| | > landmarks?]{dir | |
| | ="ltr"} | |
| | | |
| | - [Guided by | |
| | > built-in | |
| | > scanner | |
| | > functions (e.g. | |
| | > AUTO | |
| | > ALIGN)?]{dir="l | |
| | tr"} | |
+-----------------------+-----------------------+-----------------------+
| | [Voxel size | [__] |
| | (in-plane)]{dir="ltr" | |
| | } | |
+-----------------------+-----------------------+-----------------------+
| | [Slice | [__] |
| | thickness] | |
+-----------------------+-----------------------+-----------------------+
| | [Slice | [__] |
| | gap] | |
+-----------------------+-----------------------+-----------------------+
| | [Slice selection | [__] |
| | direction (axial, | |
| | sagittal, coronal, | |
| | oblique)] | |
+-----------------------+-----------------------+-----------------------+
| | [Slice | [__] |
| | angulation]{dir="ltr" | |
| | } | |
+-----------------------+-----------------------+-----------------------+
| | [Slice acquisition | [__] |
| | order (ascending, | |
| | descending, | |
| | interleaved)]{dir="lt | |
| | r"} | |
+-----------------------+-----------------------+-----------------------+
| | [Parallel imaging | [_ or NA] |
| | method (GRAPPA, PAT | |
| | ...)] | |
+-----------------------+-----------------------+-----------------------+
| | [Scanner-side | [_ or NA] |
| | preprocessing (e.g., | |
| | Including: Fat | |
| | saturation, | |
| | Reconstruction matrix | |
| | size differing from | |
| | acquisition matrix | |
| | size; | |
| | Prospective-motion | |
| | correction (including | |
| | details of any | |
| | optical tracking, and | |
| | how motion parameters | |
| | are used); Signal | |
| | inhomogeneity | |
| | correction; | |
| | Distortion-correction | |
| | .)] | |
+-----------------------+-----------------------+-----------------------+
| | [Phase encoding | [__] |
| | direction] | |
+-----------------------+-----------------------+-----------------------+
| **[Functional MRI | [Number of | [__] |
| /]** | volumes] | |
| | | |
| **[or \"dynamic (4D) | | |
| MRI e.g. functional, | | |
| perfusion | | |
| MRI\"]** | | |
+-----------------------+-----------------------+-----------------------+
| | [Single or | [__] |
| | multi-echo?]{dir="ltr | |
| | "} | |
+-----------------------+-----------------------+-----------------------+
| | [Simultaneous | [_ or NA] |
| | multislice | |
| | acquisition & | |
| | parameters (e.g. | |
| | multiband)]{dir="ltr" | |
| | } | |
+-----------------------+-----------------------+-----------------------+
| | [T1 stabilization | [_ or NA] |
| | (discarded "dummy" | |
| | scans *by | |
| | scanner*)] | |
+-----------------------+-----------------------+-----------------------+
| | > [Sparse sampling | |
| | > delay (delay in TR) | |
| | > if | |
| | > used.] | |
+-----------------------+-----------------------+-----------------------+
| **[T1-weighted | [Fat | [_ or NA] |
| imaging]** | suppression]{dir="ltr | |
| | "} | |
+-----------------------+-----------------------+-----------------------+
| **[Other anatomical | | [_ or NA] |
| imaging | | |
| (T2)]** | | |
+-----------------------+-----------------------+-----------------------+
| **[Inversion recovery | [Inversion time | [_ or NA] |
| sequences] | (TI)] | |
| ** | | |
+-----------------------+-----------------------+-----------------------+
| > **[Additional | [B0 field | [_ or NA] |
| > imaging] | maps] | |
| ** | | |
| > | - [echo difference | |
| > **[for | > between | |
| > distortion]{dir="lt | > acquisitions]{d | |
| r"}** | ir="ltr"} | |
| > | | |
| > **[correction]{dir= | | |
| "ltr"}** | | |
| | | |
| | | |
+-----------------------+-----------------------+-----------------------+
| | [ap-pa acquisitions | [_ or NA] |
| | (reverse | |
| | phase)] | |
| | | |
| | - [state if | |
| | > parameters | |
| | > differ from | |
| | > functional | |
| | > acquisition]{di | |
| | r="ltr"} | |
+-----------------------+-----------------------+-----------------------+
| [**Physiological | [Description | [_ or NA] |
| measures**]{dir="ltr" | (acquisition method, | |
| } | hardware) and brief | |
| | purpose of any | |
| | physiological data | |
| | that will be | |
| | collected from the | |
| | participants | |
| | before/during/after | |
| | fMRI (e.g. | |
| | eye-tracking, pulse, | |
| | electrocardiography, | |
| | plethysmography | |
| | (pulse oximetry), | |
| | respiration, blood | |
| | pressure, blood | |
| | samples, skin | |
| | conductance (SCR), | |
| | electromyography, | |
| | etc.).] | |
| | | |
| | | |
+-----------------------+-----------------------+-----------------------+
| **[Other imaging | [Give a description | |
| modalities]{dir="ltr" | and brief purpose | |
| }** | statement of any | |
| | other imaging | |
| | modalities that will | |
| | be included in your | |
| | study (e.g., EEG, | |
| | Neuromodulation (TMS, | |
| | tDCS, | |
| | ...)).] | |
+-----------------------+-----------------------+-----------------------+





[Appendix 3: Additional fMRI analyses]
-------------------------------------------------

+-----------------------------------+-----------------------------------+
| **[Functional | |
| connectivity]** | |
+===================================+===================================+
| *[Confound adjustment & filtering | |
| Report:]* | |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Method for detecting movement |
| | artifacts, movement-related |
| | variation, and remediation |
| | (e.g. 'scrubbing', 'despiking', |
| | etc)] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Use of global signal regression, |
| | exact type of global signal used |
| | and how it was |
| | computed] |
+-----------------------------------+-----------------------------------+
| [\ | [Whether a high or lowpass |
| __or NA] | temporal filtering is applied to |
| | data, and at which point in the |
| | analysis pipeline. Note, any |
| | temporal regression model using |
| | filtered data should have its |
| | regressors likewise |
| | filtered] |
+-----------------------------------+-----------------------------------+
| [*Multivariate method: | |
| Independent Component Analysis | |
| Report:*] | |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Algorithm to estimate |
| | components] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Number of components (if fixed), |
| | or algorithm for estimating |
| | number of components] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [If used, method to synthesize |
| | multiple runs] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Sorting method of IC's, if |
| | any] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Detailed description of how |
| | components were chosen for |
| | further analysis] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Dependent variable |
| | definition] |
+-----------------------------------+-----------------------------------+
| [*For seed-based analyses | |
| report:*] | |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Definition of the seed |
| | region(s)] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Rationale for choosing these |
| | regions] |
+-----------------------------------+-----------------------------------+
| [*For region-based analyses | |
| report:*] | |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Number of ROIs] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [How the ROI's are defined |
| | (e.g. citable anatomical atlas; |
| | auxiliary fMRI experiments); note |
| | if ROIs overlap] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Assignment of signals to regions |
| | (i.e. how a time series is |
| | obtained from each region, |
| | e.g. averaging or first singular |
| | vector)] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Note if considering only |
| | bilateral (L+R) merged |
| | regions] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Note if considering only |
| | interhemispheric homotopic |
| | connectivity] |
+-----------------------------------+-----------------------------------+
| [*Functional connectivity | |
| measure/model | |
| Report:*] | |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Measure of dependence used, |
| | e.g. Pearson's (full) |
| | correlation, partial correlation, |
| | mutual information, etc; also |
| | specify:] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Use of Fisher's Z-transform |
| | (Yes/No) and, if standardised, |
| | effective N is used to compute |
| | standard error (to account for |
| | any filtering operations on the |
| | data)] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Estimator used for partial |
| | correlation] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Estimator used for mutual |
| | information] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Regression model used to remove |
| | confounding effects (Pearson or |
| | partial correlation)] |
+-----------------------------------+-----------------------------------+
| [*Effectivity connectivity | |
| Report:*] | |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Model] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Algorithm used to fit |
| | model] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [If per subject model, method |
| | used to generalize inferences to |
| | population. Itemize models |
| | considered, and method used for |
| | model comparison] |
+-----------------------------------+-----------------------------------+
| [*Graph analysis*] | |
+-----------------------------------+-----------------------------------+
| [\ | [Report the 'dependent variable' |
| \ | and 'functional connectivity |
| __or NA] | measure' used (see above). |
| | Specify either:] |
| | |
| | - [Weighted graph analysis |
| | > or] |
| | |
| | - [Binarized graph analysis is |
| | > used, clarifying the method |
| | > used for thresholding |
| | > (e.g. a 10% density |
| | > threshold, or a |
| | > statistically defined |
| | > threshold); consider the |
| | > sensitivity of your |
| | > findings to the particular |
| | > choice of threshold |
| | > used] |
+-----------------------------------+-----------------------------------+
| [\ | [Itemise the graph summaries used |
| __or NA] | (e.g. clustering coefficient, |
| | efficiency, etc), whether these |
| | are global or per¬node/per¬edge |
| | summaries. In particular with |
| | fMRI or EEG, clarify if measures |
| | applied to individual subject |
| | networks or group |
| | networks] |
+-----------------------------------+-----------------------------------+
| **[Decoding | |
| analysis]** | |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Algorithm choice(s)] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Hyperparameter |
| | optimization] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Cross-validation regimen |
| | \[including whether |
| | stratification is |
| | applied\]] |
+-----------------------------------+-----------------------------------+
| [__or NA] | [Hold-out samples] |
+-----------------------------------+-----------------------------------+


