Moreover, its application is not restricted to facial affective analysis.
Its versatility has the potential to extend to various facial tasks.
It is welcome for you to explore the potential of MAE-Face and share your findings with us (through issues or [contact us](#contact)).

## Getting Started

To use MAE-Face, clone this repository and install the required dependencies:
- [PyTorch](https://pytorch.org/)
- [timm](https://timm.fast.ai/)

To use the pre-trained MAE-Face model, download the `.pth` files from the [Releases](https://github.com/FuxiVirtualHuman/MAE-Face/releases) section.
Use `models_vit.py` to create the model, and load the pre-trained weights from the `.pth` files.
You can refer to `example.py`, which shows a simple example about how to load the pre-trained model.

For more details, please refer to the orignial [MAE](https://github.com/facebookresearch/mae) repository.
For example, use `main_finetune.py` to fine-tune MAE-Face on your own dataset, or use `main_pretrain.py` for further pre-training.



## Contact

[Bowen Ma](mailto:sanma.kote@gmail.com)
