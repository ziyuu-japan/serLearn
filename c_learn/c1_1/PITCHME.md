### 1-1 Cプログラミング基本のキ

とは言っても僕(古田)もよく分かってない

マイクロマウスに必要な機能を実装する程度のC言語は必要、、、

---
### 参考図書

<img src="assets/c_learn/c1_1/meikai.png" width=30%>
[amazonリンク](https://www.amazon.co.jp/%E6%96%B0%E7%89%88-%E6%98%8E%E8%A7%A3C%E8%A8%80%E8%AA%9E-%E5%85%A5%E9%96%80%E7%B7%A8-%E6%9F%B4%E7%94%B0%E6%9C%9B%E6%B4%8B/dp/4797327928/ref=sr_1_20?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&keywords=%E6%98%8E%E8%A7%A3C%E8%A8%80%E8%AA%9E&qid=1576245256&sr=8-20)

高校のときに一周しただけだけど、C言語の基本の文法はこれでOK
ポインタとかよくわからねー

---
### 環境

---
### 例題

```C
/*
  整数15と37の和を表示する
*/
#include <stdio.h>

int main(void)
{
  printf("%d", 15 * 37);
  return 0;
}
```

@snap[south span-100]
@[1-3](コメント)
@[4](インクルード(今はとりあえず書くだけ))
@[6-10](メイン関数(まだ書くだけ))
@snapend
