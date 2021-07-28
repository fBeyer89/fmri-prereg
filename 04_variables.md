# [Variables]

[*In this section you can describe all variables (both manipulated and measured
variables) that will later be used in your analysis plan. In your analysis plan,
you will have the opportunity to describe how each variable will be used. If you
have variables which you are measuring for exploratory analyses, you are not
required to list them, though you are permitted to do so.*]

## [Manipulated variables]

[Describe all variables you plan to manipulate and the levels or treatment arms
of each variable. This is not applicable to an observational study.]

## [Measured variables\*]

### [Behavioral data]

[Describe each variable that you will measure and indicate the corresponding
confirmatory hypothesis. You can use the checklist below.]

+-----------------------------------+-----------------------------------+ |
**[Measured variables]**
+===================================+===================================+ | [\ |
[**Outcome** measures/dependent | \ | variables (specify whether | __] |
confirmatory or exploratory outcome, how variable was measured, scale/range of
measure, which subscale/component of measure you will use).]

| [\ | [**Predictor** | __] | measures/independent variables (specific measure,
scale/range of measure, which subscale/component of measure you will use).]

| [\ | [**Covariate** measures (specific  __or NA] | measure, scale/range of
measure, which subscale/component of measure you will use).] |

| **[Quality control]**

| [\ | [Any outcome-neutral criteria | \ | that must be met for successful | \ |
testing of the stated hypotheses. | __] | Such quality checks might include the
absence of floor or ceiling effects in data distributions, positive controls, or
other quality checks that are orthogonal to the experimental hypotheses.]

| [__or NA] | [How will you determine which subjects, data points or measures
(if any) to **exclude** from your analyses? If possible, specify objective
exclusion criteria (due to technical errors, slow reactions, instructions not
understood, accuracy below a certain threshold, or for any other reasons).]

[How will you deal with incomplete or missing data (e.g., | [__or NA] | missing
timepoints or missing/incomplete data within or between runs; what percent
missing will be included)? Under what conditions would data be replaced and
how?]

| [\ | [If possible, define contingency | \ | plans how to proceed in such | \ |
cases, (e.g., plans if x% of | __or NA] | behavioral data is missing; if the X
questionnaire is missing for more than 10% of participants we will not use it or
if X does not show variability in response (either ceiling or floor effects) in
which we cannot look at behavioral pattern of interest, we will not use that
questionnaire and use Y questionnaire instead).]

| **[Transformations]**

| [If you plan on transforming, centering, recoding the data, or will require a
coding scheme for categorical variables, please describe that process.] | [__or
NA] | [Include contingency plans for transformation: (e.g., transformations that
will occur if data are skewed or for model convergence/multicollinearity)]{d
ir="ltr"}

| **[Code]** |

| [__or NA] | [Link to shared code for scoring behavioral data.]

### [fMRI data]

[Describe what variable will be measured (e.g., BOLD response) and detail all
preprocessing steps. You can fill in the table or write paragraph below as you
would for paper and use the table as checklist of topics covered.]

[For each piece of software used, give the version number. Also indicate which
platform you ran the software on.]

