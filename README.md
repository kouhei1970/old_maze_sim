# old_maze_sim
14年前ぐらいに作った迷路探索シミュレーター

Windows用です。
たぶんXpか７で作ったとおもいますが１０でも動くようです。

クローンしてmazesim.exeを実行

```
git clone https://github.com/kouhei1970/old_maze_sim.git
cd ole_maze_sim
mazesim.exe
```

ロードボタンを押して適当な迷路ファイルを読み込んで遊んでください。
自分で迷路も作って試せます。
たまに変なデータ入っていて解けなくバグります。

斜め探索を実現するのにグラフ理論に基づいて迷路データ構築したり、ダイクストラ法で最短求めたりして遊んでました。
