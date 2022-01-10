# friendly_JA-Model
MT model trained using the friendly_JA Corpus attempting to make Japanese easier/more accessible to occidental people by using the Latin/English derived katakana lexicon instead of the standard Sino-Japanese lexicon

We used sonoisa t5-base-japanese (https://huggingface.co/sonoisa/t5-base-japanese) as pretrained model and the friendly_JA corpus to fine-tune the friendly_JA model.
We provide the pytorch model as well as the onnx quantized model.

We registered a 66.80 Bleu Score performed on the pytorch model.


# License
Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
