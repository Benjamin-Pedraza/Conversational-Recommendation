The use of large language models (LLMs) for
conversational recommendation tasks has gained
significant relevance in recent years. However,
their performance heavily depends on the quality and structure of the datasets used for training. Conversely, it is increasingly critical to ensure that these models are reliable and capable of
producing accurate and trustworthy content. To
quantify the extent of these challenges in Conversational Recommender Systems (CRS), we (i)
evaluate the effectiveness of PEARL and ReDial
datasets, specifically designed to enhance recommendation systems, and (ii) propose a methodology for estimating the uncertainty of these models. Using the LLaMA 3, Qwen, and DeepSeek
models, we conducted controlled fine-tuning on
both datasets and evaluated their performance using metrics such as BLEU, ROUGE, BERTScore,
and Recall. In addition, we estimated both the
aleatoric and epistemic uncertainty of these models. Our results show that PEARL facilitates the
generation of more coherent, relevant, and useraligned responses, consistently outperforming ReDial across most evaluation metrics. Although
ReDial demonstrated superior performance in Recall@1, PEARL proved to be a more robust and
effective dataset for training LLMs in conversational recommendation tasks. Uncertainty analysis reveals complementary strengths: DeepSeek is
the most self-consistent but least confident, Qwen2 is the most confident yet slightly less stable, and
LLaMA-3 offers the widest range of suggestions
with mid-level confidence.
