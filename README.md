# The Foundation Model Transparency Index

The Foundation Model Transparency Index is an ongoing initiative to comprehensively assess the transparency of foundation model developers. To learn more, please see our [website](https://crfm.stanford.edu/fmti/) and the October 2023 [paper](https://arxiv.org/abs/2310.12941).  

Foundation models like GPT-4 and Llama 3 impact millions of people. While the societal impact of these models is rising, transparency is on the decline. If this trend continues, foundation models could become just as opaque as social media platforms and other previous technologies, replicating their failure modes.

# May 2024 Foundation Model Transparency Index
For the follow-on version to the initial October 2023 [paper](https://arxiv.org/abs/2310.12941), we assess 14 foundation model developers (e.g. OpenAI, Google, Meta) on 100 indicators of transparency in relation to their flagship models (GPT-4, Gemini 1.0 Ultra API, Llama 2). 
These indicators span transparency on upstream resources (e.g. data, labor, compute), foundation models themselves (e.g. capabilities, risks, mitigations), and downstream use (e.g. distribution channels, usage policies, downstream impact). 

# December 2025 Foundation Model Transparency Index
In 2025, we update the indicators to reflect the current AI ecosystem: we add indicators to reflect new developments in foundation model development and raise the bar for several indicators to ensure that disclosures provide useful information. We score 13 companies on their transparency, including DeepSeek, Alibaba, xAI, and Midjourney who we score for the first time.

# Methodology
1. **Targets.** In 2025, we reached out to 23 major foundation model developers and requested that they prepare reports disclosing information related to our 100 transparency indicators. 7 agreed to submit these transparency reports. To maintain coverage, the FMTI team prepared reports for 6 of the remaining companies.
2. **Initial scoring.** For each developer, two researchers scored the developer's disclosures on the 100 indicators, assessing whether the developer satisfied the indicator on the basis of this information. We compared scores and resolved disagreements through discussion.
4. **Company response.** We shared the initial scores with leaders at each company, encouraging them to contest scores they disagreed with. We addressed their reviews and conducted virtual meetings with companies, finalizing scores over the course of two months.

# This repository
This repository provides all the data associated with the Index:
1. **Indicators.** We define each indicator, hierarchically organize it into a domain and subdomain, and provide references in the literature that speak to its importance.
2. **Scoring Materials.** We provide the scores on each indicator for all of the developers.
3. **Transparency Reports.** We provide a transparency report for each developer including the information it makes publicly available related to the upstream resources required to build its flagship foundation model, the model itself, and the downstream use of the model. 
4. **Visuals.** All visuals generated on the basis of our scores are provided.

The Foundation Model Transparency Index is not a common task benchmark; it is a composite index compiled by researchers at Stanford's Institute for Human-Centered AI, Princeton's Center for IT Policy, and MIT Media Lab. 
The scores assigned by the FMTI team are the only validated scores associated with the FMTI. 
All data and visuals are licensed under [CC-BY](https://creativecommons.org/share-your-work/cclicenses/) and may be re-used for any purpose with attribution. Please cite the Foundation Model Transparency Index if re-using this data, and please use the citation below if citing the work in a paper.

# Authors
Rishi Bommasani*, Kevin Klyman*, Sayash Kapoor, Shayne Longpre, Betty Xiong, Nestor Maslej, Percy Liang

## Cite as

```
@article{bommasaniklyman2024fmti,
  author       = {Bommasani, Rishi and
                  Klyman, Kevin and
                  Kapoor, Sayash and
                  Longpre, Shayne and
                  Xiong, Betty and
                  Maslej, Nestor and
                  Liang, Percy},
  title        = {The Foundation Model Transparency Index v1.1},
  month        = may,
  year         = 2024,
  url          = {https://arxiv.org/abs/2310.12941}
}
```
