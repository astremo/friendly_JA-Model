# friendly_JA-Model
MT model trained using the friendly_JA Corpus attempting to make Japanese easier/more accessible to occidental people by using the Latin/English derived katakana lexicon instead of the standard Sino-Japanese lexicon

We used sonoisa t5-base-japanese (https://huggingface.co/sonoisa/t5-base-japanese) as pretrained model and the friendly_JA corpus to fine-tune the friendly_JA model.


# Examples

| input | output|
|---|---|
|最適化を応用した機械翻訳モデルは高精度だ|オプティマイゼーションを応用したマシントランスレーションモデルは高いアキュラシーだ|
|彼は架空の世界に住んでいる|彼はイマジナリー世界に住んでいる|
|新型コロナウイルスに感染してしまった|コロナウイルスにかかってしまった|
|深層学習は難しい|ディープラーニングはむずかしい|
|新たな概念を紹介する|新しいコンセプトを紹介する|
|津波の警報が流れた|ツナミのアラートが流れた|
|南海トラフの災害は震源地による|南海トラフのディザスターはエピセンターによる|
|息子は際どい内容の本を読んでしまった|子どもはセンシティブなコンテンツの本を読んでしまった|
|非現金決済に対応する|クレジットカード決済をサポートする|
|係員は会議の予定を調整している|担当の人はアジェンダを調整している|
|友人とカラオケに行く予定があったが、彼女はどうしても美術館に行きたかった|友だちとカラオケに行くスケジュールがあったが、彼女はどうしてもミュージアムに行きたかった|
|国際会議に参加しました|インターナショナルコンファレンスに参加しました|
|部長は今日の会議に参加できかねました|部長は今日のミーティングに参加できませんでした。|
|新型コロナウイルスの予防接種による心膜炎が多数報告されている|コロナウイルスのワクチンによるペリカーダイティスがレポートされている|
|私はジョジョの奇妙な冒険が好き|私はジョジョのビザールアドベンチャーが好き|
|新型コロナウイルス　オミクロン株 1人死亡 8249人感染|コロナウイルス オミクロンバリアント 1人死んだ 8249人インフェクション|
|2021年10月4日から岸田文雄は日本の総理大臣として勤めている|2021年10月4日から岸田文雄は日本のプライムミニスターとして働いている|


# Download
https://huggingface.co/astremo/friendly_JA

# License
Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
