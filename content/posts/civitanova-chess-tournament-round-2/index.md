---
date: 2025-12-07T11:48:08+01:00
# description: ""
# image: ""
lastmod: 2025-12-07
showTableOfContents: false
tags: ["chess"]
title: "Civitanova Chess Tournament Round 2"
type: "post"
---

Welcome back! Already here for round 2? This morning it was a quick game, so I should manage to publish this before the third round.

## The game

This time I had the white pieces against Corrado Luberti, a player at his very first tournament! I talked to him a little bit after the game and he confessed he doesn't really like thinking too much at every move, but he wanted to give it a try anyway. Honestly I also wasn't really in the mood to spend too much time, since today it is my brother's birthday - 🥳🥳 - and we will go out for lunch - oh no, I still have only 20 minutes to write this post 😱.

Anyway, as usual, you can see the whole game down here and then I will make the analysis step by step. This time I've already scrolled it with the engine together with my opponent, but I will try to give you my honest thoughts during the game and integrate it with Stockfish's evaluation.

{{< chess-viewer height="280px" >}}
[Event "2025/12/06 - Civitanova: Turno 2"]
[Date "2025.12.07"]
[Result "1-0"]
[Variant "Standard"]
[ECO "B12"]
[Opening "Caro-Kann Defense: Maróczy Variation"]
[StudyName "2025/12/06 - Civitanova"]
[ChapterName "Turno 2"]
[UTCDate "2025.12.07"]
[UTCTime "10:53:16"]

1. e4 c6 2. d4 d5 3. f3 Nf6 4. e5 Nfd7 5. Bd3 c5 6. c3 Nc6 7. Ne2 Qb6 8. Bc2 e6 9. O-O Be7 (9... cxd4 10. cxd4 Ndxe5) 10. Kh1 O-O 11. f4 cxd4 12. cxd4 Nb4 13. Bb3 f6 14. Nbc3 Nb8 15. f5 fxe5 16. dxe5 Bd7 17. Nd4 Bc5 (17... N8c6 18. Nxe6 Bxe6 19. fxe6 Rxf1+ 20. Qxf1 Rf8 21. Qd1 Nxe5) 18. fxe6 Bxd4 19. Rxf8+ Kxf8 20. Qf1+ Kg8 21. Qf7+ Kh8 22. Qf8# 1-0

{{< /chess-viewer >}}

### The opening

I was hoping for a Caro-Kann, since against it I always play the fantasy variation, which for inexperienced players is very dangerous - remember, I was aiming for a quick game. But at {{< go-to-move id="ct-1" move="8" >}}move 3{{</ go-to-move >}} he played **Nf6** and once again I was out of theory very soon. It's true I've seen it many times online, but I've never studied this move so I don't know exactly what to play. After a while I thought that playing **4. e5**, entering a french structure and just enjoying my space advantage couldn't be a bad move - *the engine approves*.

For a while I also considered going **e6**, for example a {{< go-to-move id="ct-1" move="14" >}}move 6{{</ go-to-move >}}, to provoke **fxe6** and play against his weak **e**-pawn, but it felt wrong - *the engine agrees with this too*.

So the opening went well until {{< go-to-move id="ct-1" move="19" >}}move 9{{</ go-to-move >}}. As soon as I played it I saw it was a blunder, because after **9... cxd4 10. cxd4 Ndxe5** black gains a clean pawn. The only thing I could do was implementing the good old strategy "look away and whistle" - illustrative gif below.

![](monkey-d-luffy-whistle.gif)

It worked like a charm, my opponent played **9. ... Be7**, I went **10. Kh1** and the game went on.

### The middlegame

My idea was to push the **f** pawn, opening up his king and mating him - very clear plan and very optimistic. But it kinda worked.

After **11. f4 cxd4 12. cxd4 Nb4 13. Bb3** my opponent pushed {{< go-to-move id="ct-1" move="32" >}}**f6**{{</ go-to-move >}}. Even though it is a standard plan in these structures, in this exact position it felt a bit risky for him: my bishop on **b3** is pointing at his king and my pawn is ready to strike with **f5**. But it felt too soon to go **f5** so I first went for **Nc3** developing a piece - *the engine more or less agrees with that*.

But, after **14. ... Nb8**, **f5** was calling and I played it without thinking too much - like the whole game in the end. It is actually very strong, since at this point the problems on the **a2 - g8** diagonal are too big to handle and black is too undeveloped.

After **15. ... fxe5 16. dxe5 Bd7** I went for **17. Nd4**, to increase the pressure on **e6** and bringing another piece into the attack - *the engine does not agree*. Apparently this spoils a big share of the advantage after **17. ... Nc6**. The biggest problem is that I was preparing to play **18. Nxe6 Bxe6 19. fxe6 Rxf1+ 20. Qxf1 Rf8 21. Qd1 Nxe5** {{< go-to-move id="ct-1" move="50" >}}after which{{</ go-to-move >}} Black is almost winning!

But luckily we didn't go into any of these variations, since my opponent played **17. ... Bc5** and now **18. fxe6** is winning, especially after **18. ... Bxd4 19. Rxf8+ Kxf8 20. Qf1+ Kg8 21. Qf7+ Kh8 22. Qf8#**.

## Conclusion

Not the cleanest game, but it's understandable once you consider that my opponent is used to short-time chess and I wanted to finish early to go to lunch. When we talked after the game we also discussed about long-time chess and how top-level players are pushing for shorter time controls.

Is long-time chess dying? Will there be only short-time tournaments at some point? I don't think so, the complexity of the game is so high that there will always be people willing to spend hours and hours for a single game.

Now sorry but I have to go to lunch, see you this evening for round 3!