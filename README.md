### 🔍Measuring the psychological restorative quality of urban spaces: A Vision Language Model-based method
> **Abstract:** Well-designed urban environments crucially mitigate stress and enhance mental well-being through their restorative qualities. However, subjective surveys lack spatial scalability, while objective machine learning often fails to capture the complexity of human perceptual experiences. To address this gap, this study proposes a hybrid framework based on Vision Language Models (VLMs) and human experiences to assess the restorative quality of urban spaces. Using Shenzhen, China as a case study, we gathered subjective and objective knowledge from PRS-11 surveys and ChatGPT-4 descriptions of 566 street view images, incorporating this into VLM prompts via the Contrastive Language-Image Pretraining (CLIP) model. Through prompt engineering, the VLM evaluated 2,224 additional images, with semantic networks analyzing the decision-making process. Results demonstrate that: 1) our method significantly outperformed Random Forest, with an R² increase of 0.535 attributed to prior knowledge fusion; 2) restorative quality exhibits spatial heterogeneity, clustering in developed district near park and coastal zones; and 3) semantic network analysis further revealed the decision rationales of VLMs across different restorative dimensions, providing design guidelines for low restorative quality spaces. This research offers a novel methodology for assessing restorative quality of urban spaces, providing practical tools for sustainable development and human mental well-being.
>
> **Keywords:** Visual language model; Restorative quality; Urban spaces; Street view images; Attention Restoration Theory

<img height="750" alt="image" src="https://github.com/user-attachments/assets/1b1dd412-c436-40a6-987c-9228c07e143d" />

### 📌Data Information
> 1. Code and data preparation
> - The main code of this study `main_code.ipynb`
> - Prior knowledge preparation `image_text_pairs.csv` and `clip_embeddings.npy`

> 2. Human-labeled groud-truth
> - The human-labeled data from the online survey for result validation `ground_truth.csv`
> - The human-labeled data from the online survey for model training `ground_truth_train.csv`
> - The human-labeled data from the online survey for model testing `ground_truth_test.csv`

> 3. Evaluation results
> - Evaluation result across different VLMs `vlm_evaluation.csv`
> - Evaluation result of Claude-3.7-sonnet model `vlm_evaluation_claude.csv`
> - Prediction result across Shenzhen city based on VLMs `vlm_evaluation_final.csv`

> 4. other data
> - map of Shenzhen city `shenzhen.json`
