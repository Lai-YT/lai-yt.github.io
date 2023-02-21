---
layout: post
title: "總結我寒假的學習內容與情況"
date: 2023-02-20
categories: vacation
lang: zh
ref: summarize-the-work-of-my-winter-vacation
assets: 2023-02-20-summary-of-my-winter-vacation
---

## 時間規劃

我嘗試使用 [番茄工作法](https://zh.wikipedia.org/zh-tw/%E7%95%AA%E8%8C%84%E5%B7%A5%E4%BD%9C%E6%B3%95)，以每顆 :tomato: 25 分鐘為單位，每次休息 5 分鐘，4 顆 :tomato: 後休息 15 分鐘的方式來幫助自己專心。我使用的番茄工作法工具是 [Pomodoro Tracker](https://pomodoro-tracker.com/)。
> 番茄工作法的強大之處沒這麼簡單，但我著重在專注、休息與記錄這三點上，因此不那麼嚴謹。

單天的學習情況大致上有 3 種：
- 4 ~ 5 小時，早上和下午各 5 ~ 7 顆 :tomato:（以下簡稱*整天*）
- 2 小時，只學習上午或是下午（以下簡稱*半天*）
- < 1 小時，無學習，只進行基本的打字練習

對我來說 4 ~ 5 小時的強度已經相當高了。我秉持 **休息可以提高整體效率** 這個原則，理想上每週有 5 天是整天學習，週休 2 日半天學習，並且晚上都是休息的。但因為有些日子需要出門，因此只會學習半天，並且因為專注力似乎還是有限，實際上是 4 個整天，3 個半天。
整個寒假的時長是 5 週，前 4 週算是有保持這個時間安排，最後 1 週為了避免開學後過早倦怠，我就完全休息了（看了一本書）。

![pomodoro record from 01/17/2023 to 02/16/2023]({{ "/assets/images/" | append: page.assets | append: "/pomodoro-record.jpg" | relative_url }})
> 01/23 其實有 25m

![pomodoro record from 01/17/2023 to 02/17/2023 in weeks]({{ "/assets/images/" | append: page.assets | append: "/pomodoro-record-in-weeks.jpg" | relative_url }})

---

## 學習項目

- [編譯器](#編譯器)
- [盲打](#盲打)
- [LaTeX](#latex)
- [Rust](#rust)
- [Vim](#vim)

> 在番茄工作法的時間記錄中，除了編譯器的 category 被設為 work 之外，其他都是 personal

### 編譯器

研究所要專攻的編譯器領域在大學算是完全沒有接觸，因此從這個寒假開始追趕。 \
這個項目作為主要項目使用了最多的時間（70 小時～）。我從 Stanford 的 [CS143: Compilers](https://web.stanford.edu/class/cs143/) 開始，搭配火龍書（Compilers: Principles, Techniques, and Tools, 2/e）進行學習。目前算是完成了 CS143 的 [Programming Assignment](https://github.com/Lai-YT/CS143-cool-compiler-assignments) 3，練習了基本的 *Lex* 和 *Bison* 的使用，線上課程看完了第 11 週的內容（Runtime Organization）；火龍書還在第 4 章（Syntax Analysis），大概只閱讀完了全書的 25%。預計未來的研究方向是在 Optimization（backend），是火龍書後 40% 的內容，還有些距離，希望下學期可以讀得完。

| 子項目名稱 | 完成比率 |
|:----------|:--------:|
| CS143 線上課程影片 | 11 / 18 |
| CS143 Programming Assignment | 3 / 5 |
| CS143 Writing Assignment | 0 / 4 |
| 火龍書 | 25% |

### 盲打

一直以來都不會盲打，自己在寫程式的時候常常可以感覺到撰寫速度跟不上思緒的速度 :disappointed_relieved: \
我使用 [TypingClub](https://www.typingclub.com/) 這個學習網站練習，從字母鍵到數字鍵再到符號。

![Speed, Accuracy, Coverage & Practice Time in TypingClub]({{ "/assets/images/" | append: page.assets | append: "/typing-club-speed-and-practice-time.jpg" | relative_url }})

![Accuracy, Coverage & Practice Time in weeks]({{ "/assets/images/" | append: page.assets | append: "/typing-club-accuracy-coverage-and-time-in-weeks.jpg" | relative_url }})

這個項目使用了第二多的時間（25 小時～），因為練習打字還蠻有成就感的，有時在休息時間仍會手癢練習個幾關。目前打符號的速度還相當慢（< 20 wpm），而寫程式往往需要符號，修正錯誤的速度也不夠快，因此下學期我將持續練習。我每天至少會練習 30 分鐘的盲打。

另外我也使用 [monkeytype](https://github.com/monkeytypegame/monkeytype) 這個開源的打字網站記錄自己盲打速度的變化。左側的低谷是我開始練習盲打的起點。一開始的打字速度一定會下降，但 **透過練習，你終將變得更加優秀**。

![Speed when typing English in monkeytype]({{ "/assets/images/" | append: page.assets | append: "/monkey-type-long-time-eng.jpg" | relative_url }})

![Wpm and time when typing English in monkeytype]({{ "/assets/images/" | append: page.assets | append: "/monkey-type-wpm-and-time-of-long-time-eng.jpg" | relative_url }})

### LaTeX

我真正決定入門 LaTeX 是在看到 CS143 的 Writing Assignments 都是用 LaTeX 撰寫後。喟嘆其課程之扎實。我閱讀完 [Overleaf 的 30 分鐘 LaTeX 學習引導](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)（實際上花了 3 顆 :tomato:），對於 LaTeX 的語法規則有了一定的瞭解。但想習得一個技能，練習是不可或缺的，因此下學期我將強迫自己使用 LaTeX 繳交所有的作業 :rocket:

### Rust

我從 [Rust by Example](https://doc.rust-lang.org/stable/rust-by-example/) 切入，開始瞭解 Rust。目前閱讀完了前 10 章，只知道基本的語法且仍不熟悉，距離學會使用 Rust 表達還有相當的距離。若依循學習 Python 的模式，我會寫一些 [LeetCode](https://leetcode.com/) 的 [題目](https://github.com/Lai-YT/leetcode/search?l=rust) 強化語法以及函式的使用，然後再寫個小專案以更實際地瞭解其軟體應用。

### Vim

我在學 [作業系統](https://youtube.com/playlist?list=PLS0SUwlYe8czigQPzgJTH2rJtwm0LXvDX) 和 [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/) 的時候，教授都一再強調了 Vim 的重要與強大：如果鍵盤的打字速度夠快，熟悉 Vim 的指令之後撰寫程式的速度能再更上一層樓，同時也是遠端連線時最方便的文字編輯器。 \
我只有跟著最基本的 vimtutor 做練習，距離會用 Vim 還天差地遠。因為同時學習盲打和 Vim 生產力會近乎歸零，十分難熬，因此我會於盲打順手之後再強迫自己練習 Vim。
