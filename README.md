# misou
味噌荘 is misou. misou gives you some porker protocol games
using mazekoze(=dh-shuffle) technique.

インターネット雀荘　味噌荘へようこそっ！
Welcome to misou of internet gambling room !.
# after I translate Japanese to English...

味噌荘では，まぜこぜを使って，ポーカープロトコルを実現しました。
ポーカープロトコルは，暗号数学の一分野です。
ポーカープロトコルを簡単に言うと，暗号技術を使ってインターネット上でポーカーをしましょう。
ってことです。
まぜこぜの暗号数学的な説明は，簡単にですが後でします。

DHT は，馬跳びを採用しています。
馬跳びを簡単に説明すると，
自分にとってn個隣のnodeにとってn個隣のnodeを聞いて，
自分にとって2n個隣のnodeの情報を得る。
ってことです。

申し遅れました。
私は管理人の，梅濁酒（どぶろく）と申します。
以後，お見知りおきを。
何か連絡があれば，umedoblock AT gmail.com 宛にメールお願いします。

= まぜこぜの暗号数学的な簡単な説明。
まぜこぜは，DH-key exchange の発展版です。
まぜこぜは，DH-shuffle です。
というと感覚的に理解しやすいでしょうか。

DH-key exchange では，
(g^x)^y と (g^y)^x は p を法として合同。
でしたね？

まぜこぜでは，
原子根を複数(=g1...gn, n個)用意して，べき乗を複数人(4人等)で行い，
g1...gn^abcd mod p
共通な↑を得て，事前に合意した任意の順（昇順など）に並べ替えることで，
予測不可能な原子根の並びを得よう。
ってことです。
