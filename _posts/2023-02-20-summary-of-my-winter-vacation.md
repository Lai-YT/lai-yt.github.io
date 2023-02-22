---
layout: post
title: "Summarize the Learning Contents & Progress in my Winter Vacation"
date: 2023-02-20
categories: vacation
lang: en
ref: summary-of-my-winter-vacation
assets: 2023-02-20-summary-of-my-winter-vacation
---

## Time Plan

I tried to use the [Pomodoro Technique](https://en.wikipedia.org/wiki/Pomodoro_Technique) to help me on focusing. Each Pomodoro (:tomato:) lasts 25 minutes with a successive short break (5 minutes). After the third :tomato:, take a long break (15 minutes). The tool I used is [Pomodoro Tracker](https://pomodoro-tracker.com/).
> The power of the Pomodoro Technique is much more than what I've experienced. I cared only about focusing, taking rest and recording, so not practicing it strictly.

The time spent in a single day is one of the followings:
- 4 ~ 5 hours. 5 ~ 7 :tomato: each in the morning and the afternoon. (simply, the whole day)
- 2 hours. Only learning in the morning or the afternoon. (simply, half-day)
- < 1 hour. No learning. Only practicing typing.

To me, learning 4 ~ 5 hours a day is intensive enough. I believe **taking rest improves overall efficiency**. There should be 5 whole days and 2 half-days per week and no learning in all the evenings, but sometimes I had to go outdoors and my concentration is more limited than that, so there were only 4 whole days.

The winter vacation lasted for 5 weeks. I kept the above time plan in the beginning 4 weeks and had entirely been resting (I read a book) in the last week to prevent myself from burning out early in the coming semester. In summary, the time that I'd been focusing on did increase.

![pomodoro record from 01/17/2023 to 02/16/2023]({{ "/assets/images/" | append: page.assets | append: "/pomodoro-record.jpg" | relative_url }})
> actually 25m in 01/23

![pomodoro record from 01/17/2023 to 02/17/2023 in weeks]({{ "/assets/images/" | append: page.assets | append: "/pomodoro-record-in-weeks.jpg" | relative_url }})

---

## Learning Topics

- [Compiler](#compiler)
- [Blind Typing](#blind-typing)
- [LaTeX](#latex)
- [Rust](#rust)
- [Vim](#vim)

> In my Pomodoro record, the category of Compiler is set to work. Others are set to personal.

### Compiler

I'll be studying and researching Compilers in graduate school but haven't been learning them yet, so I started chasing since this winter vacation.
As the main topic, I spent the most time on it (70 hours ~). I started from the [CS143: Compilers](https://web.stanford.edu/class/cs143/) in Stanford along with the Red Dragon Book (*Compilers: Principles, Techniques, and Tools, 2/e*). For the [Programming Assignments](https://github.com/Lai-YT/CS143-cool-compiler-assignments), I finished up to PA3, which covered the basic usage of *Lex* and *Bison*; for the video lectures, I finished up to week 11 (*Runtime Organization*) and for the Red Dragon Book, I'm in chapter 4 (*Syntax Analysis*), approximately only 25% of the book. I shall be having research on the *Optimization* phase (backend), which is the last 40%, still a bit further. Hope I can finish them in the coming semester.

| Sub-topics | Completion Rate |
|:----------|:--------:|
| CS143 video Lecture | 11 / 18 |
| CS143 Programming Assignment | 3 / 5 |
| CS143 Writing Assignment | 0 / 4 |
| Red Dragon Book | 25% |

### Blind Typing

I used to type with my eyes looking at the keyboard and often felt my typing behind my thought :disappointed_relieved: \
I learn blind typing on [TypingClub](https://www.typingclub.com/). From alphabets to numbers, and then symbols.

![Speed, Accuracy, Coverage & Practice Time in TypingClub]({{ "/assets/images/" | append: page.assets | append: "/typing-club-speed-and-practice-time.jpg" | relative_url }})

![Accuracy, Coverage & Practice Time in weeks]({{ "/assets/images/" | append: page.assets | append: "/typing-club-accuracy-coverage-and-time-in-weeks.jpg" | relative_url }})

This topic takes the second most time (25 hours ~). Because practicing typing somehow brings me a sense of accomplishment, I sometimes played some more stages in my rest time. My current typing speed on symbols is pretty slow (< 20 wpm) but usually need to type many symbols when programming. Also, my error-correcting speed is quite slow. so I'll keep practicing blind typing in the coming semester. At least 30 minutes a day.

Moreover, I practice on [monkeytype](https://github.com/monkeytypegame/monkeytype), an open-source typing website, to track the progress of my typing speed. The rock bottom on the left is when I start practicing blind typing. The typing speed will decrease at the beginning but **with practice, you'll become better eventually**.

![Speed when typing English in monkeytype]({{ "/assets/images/" | append: page.assets | append: "/monkey-type-long-time-eng.jpg" | relative_url }})

![Wpm and time when typing English in monkeytype]({{ "/assets/images/" | append: page.assets | append: "/monkey-type-wpm-and-time-of-long-time-eng.jpg" | relative_url }})

### LaTeX

The moment that I make up my mind to learn LaTeX is when I found that the Writing Assignments in CS143 has to be handed out in LaTeX. I'm astonished by how solid the course is. I read [Learn LaTeX in 30 minutes](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes) at Overleaf (though I spent 3 :tomato:). I now understand the basic syntax of LaTeX, but to master a skill, practicing is indispensable. So I'll force myself to hand out all of the assignments in LaTeX in the coming semester :rocket:

### Rust

I begin the learning of Rust with [Rust by Example](https://doc.rust-lang.org/stable/rust-by-example/). I finished reading the first 10 chapters, knowing only the basic syntax and not familiar with it, far from being able to express my thought with Rust. Following the way I learned Python, I will be solving some [LeetCode](https://leetcode.com/) [problems](https://github.com/Lai-YT/leetcode/search?l=rust) to improve my acknowledgment of syntax and the usage of libraries. After that, write a small project to feel how Rust plays its role in software applications.

### Vim

When learning [The Operating System](https://youtube.com/playlist?list=PLS0SUwlYe8czigQPzgJTH2rJtwm0LXvDX) and [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/), professor emphasized the importance and power of Vim: if you type fast, Vim enables you to type in the speed of your thoughts, furthermore, it's your best text editor when connecting to remote machines. \
I only practiced through the *vimtutor*, so there's a long way further before using Vim as a productive tool. Since practicing blind typing and Vim at the same time would make me nearly unproductive, which is too tough, I'll push myself on practicing Vim after I can type at a certain speed.