+-----------------------+-----------------------+-----------------------+ |
[**Quality | **[software, | control**] | version]\*\*
+=======================+=======================+=======================+ | [\ |
[incidental findings | \ | (Protocol for review | __or NA] | of any incidental
findings, and how they are handled in particular with respect to possible
exclusion of a subject's data.)]
+-----------------------+-----------------------+-----------------------+ | [\ |
[motion monitoring | \ | (For functional | \ | acquisitions, any | __] | visual
or qualitative checks for severe motion; likewise, for structural images, checks
on motion or general image quality.) Including prospective quantitative motion
monitoring and/or correction?]{dir="ltr "}
+-----------------------+-----------------------+-----------------------+ [How
will you determine which data points or samples (if any) to exclude from your
analyses? How will outliers be defined and handled?]

[If possible, specify | [__] | objective exclusion criteria, e.g.]

- [a participant has X percentage of volumes with motion or exceeds pre-defined
  motion threshold?]{dir=" ltr"}

- [general artifacts qualitatively or quantitatively defined (multi band
  stripes, respiration-relat ed ... )]

- [registration fails because of atrophy, brain lesion ...]
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [How will you deal | NA] | with incomplete or missing data (e.g.,
  missing timepoints or missing/incomplete data within or between runs; what
  percent missing will be included)? Under what conditions would data be
  replaced?]
  +-----------------------+-----------------------+-----------------------+ | [\
  | [Other quantitative | \ | quality control | **or NA] | metrics
  (signal-to-noise ratio, contrast-to-noise ratio, motion parameters, outliers,
  etc)? How will these be assessed (e.g. which software, version, etc)? Will any
  of these metrics factor into the decision to exclude subjects? If so, how?]
  +-----------------------+-----------------------+-----------------------+ |
  [**Anatomical  preprocessing** (e.g.  which steps are taken  before
  coregistration  of anatomical &  functional)]{dir="ltr  "} |
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [Intensity | NA] | non-uniformity correction]{dir="ltr" }
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [brain | NA] | extraction]{dir="ltr" }
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [tissue | NA] | segmentation]{dir="lt r"}
  +-----------------------+-----------------------+-----------------------+ |
  **[Functional  preprocessing]{dir="l  tr"}** |
  +-----------------------+-----------------------+-----------------------+ | [\
  | [Remove first volumes | **or NA] | to reach steady-state (during acquisition
  or preprocessing)? How many volumes were discarded?]{dir="ltr" }
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [**Distortion | NA] | correction\*\* (fieldmap, ap-pa
  acquisitions)]{dir="l tr"}
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [**Intensity | NA] | normalization**]{dir= "ltr"}
  +-----------------------+-----------------------+-----------------------+ |
  [**\ | [**Slice timing | **__or | correction** (specify | NA] | reference
  slice, e.g., first slice, and interpolation, e.g., Fourier phase shift
  interpolation)]{dir=" ltr"}
  +-----------------------+-----------------------+-----------------------+ |
  [**\ | [**Primary motion | \ | correction | **\_\_or | (realignment)** | NA] |
  (reference scan for realignment, image similarity metric, type of
  interpolation used, degrees-of-freedom and optimization method)]
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [**Intrasubject | NA] | registration (e.g. anatomical to
  functional)**]{dir="l tr"}
  +-----------------------+-----------------------+-----------------------+ |
  [**\ | [Directionality (e.g. | \*\***or | anatomical to | NA] | functional,
  functional session 1 to functional session 2, etc)]
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [Transformation model | NA] | (linear or nonlinear)]{dir="ltr" }
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [Degrees of | NA] | freedom]
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [Interpolation | NA] | method]
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [Image similarity | NA] | metric]
  +-----------------------+-----------------------+-----------------------+ | [\
  | **[Intersubject | __or NA] | registration (e.g. anatomical/functional to
  template)] **
  +-----------------------+-----------------------+-----------------------+ |
  [**\ | [Brain image template | ****or | space, name, modality | NA] | and
  resolution (e.g., MNI Avg152, T1 2 × 2 × 2 mm; customized sample template)]
  +-----------------------+-----------------------+-----------------------+ |
  [**\ | [Directionality (e.g. | ****or | anatomical to | NA] | functional,
  functional session 1 to functional session 2, etc)]
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [Transformation model | NA] | (linear or nonlinear)]{dir="ltr" }
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [Degrees of | NA] | freedom]
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [Interpolation | NA] | method]
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [Image similarity | NA] | metric]
  +-----------------------+-----------------------+-----------------------+ |
  [**\ | **[Smoothing]{dir="lt | \ | r"}** | \  \ | [Size and type of | \ |
  smoothing kernel | ****or | (provide | NA] | justification for size; e.g., for
  a group study, "12 mm FHWM Gaussian smoothing applied to ameliorate
  differences in intersubject localization"; for single subject fMRI "6 mm FWHM
  Gaussian smoothing used to reduce noise")]
  +-----------------------+-----------------------+-----------------------+ |
  [**or | [**Temporal | NA] | filtering** (type of filter, frequency band)]
  +-----------------------+-----------------------+-----------------------+ |
  [**Flowchart**]{dir="  ltr"} |
  +-----------------------+-----------------------+-----------------------+ | [\
  | [A flowchart can be | __or NA] | attached that depicts the order of the
  preprocessing steps for each acquisition type (anatomical and
  functional).]{dir="lt r"}
  +-----------------------+-----------------------+-----------------------+ |
  **[Code]\*\* |
  +-----------------------+-----------------------+-----------------------+ |
  [\_\_or | [Link to shared code | NA] | for preprocessing data]
  +-----------------------+-----------------------+-----------------------+
