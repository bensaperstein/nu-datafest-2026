# Better Follow-Up, More Connected Care
### ASA DataFest 2026 · Northwestern University · Team Byte Me

**🏆 People's Choice Award — among 20+ competing teams**

Over 48 hours, our five-person team explored how patient engagement, access barriers, and coordination across departments relate to healthcare journeys. We brought the findings together into a focused story: helping patients stay connected to care takes both easier follow-up and better communication across their care team.

[View our final presentation](https://drive.google.com/file/d/1d7GsmdoV1GePqBKSjf_gvAK0NtxrNmsJ/view) · [Read the project notes](docs/approach-and-findings.md) · [Team and AI contributions](docs/contributions.md)

## The competition

ASA DataFest is a collaborative data analysis competition. At Northwestern's 2026 event, our team worked with a real-world healthcare challenge from **Stormont Vail Health**, a Kansas health system. The challenge asked participants to look beyond isolated appointments and understand patients' journeys through care.

Our question was:

> What changes to care processes could improve patient experience and measurable health outcomes?

We focused on follow-up care and care coordination, particularly for patients with type 2 diabetes. This repository presents our final competition story; it does not extend or rerun the original analysis.

## Our approach

We broke the broad question into smaller, connected questions:

| Area | What we examined |
| --- | --- |
| Regular care | Visit frequency and its relationship with emergency visits |
| Patient engagement | MyChart use and follow-up attendance, including differences by age |
| Access barriers | Transportation barriers and engagement with follow-up care |
| Care coordination | Department fragmentation and emergency visits among patients with type 2 diabetes |

The team used exploratory analysis, visualizations, and a logistic-regression analysis of follow-up engagement. Ben's care-fragmentation work examined distinct departments visited per patient alongside encounter and emergency-visit counts, using Python/pandas and Seaborn/Matplotlib visualizations.

## Findings and recommendations

Our final presentation highlighted three connected observations:

- **Follow-up engagement:** MyChart users showed higher follow-up engagement; the patterns varied by age.
- **Access barriers:** Transportation barriers helped identify groups facing particular challenges staying connected to care.
- **Department fragmentation:** The team observed a relationship between care spread across departments and emergency visits in type 2 diabetes care.

We recommended making MyChart registration part of discharge, following up with activation reminders, and establishing a consistent point of contact to support communication across a patient's care team.

These are **observational findings and proposed changes**, not evidence that MyChart or fragmentation caused the outcomes. The competition did not establish implementation, reduced costs, or improved clinical outcomes.

## Result

**Team Byte Me won the People's Choice Award at Northwestern ASA DataFest 2026.** Our final presentation combined the analysis with an accessible narrative and concrete recommendations. This was a shared team achievement.

## Team

**Zara Ahmar · Samuel Bowen · Ben Saperstein · Ashley Dong · Fiona Zhou**

Thank you to our mentor **Cara Chang**, the organizers, judges, fellow competitors, and Northwestern's Department of Statistics and Data Science.

Ben contributed to the care-fragmentation analysis, the team's approach and key findings, and the presentation of care-coordination recommendations. Other analyses and the overall award belong to the team; see [contribution notes](docs/contributions.md).

## Materials and data

The [final presentation](https://drive.google.com/file/d/1d7GsmdoV1GePqBKSjf_gvAK0NtxrNmsJ/view) is the primary competition artifact. The written notes here summarize that presentation rather than report new results.

**No raw patient data, patient-level extracts, or data-bearing notebooks are included.** The competition data are proprietary. This is a portfolio record of the final work, not a reproducible data release.

The competition's May 2 source embargo has ended; its restrictions on the underlying data remain. Final-product sharing does not grant permission to reuse the data. See [data and interpretation notes](docs/approach-and-findings.md#data-and-interpretation).

## AI assistance

The team documented Microsoft Copilot assistance with understanding relationships between files, data-processing code, debugging, and more sophisticated visualizations. Some processing code was AI-generated. The disclosure describes sparing use for the big-picture approach and takeaways. See [the fuller summary](docs/contributions.md#ai-assistance).

This repository's explanatory text was assembled after the competition with AI assistance from the final presentation and existing project records. No new analysis was performed.
