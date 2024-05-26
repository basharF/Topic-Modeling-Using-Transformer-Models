# Topic-Modeling-Using-Transformer-Models

## About this repo
In this analysis, I conduct Topic Modeling on a collection of scientific publications from the Deggendorf Institute of Technology's publication database. The objective is to group similar documents together and identify the active research areas within the database. The documents are encoded using the encoder component of the model TinyLlama-1.1B-Chat-v1.0 (https://arxiv.org/abs/2401.02385), which is a small chat model that adopts the architecture of Llama2.

## Instructions
- To successfully load and run the model, you need sufficient RAM memory and preferably a GPU, or you can use Google Colab.
- Please ensure that the following libraries are installed: torch, transformers, keybert, langdetect, tqdm, matplotlib, sklearn, nltk, and umap-learn. If you encounter the error "No module X found," simply install the missing module.

## References
@misc{zhang2024tinyllama,
      title={TinyLlama: An Open-Source Small Language Model}, 
      author={Peiyuan Zhang and Guangtao Zeng and Tianduo Wang and Wei Lu},
      year={2024},
      eprint={2401.02385},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
