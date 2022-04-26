# pandoc_samples

ドキュメント変換ツール[Pandoc](https://pandoc.org/)のサンプル

Pandoc は Markdown や reStructuredText などのテキストフォーマットのドキュメントを、PDF, Word, PowerPoint などのリッチなファイルに変換でき、文書作成コストをさげることができる
一方で、デザインなどを考慮して利用するにはコツも必要なので、サンプル集としてここにアップする


## -> Powerpoint


* [変換前(Markdown)](./powerpoint/sample.md)
* 変換: 標準テンプレートへの変換
  * コマンド
    * `pandoc ./powerpoint/sample.md -o ./powerpoint/sample.pptx`
  * [変換後(標準テンプレート)](./powerpoint/sample.pptx)

