# Language identification
In this repository there are some training pipelines and evaluation records of the models prepared and trained by Orel Daniil durng the SRP at ISSAI. <br>
There are also multiple notebooks/programs which perform the routine tasks (such as audio conversion), but they will stay behind the scenes. <br>
There are some pretrained models:
- [CLSTM](https://drive.google.com/file/d/1ampqdvugX0N5mBtaLMGLpEC94yCYRECP/view?usp=sharing)
- [LSTM with AP loss](https://drive.google.com/file/d/1d9mkFUgkH8Gj6EpAcbEdRIya34nbhBzz/view?usp=sharing)
- [GRU](https://drive.google.com/file/d/1jXR7nyfaIYtRtojkAVfXxEUOJ_xs8pxC/view?usp=sharing)
- [Simple Xvector](https://drive.google.com/file/d/1F8UIpVnlinYzxUrkK1yvNYXKhYv5yKk7/view?usp=sharing)
- [Xvector with attention](https://drive.google.com/file/d/1H9s9wYl2exDPB_X-IwMGk9IFILP7DBOq/view?usp=sharing)
- [Augmented Xvector](https://drive.google.com/file/d/1EFa_e3o4vaKAP4zUi3T_fQekBdELRBiH/view?usp=sharing)

These models were built using [python lidbox](https://github.com/py-lidbox/lidbox). The data used for training and evaluation purposes was taken from the [Vox dataset], Common Voice data and from the Kazakh Speech Corpus. <br>
A small study has shown that among these models the most precise one is the Xvector model with the attention mechanism. Also, when trained with multiple augmentations, it shows a good generalization capability
