# -How-Pick-Up-Lines-and-Personal-Scent-Influence-Relationship-Initiation-
## Analysis Overview
   This study aims to understand how pick-up lines and personal scent contribute to relationship initiation by first testing whether the attractiveness effects of personal scent are enhanced by the use of pick-up lines.
## Data Source
   The data used in this analysis was sourced from a CSV file named 'PickUpLines'
## Tools
   - SQL- Data Cleaning
   - Python- Data Analysis
## Data Preparation
   During the initial data preparation stage, I carried out the following tasks:
   - Data loading and inspection
   - Handling missing values
   - Data formatting
## Exploratory Data Analysis
   An exploratory analysis of the "Diet" dataset was carried out to answer essential questions like:
   - Are there any outliers?
   - Was normal distribution observed within each group?
   - Is there equality of variance between the groups?
## Data Analysis
   A Python script has been attached to this documentation.

## Result
   A robust heteroscedastic two-way analysis of variance (ANOVA; HC3) was conducted to examine whether the effect of androstenedione spray (spray vs. no spray) on attractiveness (receptivity) was moderated by pick-up approach (cute-direct vs. direct-direct). The analysis revealed a significant interaction between scent and pick-up approach, F(1, 190) = 8.18, p = 0.005, η² = 0.04, indicating that the effect of androstenedione spray on attractiveness depended on the pick-up approach used.

   Follow-up simple effects analyses using the Games–Howell procedure showed that, when androstenedione spray was present, participants exposed to the cute-direct pick-up approach (M = 4.04, SD = 0.57) reported significantly higher attractiveness than those exposed to the direct-direct approach (M = 3.61, SD = 0.56), t(96.35) = 4.06, p = 0.000098. The mean difference was .35, with a 95% confidence interval of [0.20, 0.65], and the effect size was large (Hedges’ g = 0.75).

   - Based on the findings above, the results suggest that relationship initiative, operationalized as perceived attractiveness or receptivity, is influenced by an interaction between verbal communication style and olfactory cues, rather than by either factor in isolation. Prior to analysis, key assumptions underlying factorial designs were evaluated. Visual inspection of residuals indicated no substantial violations of independence or linearity, while tests of homogeneity of variance revealed unequal variances across experimental conditions. In response to this violation, a heteroscedasticity-robust two-way ANOVA (HC3) was employed, ensuring that the reported effects are not artefacts of variance inequality.

     The significant interaction between pick-up approach and scent indicates that the effect of spray on relationship initiative depends on how the individual initiates social interaction. Specifically, when the spray was present, a cute-direct pick-up approach elicited significantly higher receptivity than a direct-direct approach. This suggests that scent alone does not uniformly enhance attractiveness; instead, its influence is context-dependent, amplifying the effectiveness of a more socially engaging and playful communicative style. The large effect size observed for this simple effect further underscores the practical relevance of this interaction.

     From a psychological perspective, these results imply that relationship initiation is shaped by multimodal cues, wherein chemical signals may enhance perceived attractiveness most effectively when they complement positive social behaviours. Importantly, the use of robust statistical methods and variance-insensitive follow-up tests strengthens confidence in these conclusions. Overall, the findings indicate that successful relationship initiation is not solely determined by what is said or by biological cues alone, but by the alignment of social approach and sensory signals.

## Recommendations
  - Integrate communication style with sensory cues
  - Avoid relying on scent in isolation
  - Tailor strategies to social context

