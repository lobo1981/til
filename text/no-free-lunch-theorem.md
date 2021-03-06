# ノーフリーランチ定理

この用語、たまに聞くしなんだっけ、って思い出すたびにググッているきがする。

コトバンクで調べてみると

[ノーフリーランチ定理 (コトバンク 参照:2020/11/7)](https://kotobank.jp/word/%E3%83%8E%E3%83%BC%E3%83%95%E3%83%AA%E3%83%BC%E3%83%A9%E3%83%B3%E3%83%81%E5%AE%9A%E7%90%86-1834256)

```
あらゆるコスト関数に対する探索量の平均は，どの探索アルゴリズムも同じである，と結論する定理。
```

とある。文章だけだと少しつかみづらいかもしれない。
参考として、Wikipediaにどのような状態を表すのかグラフとして描画されていたのでそちらを見ると良い。

[ノーフリーランチ定理 (Wikipedia日本語版 参照:2020/11/7)](https://ja.wikipedia.org/wiki/%E3%83%8E%E3%83%BC%E3%83%95%E3%83%AA%E3%83%BC%E3%83%A9%E3%83%B3%E3%83%81%E5%AE%9A%E7%90%86#:~:text=%E3%83%8E%E3%83%BC%E3%83%95%E3%83%AA%E3%83%BC%E3%83%A9%E3%83%B3%E3%83%81%E5%AE%9A%E7%90%86%EF%BC%88%E3%83%8E%E3%83%BC%E3%83%95%E3%83%AA%E3%83%BC%E3%83%A9%E3%83%B3%E3%83%81%E3%81%A6%E3%81%84%E3%82%8A%E3%80%81%20no-free-lunch%20theorem%20%E3%80%81%20NFLT%20%EF%BC%89%E3%81%AF%E3%80%81%E7%89%A9%E7%90%86%E5%AD%A6%E8%80%85%20David,H.%20Wolpert%20%E3%81%A8%20William%20G.%20Macready%20%E3%81%8C%E7%94%9F%E3%81%BF%E5%87%BA%E3%81%97%E3%81%9F%E7%B5%84%E5%90%88%E3%81%9B%E6%9C%80%E9%81%A9%E5%8C%96%E3%81%AE%E9%A0%98%E5%9F%9F%E3%81%AE%E5%AE%9A%E7%90%86%E3%81%A7%E3%81%82%E3%82%8B%E3%80%82%E3%81%9D%E3%81%AE%E5%AE%9A%E7%BE%A9%E3%81%AF%E4%BB%A5%E4%B8%8B%E3%81%AE%E3%82%88%E3%81%86%E3%81%AB%E3%81%AA%E3%82%8B%E3%80%82)

![NoFreeLunch](https://user-images.githubusercontent.com/59351307/98434217-14ad6280-2111-11eb-908b-b975c3afeff0.gif)

グラフ作成者: [Melan](https://ja.wikipedia.org/wiki/%E5%88%A9%E7%94%A8%E8%80%85:Melan)

```
この定理は「あらゆる問題で性能の良い汎用最適化戦略は理論上不可能であり、ある戦略が他の戦略より性能がよいのは、
現に解こうとしている特定の問題に対して特殊化（専門化）されている場合のみである」ということを立証している
```

専門性に特化したアルゴリズムは専門外の問題であると不得意となる、という意味。
