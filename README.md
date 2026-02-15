# Paper 2 Code

Dans ce projet, je lis des papiers de recherche de référence en deep learning et j'implémente les concepts décrits from scratch avec PyTorch.

L'objectif est de comprendre en profondeur les architectures fondamentales en les codant soi-même, sans utiliser les couches pré-faites des frameworks.

## Notebooks

| Notebook | Papier | Description |
|----------|--------|-------------|
| [transformer_from_scratch.ipynb](transformer_from_scratch.ipynb) | [Attention Is All You Need](https://arxiv.org/abs/1706.03762) (Vaswani et al., 2017) | Implémentation complète d'un Transformer encoder-decoder avec self-attention, positional encoding, et test sur une tâche de traduction FR→EN |
| [LoRA_from_scratch.ipynb](LoRA_from_scratch.ipynb) | [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685) (Hu et al., 2021) | Implémentation de l'adaptation low-rank pour le fine-tuning efficace de LLMs |

## Stack

- Python 3.13
- PyTorch
- Transformers (pour comparaison avec des modèles pré-entraînés)