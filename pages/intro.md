# AtCoder アカウントの作成

- AtCoder のアカウントを作りましょう
  - atcoder.jp

---

# AtCoder アカウントの作成

- atcoder.jp にアクセス
- 右上の「新規登録」から登録
  
<img src="/atcoder-ss.png" alt="" height="600" width="600"/>

---

# AtCoder アカウントの作成

- ユーザ名: 本名でなくても良い(本名でないほうが良いかも)
- メールアドレス: 自分のメアド　学校のやつは使えない
- 所属: なんでも良い　麻布のパー研なら「APCC」

+ 「個人情報の取り扱いについて確認しました」にチェックして「新規登録」

---

# コードテストを使ってみよう

- https://atcoder.jp/contests/APG4b/custom_test
- 言語: `C++ (GCC 9.2.1)`
- ソースコード:
  ```cpp
  #include <bits/stdc++.h>
  using namespace std;
  
  int main() {
      cout << "Hello,World!" << endl;
  }
  ```

---

# コードテストを使ってみよう

- 実行して、「標準出力」の欄が実行結果
- こうなれば成功:
  <img src="/atcoder-codetest.png" height="600" width="600">

---

# AtCoder のレーティング

- AtCoder は競プロのコンテストサイト
- 毎週末のコンテストには 3000~10000 人が参加する

+ コンテストの結果に基づいて、「レート」がつく
  - ゲームのランクシステムみたいなもん
  - レート ≒ 実力

---

# AtCoder のレーティング

- レートの値に基づいて「色」が割り当てられている

<div id="rate-table">

| レート       | 色                              | 相対的な位置  | 強さ                        |
|-----------|--------------------------------|---------|---------------------------|
| 0~400     | <div color="#777777"> 灰 </div> | 上位 100% | 参加するだけでなれる                |
| 400~800   | <div color="#774400"> 茶 </div> | 上位 35%  | 学生なら優秀                    |
| 800~1200  | <div color="#007700"> 緑 </div> | 上位 20%  | エンジニアとしてかなり優秀             |
| 1200~1600 | <div color="#00AAAA"> 水 </div> | 上位 10%  | 半数以上のIT企業でアルゴリズム能力がカンストする |
| 1600~2000 | <div color="#0000FF"> 青 </div> | 上位 5%   | ほとんどのIT企業でアルゴリズム能力がカンストする |
| 2000~2400 | <div color="#AAAA00"> 黄 </div> | 上位 2%   | アルゴリズムの研究職・研究開発で重宝されるレベル  |
| 2400~2800 | <div color="#FF7700"> 橙 </div> | 上位 0.6% | やばい                       |
| 2800~     | <div color="#FF0000"> 赤 </div> | 上位 0.2% | 世界大会レベル                   |

</div>

<style>

.slidev-layout table {
  margin-top: 12px;
  font-size: 18px;
}

</style>


---

# AtCoder のレーティング

- 各世代の国内トップレベル

+ 中 1: 茶〜緑
+ 中 2: 水〜青
+ 中 3: 青〜黄
+ 高 1: 黄〜橙
+ 高 2: 橙〜赤

---

# AtCoder のレーティング

- ちなみに、AtCoder のレートはコンテスト参加回数が 15 回以下ぐらいの間はマイナスの補正が付き、低くなる

+ モチベーションを保ってたくさん出よう

---

# AtCoder のコンテスト

- ABC (AtCoder Beginner Contest): 初心者〜中級者向け
- ARC (AtCoder Regular Contest): 中級者向け
- AGC (AtCoder Grand Contest): 中級者〜上級者向け

+ しばらくは ABC に出よう

---

# AtCoder Problems

- AtCoder の問題がまとまっていて、過去問を解いて練習するのにとても便利

+ 詳しくは: https://ntk-ta01.hatenablog.com/entry/2020/04/15/001405

---

# それ以外のコンテスト

- 情報オリンピック(JOI): 中高生向けの最も権威がある大会
  - 中１で出るのはむずかしい
  - 世界大会(IOI)の代表選考
- PGBattle: 賞金付きチーム戦
- パソコン甲子園(PCK): 高校生向けチーム戦
