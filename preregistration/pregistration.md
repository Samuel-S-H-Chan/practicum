Study Information
Hypotheses
All else equal, saying "Kobe" when throwing improves accuracy. 

Design Plan
Study type
Experiment - A researcher randomly assigns treatments to study subjects, this includes field or lab experiments. This is also known as an intervention experiment and includes randomized controlled trials.

Blinding
For studies that involve human subjects, they will not know the treatment group to which they have been assigned.

Is there any additional blinding in this study?
No data

Study design
The experiment will be conducted indoors to minimize external disturbances such as wind or lighting variation. The subject will throw paper balls made from identical A4 sheets toward a stationary laundry basket positioned three meters away. Each throw will be made with the subject’s dominant (right) hand. A total of fifty throws will be conducted under each condition, yielding one hundred throws per subject. Two subjects will participate in the study. To manage fatigue, the subject will rest for approximately five seconds between throws, and the research assistant (RA) will collect and return the paper balls after every ten throws. 

The experiment follows a within-subject design with randomized ordering of treatment and control conditions. In the treatment condition, the RA will say the word “Kobe” at the precise moment the subject releases the paper ball. In the control condition, the RA will instead say the word “Coco,” which serves as a neutral placebo. The subject will not know which condition is being implemented in any given throw. The use of the RA, rather than the subject, to pronounce the word ensures that the subject remains blinded to treatment assignment, preserving excludability and reducing the potential for bias. 

Chan_Practicum_PAP.pdf
Randomization
No data

Sampling Plan
Existing Data
Registration prior to any human observation of the data

Explanation of existing data
No data

Data collection procedures
The experiment will be conducted indoors to minimize external disturbances such as wind or lighting variation. The subject will throw paper balls made from identical A4 sheets toward a stationary laundry basket positioned three meters away. Each throw will be made with the subject’s dominant (right) hand. A total of fifty throws will be conducted under each condition, yielding one hundred throws per subject. Two subjects will participate in the study. To manage fatigue, the subject will rest for approximately five seconds between throws, and the research assistant (RA) will collect and return the paper balls after every ten throws. 

The experiment follows a within-subject design with randomized ordering of treatment and control conditions. In the treatment condition, the RA will say the word “Kobe” at the precise moment the subject releases the paper ball. In the control condition, the RA will instead say the word “Coco,” which serves as a neutral placebo. The subject will not know which condition is being implemented in any given throw. The use of the RA, rather than the subject, to pronounce the word ensures that the subject remains blinded to treatment assignment, preserving excludability and reducing the potential for bias. 

No files selected

Sample size
The study includes two participants (subjects), each performing one hundred throws—fifty under the Kobe condition and fifty under the Coco condition—yielding a total of 200 throwing observations. Each throw constitutes one analytical unit in the dataset. Because the experiment follows a within-subject design, treatment assignment is randomized at the throw level and clustered within subjects. Standard errors in all analyses are therefore adjusted for within-subject correlation.

Sample size rationale
No data

Stopping rule
No data

Variables
Manipulated variables
No data

No files selected

Measured variables
The primary outcome variable is throwing accuracy, measured as a binary indicator equal to 1 if the paper ball lands inside the laundry basket and 0 otherwise. This measure is used to estimate the probability of a successful throw under each condition.

The key independent variable is treatment, coded as 1 for throws during which the research assistant says “Kobe” at the moment of release and 0 for throws during which the assistant says “Coco.”

No additional covariates are included in the analysis, as treatment assignment is randomized. However, each observation includes a subject identifier, used to cluster standard errors and account for the within-subject experimental design.

No files selected

Indices
No data

No files selected

Analysis Plan
Statistical models
To test the hypothesis that saying “Kobe” improves throwing accuracy, I use a logistic regression model where each throw is coded as either a hit (1) or a miss (0). The main predictor is a binary treatment variable indicating whether the research assistant said “Kobe” or “Coco.” The estimated coefficient represents how the probability of a successful throw changes when the “Kobe” treatment is applied.

Standard errors are clustered by subject to account for repeated measures within individuals. Because treatment assignment was randomized, no covariates or interaction terms are included. I also compute marginal effects to express the treatment impact in probability terms rather than log-odds.

For robustness, I compare results to a linear probability model that produces substantively identical conclusions. All analyses are conducted in R using the glm() function with a binomial link and the vcovCL() function to adjust for clustered standard errors.

No files selected

Transformations
No data

Inference criteria
No data

Data exclusion
No data

Missing data
No data

Exploratory analysis
No data

Other
Other
No data
