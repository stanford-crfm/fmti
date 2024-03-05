# The Foundation Model Transparency Index

The Foundation Model Transparency Index is an ongoing initiative to comprehensively assess the transparency of foundation model developers. To learn more, please see our [website](https://crfm.stanford.edu/fmti/) and [paper](https://arxiv.org/abs/2310.12941).  

Foundation models like GPT-4 and Llama 2 impact millions of people. While the societal impact of these models is rising, transparency is on the decline. If this trend continues, foundation models could become just as opaque as social media platforms and other previous technologies, replicating their failure modes.

# 2023 Foundation Model Transparency Index
The inaugural iteration of the Index defines 100 indicators that span transparency on upstream resources (e.g. data, labor, compute), foundation models themselves (e.g. capabilities, risks, mitigations), and downstream use (e.g. distribution channels, usage policies, downstream impact). 
10 major foundation model developers (e.g. OpenAI, Google, Meta) are assessed for their transparency in relation to their flagship models (GPT-4, PaLM 2, Llama 2).

# Methodology
1. **Targets.** We selected 10 major foundation model developers based on their influence, heterogeneity, and status as established companies. We assessed these companies on the basis of their most salient and capable foundation model.
2. **Information gathering.** We systematically gathered information made publicly available by the developer as of September 15, 2023. The exact search protocol is available in this repository.
3. **Initial scoring.** For each developer, two researchers scored the 100 indicators, assessing whether the developer satisfied the indicator on the basis of public information. We compared scores and resolved disagreements through discussion.
4. **Company response.** We shared the initial scores with leaders at each company, encouraging them to contest scores they disagreed with. We addressed their reviews, finalizing scores along with justifications and sources. The scores, justifications, and sources are available in this repository.

# This repository
This repository provides all the data associated with the Index:
1. **Indicators.** We define each indicator, hierarchically organize it into a domain and subdomain, and provide references in the literature that speak to its importance.
2. **Search Protocol.** We define the precise search protocol we execute to identify public information on each indicator.
3. **Scoring Materials.** We provide the scores, textual justifications for those scores, and specific sources of information for all of the developers.
4. **Visuals.** All visuals generated on the basis of our scores are provided.
All data and visuals are licensed under [CC-BY](https://creativecommons.org/share-your-work/cclicenses/) and may be re-used for any purpose with attribution. Please cite the Foundation Model Transparency Index if re-using this data, and please use the citation below if citing the work in a paper.

# Authors
Rishi Bommasani*, Kevin Klyman*, Shayne Longpre, Sayash Kapoor, Nestor Maslej, Betty Xiong, Daniel Zhang, Percy Liang

## Cite as

```
@article{bommasani2023fmti,
  author       = {Bommasani, Rishi and
                  Klyman, Kevin and
                  Longpre, Shayne and
                  Kapoor, Sayash and
                  Maslej, Nestor and
                  Xiong, Betty and
                  Zhang, Daniel and
                  Liang, Percy},
  title        = {The Foundation Model Transparency Index},
  month        = oct,
  year         = 2023,
  url          = {https://arxiv.org/abs/2310.12941}
}
```
