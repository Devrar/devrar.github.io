---
date: 2025-12-09T14:09:33+01:00
# description: ""
# image: ""
lastmod: 2025-12-09
showTableOfContents: false
tags: ["chess",]
title: "Civitanova Chess Tournament Round 5"
type: "post"
---

Welcome back! Yesterday I was too tired to write this post, so I'm writing it now. This is the final game of the tournament and I'm at 3/4 playing on second board and if I manage to win I guarantee a third place! However, fortunately this didn't affect my way to play, I was only focused on playing well.

## The game

For the final game I'm Black against Mauro Di Mantino, a 1984-rated player - and also born in 1984, how cool is that? Here it is the game:

{{< chess-viewer height="280px" flip="true">}}
[Event "2025/12/06 - Civitanova: Turno 5"]
[Date "2025.12.08"]
[Result "0-1"]
[Variant "Standard"]
[ECO "A15"]
[Opening "English Opening: Anglo-Indian Defense"]
[StudyName "2025/12/06 - Civitanova"]
[ChapterName "Turno 5"]
[UTCDate "2025.12.08"]
[UTCTime "23:23:46"]

1. c4 Nf6 2. g3 g6 3. Bg2 Bg7 4. Nc3 O-O 5. e4 d6 6. Nge2 c5 7. O-O Nc6 8. d3 a6 9. h3 Rb8 10. Be3 b5 11. Qd2 bxc4 12. dxc4 Ne5 13. b3 Bxh3 14. f4 (14. Bxh3 Nf3+ 15. Kh1 Nxd2) 14... Bxg2 15. fxe5 Nxe4 (15... Bxf1 16. exf6 Bxf6 17. Rxf1) 16. Nxe4 Bxe4 17. Nc3 Ba8 18. exd6 Qxd6 19. Qxd6 exd6 20. Rac1 Rfe8 21. Bf2 Re5 22. Rfd1 Rh5 23. Nd5 Bxd5 24. cxd5 Rb4 25. Rc4 Re5 26. Kf1 Re4 27. Rc2 Be5 28. Kg2 c4 29. Kf3 cxb3 30. axb3 Rxb3+ 31. Kg2 (31. Kxe4 f5#) 31... Rb2 32. Rc8+ Kg7 33. Rd3 Ree2 34. Rf3 Bd4 0-1

{{< /chess-viewer >}}

### The opening

He played **1. c4**, the English Opening, against which I don't have a clear response. Most of the time I just play the King's Indian moves and pray that I have a reasonable position. Even though it is a naive approach, it's not completely wrong.

So this time I did the same thing until we reached {{< go-to-move id="ct-1" move="17" >}}move 8{{</ go-to-move >}}. I don't know if it is too soon to talk about a middlegame, but I don't care so let's go to the next section.

### The middlegame

I implemented a standard plan in the King's Indian with **c5**: pushing **a6**, then **b5** and trying to attack on the queenside. My opponent didn't put any resistance to that and let me push on **b5**, while building a battery with queen and bishop.

Now it is time for a philosophical question: is there luck in chess? I hope that this game will convince you that yes, sometimes luck is an important component of a game. Indeed look at {{< go-to-move id="ct-1" move="23" >}}this position{{</ go-to-move >}}. Here I thought for a while and eventually I found a very nice tactical shot that gives me an advantage: **11. ... bxc4 12. dxc4 Ne5** attacking **c4** and if White defends with **12. b3** then **12. ... Bxh3!**, thanks to the tactic **13. Bxh3 Nf3+** forking King and Queen.

I played it and everything went on well until he played **13. f4!**. I didn't see that move and now I'm in trouble: if I just follow the line **14... Bxg2 15. fxe5 Bxf1 16. exf6 Bxf6 17. Rxf1** we end up {{< go-to-move id="ct-1" move="42" >}}here{{</ go-to-move >}} where I have a rook for two pieces and he is well positioned to attack me on the kingside.

But here is where luck comes in! Even though I ended up in a line I didn't consider at all, there is a move that saves me and gives me a clear two-pawn advantage: **14... Bxg2 15. fxe5 Nxe4! 16. Nxe4 Bxe4** and I'm safe.

At this point I need to keep calm and convert my advantage without allowing too much counterplay. I managed to exchange queens quickly with **17. Nc3 Ba8 18. exd6 Qxd6 19. Qxd6 exd6** and now we get into the endgame.

### The endgame

The main thing I didn't like in my position was the backward pawn on **d6**, which is very weak and an easy target for his rooks. Thus I was looking for a way to force his knight on **d5** and exchange it for my light-square bishop, closing the file pointing at my weak pawn.

I'm quite happy with the plan I pulled out to do this, because it worked very well: **20. ... Rfe8 21. Bf2 Re5 22. Rfd1 Rh5** and {{< go-to-move id="ct-1" move="56" >}}now{{</ go-to-move >}} White is forced to close the diagonal with **23. Nd5**, otherwise the attack on **h1** is too strong. And after **23. ... Bxd5  24. cxd5** my pawn on **d6** is well covered and I don't have to worry about it anymore.

After this problem was solved, I was quite confident I could convert the game. I managed to consolidate my position and at the {{< go-to-move id="ct-1" move="68" >}}right moment{{</ go-to-move >}} I pushed on **c4** to liquidate his queenside pawns, thanks to a pretty tactic after **29. Kf3 cxb3 30. axb3 Rxb3**: {{< go-to-move id="ct-1" move="72" >}}here{{</ go-to-move >}} my rook on **e4** is hanging, but if **31. Kxe4** then **31. ... f5#** is checkmate! I even tried the secret technique "look desperate and hope your opponent falls into it", but it didn't work.

*Funny story: when I was a kid I managed to make this technique work and play a Legal's Mate on the board! [Explanation video if you don't know what that is](https://www.youtube.com/shorts/6Vm5q2xurtY)*

Anyway, after a few moves I pinned his bishop and he resigned as there was nothing more to play for.


## Nothing else to say

This time no big surprises from the engine, my analysis was good apparently. Indeed without **15. ... Nxe4!**, my lucky move, White is slightly better.

One thing I'm very proud of is that the plan with **Rfe8, Re5, Rh5** to force **Nd5** was the best one! After that the position is completely winning and I converted it correctly.

## Conclusion

With this win I finished in third place! I'm really happy about this tournament, I think I played well and I was always very focused. The only thing I regret is that **Rxe3** blunder on the King's Indian game, but apart from that I'm satisfied with my play.

Moreover I'm very happy I wrote a post for each game, sharing my thoughts and feelings has been really helpful. So, if you managed to read through all of these, thank you ❤️