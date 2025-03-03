# Spaced Repetition
[Wikipedia](https://en.wikipedia.org/wiki/Spaced_repetition)

[Two components of memory - supermemo.guru](https://supermemo.guru/wiki/Two_components_of_memory)

[Do not memorize before you understand - supermemo.guru](https://supermemo.guru/wiki/Do_not_memorize_before_you_understand)

[Martin Schneider on X: "This is Piotr Wozniak The father of computerized spaced repetition. His insights are used by millions of learners worldwide to get better grades and learn more effectively. Here are 5 of his most important insights to help you reduce study stress and "become a genius": https://t.co/aT6kuoS0AG" / X](https://x.com/Mart1nSchneider/status/1815099433291517954)
> If you're struggling to remember information, don't stress over it. Focus on optimizing your learning process instead. This means:
> - finding good encodings & understanding before you memorize
> - active recall (testing yourself)
> - effective spacing (timing of reviews)

## Algorithms
- SM (SuperMemo)
  - SM-2
- [FSRS](#free-spaced-repetition-scheduling-algorithm-fsrs)

### [Free Spaced Repetition Scheduling Algorithm (FSRS)](https://github.com/open-spaced-repetition/free-spaced-repetition-scheduler/tree/main)
[Hacker News](https://news.ycombinator.com/item?id=39002138)

Anki v23.10 (2023-10)
> The Free Spaced Repetition Scheduler (FSRS) is an alternative to Anki's legacy SuperMemo 2 (SM-2) algorithm. By more accurately determining how likely you are to forget a card, it can help you remember more material in the same amount of time. This setting is shared by all presets.

[FSRS4Anki: A modern Anki custom scheduling based on Free Spaced Repetition Scheduler algorithm](https://github.com/open-spaced-repetition/fsrs4anki/tree/main)
> 

> FSRS can adapt to almost any habit, except for one habit: pressing "Hard" instead of "Again" when you forget the information. When you press "Hard", FSRS assumes you have recalled the information correctly (though with hesitation and a lot of mental effort). If you press "Hard" when you have failed to recall the information, the intervals will be unreasonably high (for all the ratings). So, if you have this habit, please change it and use "Again" when you forget the information.

How often should I re-optimize parameters?
> Once per month should be more than enough. A more sophisticated rule is to optimize after every 2^n reviews: after 512, then after 1024, then after 2048, etc. But the "one month" rule is simpler.

最直接的感受就是 space 变长了。

[FSRS explained, part 1: What it is and how it works : r/Anki](https://www.reddit.com/r/Anki/comments/15mab3r/fsrs_explained_part_1_what_it_is_and_how_it_works/)

[Why isn't FSRS the default scheduler? - Anki / FSRS - Anki Forums](https://forums.ankiweb.net/t/why-isnt-fsrs-the-default-scheduler/40455)

[Should everyone switch to FSRS? - Anki / FSRS - Anki Forums](https://forums.ankiweb.net/t/should-everyone-switch-to-fsrs/45382)
> I’ve used V2 since 2021. And FSRS for about 2 months. My workload has decreased by 64%. In other words, 100 minutes of work now takes me 36 minutes. My retention is the same.

## Tools
- [Anki](Anki/README.md)
- GinkgoNotes
  
  [Show HN: I combined spaced repetition with emails so you can remember anything | Hacker News](https://news.ycombinator.com/item?id=42317393)
