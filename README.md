# sb2md

scrapbox to markdown

## Usage

```console
$ cat input.txt
例
#意味

[https://dictionary.goo.ne.jp/word/%E4%BE%8B_%28%E3%82%8C%E3%81%84%29/ 例（れい）の意味 - goo国語辞書] から
 名
  1. 以前からのやり方。しきたり。ならわし。慣習。「長年の―にならう」
  2. 過去または現在の事実で、典拠・標準とするに足る事柄。「古今に―を見ない」
  3. 他を説明するために、同類の中から引いて示す事柄。「―を挙げて説明する」「その―に漏れない」
  4. いつものとおりであること。「―によって話が大きい」
 副
  いつも。つねづね。
  >「―ある所にはなくて」〈枕・二八〉
$ cat input.txt | npx @hogashi/sb2md@latest
例
[#意味](意味)

[例（れい）の意味 - goo国語辞書](https://dictionary.goo.ne.jp/word/%E4%BE%8B_%28%E3%82%8C%E3%81%84%29/) から
- 名
  - 1. 以前からのやり方。しきたり。ならわし。慣習。「長年の―にならう」
  - 2. 過去または現在の事実で、典拠・標準とするに足る事柄。「古今に―を見ない」
  - 3. 他を説明するために、同類の中から引いて示す事柄。「―を挙げて説明する」「その―に漏れない」
  - 4. いつものとおりであること。「―によって話が大きい」
- 副
  - いつも。つねづね。
  - > 「―ある所にはなくて」〈枕・二八〉
```
