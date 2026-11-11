# Approach and findings

[Back to the project overview](../README.md)

## Starting with patient journeys

The competition challenge asked teams to understand how people move through a healthcare system over time. A single encounter can show what happened at one appointment; a journey asks what happened before and afterward, including whether follow-up occurred and how care moved between departments.

Our team narrowed this broad problem to engagement, access, and coordination. We used the final presentation to connect those topics to practical recommendations.

## Analysis summarized in the final presentation

### Regular care and emergency visits

We compared regular visit frequency with emergency-visit patterns. The presentation showed lower emergency-visit percentages in groups with more regular checkups. This motivated attention to continuity and routine follow-up.

This comparison does not establish that increasing checkups would cause fewer emergency visits. Patient characteristics, disease severity, and other differences can affect both.

### MyChart engagement and follow-up

The team compared follow-up engagement between MyChart users and nonusers and presented a logistic-regression analysis. The final slides also broke out patterns by age and transportation barriers.

The presentation used language such as “increases” and “more likely.” In this portfolio summary, we describe these as **associations**: the analysis did not randomly assign portal use, establish a causal effect, or demonstrate the results of an intervention. A regression odds ratio should not be interpreted as a probability multiplier.

### Transportation barriers

The team examined whether access barriers coincided with lower engagement and whether MyChart-related follow-up patterns differed across those groups. This connected a digital-engagement recommendation to the practical difficulty of reaching care.

Portal access alone does not resolve transportation barriers. Outreach and coordination remain relevant.

### Department fragmentation

Ben's focus was care fragmentation among patients with type 2 diabetes. The work considered the number of distinct departments a patient visited, total encounters, and emergency-visit counts.

Python/pandas aggregation and Seaborn/Matplotlib visualizations supported comparisons between department fragmentation and emergency care. The final story argued for stronger coordination and continuity across a patient's care team.

More departments can also reflect appropriate multidisciplinary care or greater illness severity. Encounter volume creates more opportunities to visit multiple departments. The analysis therefore supports a question for further investigation, not a conclusion that fewer departments would improve care.

## Recommendations presented to stakeholders

1. Include MyChart registration in discharge processes.
2. Use calls and texts to remind patients to finish activation.
3. Establish a consistent point of contact to support communication with the care team.

These were proposed actions. We did not establish that the health system implemented them or measure resulting clinical or financial improvements.

## Competition outcome

Team Byte Me received the **People's Choice Award** at Northwestern ASA DataFest 2026, among 20+ teams. The award recognizes the team project; it is not a causal-validation result or a claim to a different competition prize.

## Data and interpretation

- The analysis was exploratory and completed within a 48-hour competition.
- Patient journeys can begin before or continue after the observation window.
- Observational comparisons can reflect selection, illness severity, encounter frequency, and other confounders.
- The original data remain proprietary. This repository contains no patient-level records or new data-derived outputs.
- The competition permits displaying final products such as the slide deck on team members' websites. The deck is linked here as the primary final artifact.
- This write-up preserves the project as completed. It is not a new model, reanalysis, or claim of independently reproduced results.

## Primary artifact

[Team Byte Me — final competition presentation](https://drive.google.com/file/d/1d7GsmdoV1GePqBKSjf_gvAK0NtxrNmsJ/view)
