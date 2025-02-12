# Anthro-Chinese-AI-News

This repository contains code to compute anthropomorphic scores for Chinese news articles, focusing on AI discourse. This work is part of a Master's Thesis at National Taiwan University's Graduate Institute of Journalism, College of Social Sciences.

This code is introduced in the following thesis:

**Anthropomorphic Analysis of Chinese News: A Case Study on Artificial Intelligence Discourse**
---
Author:       Chong Jing  
Affiliation:  Graduate Institute of Journalism,
              College of Social Sciences,
              National Taiwan University  
Advisor:      Ji-Lung Hsieh, Ph.D.


## Abstract
With the rapid advancement of artificial intelligence (AI), news media often employ anthropomorphic representations to help the public better understand this emerging technology. However, excessive attribution of human characteristics to AI can lead to misconceptions about its actual capabilities and affect public perception of technological risks and ethical issues. This study examines AI-related news from ETtoday, a major Taiwanese digital news platform, to explore anthropomorphism in AI reporting.  

Applying the AnthroScore framework, developed by Stanford’s NLP Group, this study introduces three key modifications for Chinese-language analysis: (1) a two-step prediction method to enhance contextual understanding, (2) an adapted pronoun list including "他" (he), "她" (she), and "它" (it), and (3) a threshold-based filtering mechanism for improved reliability.  

Analyzing AI-related news articles published between 2016 and 2024, this study finds: (1) a significant increase in AI anthropomorphism over time, (2) higher anthropomorphism in entertainment, society, and sports news, and (3) ChatGPT-related articles showing greater anthropomorphism than general AI reports, indicating conversational AI elicits stronger human-like descriptions.  

This study contributes by adapting AnthroScore for Chinese, offering insights for cross-linguistic research. It also highlights Taiwan’s media tendency to anthropomorphize AI, underscoring the need for responsible journalism to prevent public misinterpretation.

## Key Adaptations

*   **Two-Pass Prediction:** We leverage full contextual information for improved accuracy in Chinese.
*   **Modified Pronoun Lists:** Pronoun lists have been tailored to the nuances of the Chinese language.
*   **Threshold Filtering:** A filtering step is implemented to refine the results and focus on stronger instances of anthropomorphism.

## Setup
