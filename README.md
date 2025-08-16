# Easy-Transformer (TransformerLens) Fork

This repository contains code based on the paper **"Interpretability in the Wild: a Circuit for Indirect Object Identification in GPT-2 Small"**. The library is designed to make mechanistic interpretability research easier and more accessible.

The original source code can be found at [https://github.com/redwoodresearch/Easy-Transformer.git](https://github.com/redwoodresearch/Easy-Transformer.git) (which has since been renamed TransformerLens).

---

### Changes in This Fork

This is a forked version of the original library, and the following key changes have been made to improve its usability:

* **Jupyter Notebook "Getting_Started.ipynb" is added**: This notebook provides a comprehensive, step-by-step guide to get started. It demonstrates how to install the library, load a pre-trained model like GPT-2, and run a core interpretability technique (an ablation experiment) with clear explanations.
* **Updated Dependencies**: Versions of certain imports have been updated to ensure compatibility with modern Python environments.
* **Added Code Comments**: Explanatory comments have been added to core files like `easy_transformer/EasyTransformer.py` to clarify complex functions and the library's internal workings.

---

### Citation

If you find this model and the original research useful for your publications, we encourage you to cite the original paper:

```bibtex
@misc{wang2022interpretability,
      title={Interpretability in the Wild: a Circuit for Indirect Object Identification in GPT-2 small}, 
      author={Kevin Wang and Alexandre Variengien and Arthur Conmy and Buck Shlegeris and Jacob Steinhardt},
      year={2022},
      eprint={2211.00593},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
