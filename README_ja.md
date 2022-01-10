# friendly_JA-モデル

漢語をカタカナ語に変換することを目的にfriendly_JAコーパスを用いて制作した機械翻訳モデルです。

We used sonoisa t5-base-japanese (https://huggingface.co/sonoisa/t5-base-japanese) as pretrained model and the friendly_JA corpus to fine-tune the friendly_JA model.
We provide the pytorch model as well as the onnx quantized model.

We registered a 66.80 Bleu Score performed on the pytorch model.

プリトレインドモデルとしてsonoisa t5-base-japanese (https://huggingface.co/sonoisa/t5-base-japanese)を使用し、ファインチューニングとしてfriendly_JAコーパスを使用しました。
pytorchモデルとonnx量子化モデルを提供しています。

pytorchモデルでは、66.80のBleuスコアを獲得しました。



# ライセンス
Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
