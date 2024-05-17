# Football Manager 2008 kimz tactics

Back in Football Manager 2008, a number of exploit tactics were released.  Over the years I've been experimenting with one in particular - one by the author kimz.  [Here](https://community.sigames.com/forums/topic/13906-kimz-802-tactic-with-no-tweak-at-all-the-best-tactic-for-fm08-rate-it/) is one of the threads that describes it.

Over the years, however, link rot has set in, and the tactics have since been lost.  This repository aims to not just rehost them, but also talk about them, and also show the improvements I've made to them.

## What are the kimz tactics?

kimz tactics are a set of exploit tactics for Football Manager 2008.  This match engine was, bluntly, not very good, especially by modern Football Manager standards.  It also had a number of exploits that could be employed, which kimz tactics exploit.

The tactic is not quite as effective as, say, [Championship Manager 01/02's Diablo tactic](https://fm-base.co.uk/threads/diablo-tactic-what-did-it-look-like.132821/), nor the [three-striker tactic in Football Manager 2012](https://www.fmscout.com/a-fm12-tactic-4-1-2-3-engine-exploiter-by-hazaa22299.html), but it is still effective nevertheless.

kimz tactics all have the same pattern:

- They involve what would be called inverted full-backs in modern-day Football Manager.  In Football Manager 2008, however, they are extremely strong, because the match engine is usually not able to exploit the space left behind, assuming you're not far weaker than your opponent.
- With arrows, they can pull centre-backs out of position, for an attacking midfielder or other striker to slip into the space left behind for a free key pass into space.
- A corner exploit is used as a cherry on the cake, turning saves into further easy shots on goal.

kimz tactics are also very offensive.  Despite this, they are quite good at not conceding goals - although they are achieved by bludgeoning the opposition into submission until they stop attacking.  This tactic can and will concede goals if you are far inferior, or have the wrong players.

kimz released several tactics.  Over the years, I believe that not all of them are necessary, nor do I have all of them available.  Here's a list of the versions they released:

- 1.0
- 1.1
- 2.0
- 2.1
- 2.2
- 3.0
- 4.0

I only have 3.0 and 4.0 left.  But after testing on older PC, I'm not convinced anything else is actually needed.  As will be described below, 4.0 (or variants thereof) should be your default, with 3.0 against three-at-the-back with no wing-backs.

## What changes were applied to the original kimz tactics?

The main change I've made to the tactics is that the full-backs have a new instruction: Shoot on sight often.  This is because the full-backs, which are really extremely offensive inverted wing-backs, are often in really good positions outside of the box.  If they shoot, they can score a decent number of goals if they have good Long Shots, or win several corners through deflections.

If this option is turned off, the full-backs will still be effective, although they're more likely to play more key passes instead.  Your mileage may vary on which one is more effective.  I find corners are by far the most effective ways to generate goals with the corner exploit.  It also feels far more fun to have players that play like Roberto Carlos, shooting from distance when they cut inside.

I have also made some small tweaks to the order of positions.  kimz's original tactics had them at random positions on the match stats screen, which I found annoying.

## Which tactic should you use?

I recommend the following flowchart:

1. The default strategy you should use is "[kimz](#kimz)".  This is a tactic based on the original kimz 4.0 tactic.
2. "[kimz, left bias](#kimz-left-bias)" should be used when the opponent is able to press deep and your full-backs and central midfielder are unable to pass the ball forwards with ease.  This is a small tweak to the first tactic, where the central midfielder is positioned to the left, and the left full-back performs fewer forward runs, and runs with the ball often.  This encourages the left-back to dribble into more forward positions to find players.  This is a riskier tactic since your left-back can be tackled more-easily and lose the ball.
3. "[kimz, full press](#kimz-full-press)" is an extremely aggressive version of "kims, left bias".  This tactic applies the same left-back instructions to the right-back, and several players are told to run with the ball more often.  The full-backs are now wing-backs, and the wide forwards (FL/FR) no longer track back.  You should only apply this tactic against extremely weak sides, or when you're chasing a game, or when you are up against the dreaded 3-3-2-1-1 AI tactic (details below).
4. "[kimz, full press (vs. no forwards)](#kimz-full-press-vs-no-forwards)" is an even more aggressive variation, and more of a meme than anything.  As the name suggests, employ this when the enemy is down to 9 men and has no forwards.  The wing-backs are now attacking midfielders that track back to wing-back positions, ensuring they start up the pitch instead.  You end up with an 8v8 matchup on their side of the pitch, with your two centre-backs in reserve.  It's technically possible to become even more aggressive, by promoting one of your centre-backs to a defensive midfielder with a backwards-arrow (and run frequently), but I find (albeit with a very small sample size) this creates more issues because this defensive midfielder will hold the ball very often and be tempted to dribble wide.  The key to this tactic, however, is the centre of the pitch.

Collectively, I will refer to these as the **standard** tactics.

There is one more tactic, specific to 3 at the back, with no wing-backs:

5. "[kimz, vs 3](#kimz-vs-3)" is based on the original kimz 3.0 tactic.  This tactic has a very specific purpose - against tactics that have 3 at the back, and no wing-backs.  The wingers in this tactic will exploit the spaces on the wings ruthlessly.  "kimz" might still work fine against such a formation, but I find "kimz, vs. 3" tends to work better on average.

## How does each player play?  What attributes do they need?

### Goalkeeper

You do not need a world-class goalkeeper, but you do need a competent one.  Because of the way this tactic works, there's serious diminishing returns with world-class goalkeepers, although they're certainly useful against the best teams in the world.  In other words - a good goalkeeper is a good investment, but don't sweat over a world-class one.

### Centre-backs

Football Manager 2008 has one major flaw - players with good Jumping are relatively rare.  Including centre-backs.  They're not impossible to find, but quite rare.  This tactic demands centre-backs that are excellent, and have high Jumping, Strength, Pace and Acceleration.  The right centre-back is also the corner exploit target, and should have high Heading and Bravery.  You absolutely need good centre-backs in this tactic, because it basically defends with two players.

I find this tactic works best with a left-footer on the left centre-back position, and a right-footer on the right.  However, given it's hard enough to find good centre-backs in this game, I would not worry too much about it if you can't find a good left-footed centre-back.

### Full-backs

This is where the magic actually happens.  These players are actually the most important players in this tactic from a creative perspective.  With the right players, these players are capable of creating double-digit key passes in certain games, and get double-digit goals and assists over a season.

The ideal player for this tactic, however, is unlikely to be generated as a full-back (or a wing-back).  These players often lack the Long Shots, and less-often the Passing to handle the role.  These players will often lack the Jumping to be converted to centre-backs, too.  Such players are sadly useless to this tactic, and should be eventually loaned-out and sold.

The ideal full-back is basically a cross between a central midfielder and winger, who can pass, shoot, (optionally) cross and create - but also not be bad defensively.  The player must also have decent Pace and Acceleration, although it's not critical to be world-class (just not poor - at least double-digits).

The easiest way to find such a player is to find a central midfielder and retrain them to become a full-back.  The central midfielder doesn't have to be only a central midfielder (or defensive midfielder).  In fact, players that can play, say, MC, ML, AML, AMC can be retrained too, if not better than a normal MC, because they can cross.

A secondary source, if rarer, is to find a player who can play all the way down the flank (e.g. DL, WBL, ML and optionally AML).  These players, because they're partly-wingers, are more likely to have the Passing, Long Shots and Crossing, as well as the defensive capability.  You'll know you have a good player in this category if they could in theory be retrained to MC, and be decent.

Crossing is a nice-to-have, but not critical.  Crossing is hit-or-miss in Football Manager 2008, but the full-backs will often get into positions to cross and be tempted to do so.

I find this works best if you have a left-footer on at left-back, and right-footer at right-back.  Swapping feet does seem to create more shots, but defensively, it's a bit more suspect since they're weak on the outside.

I can't stress this enough - the full-backs are where the real magic happens in this tactic.  You should try to get world-class players here.  High Passing, Long Shots, Creativity, Decisions are a must.  Good Tackling, Positioning, Pace, Acceleration, Crossing are secondary, but still not-insignificant nice-to-haves.

### Central midfielder

In the "kimz, vs. 3" tactic, this refers to the central AMC that drops deep.

The most defensive central midfielder in both tactics is probably the least important player in the tactic.  Their main job is to recycle the ball from the defence to the full-backs, strikers or wingers.  So as long as they have good Passing, Creativity and Decisions, and aren't totally slow, they'll work here.

### Wingers

These are the FL and FR positions in all the tactics.

The wingers are really wide forwards.  They will get a decent number of opportunities on goal, but their primary goal is to take the ball deep into the opponent's half and win corners.  To that end, they must have good Dribbling, Pace and Acceleration.

For the "kimz, vs. 3" tactic, there's also one more important requirement: High Aggression.  Players with high Aggression will attack space more aggressively, as you might expect.  The difference between a winger with single-digit Aggression and a winger with one close to 20 is night-and-day.  Thus you may want to have two options per wing - a wide forward who can score goals, and a pacy winger with high Aggression whose main goal is to drive forward.

### Attacking midfielder

This is the central AMC in the standard tactics.  This does not apply to to the attacking midfielders in the "kimz, vs. 3" tactic.

This player is the second-most important player in the tactic, from an offensive perspective.  Like the Diablo tactic, this is actually your main goalscorer.  But these players frequently make lots of key passes and produce assists too.  So this player needs to be excellent, as well as the ultimate striker as well as the ultimate attacking midfielder, except maybe for Crossing, and except (on occasion) physical attributes.

What modern-day Football Manager refers to as an enganche also works here.  These are players, often old, that have little-to-no physical ability left, so their technical and mental attributes are through the roof.  These players are incredible here too.  You can even train such players - if you find a young attacking midfielder is lacking in physical ability to begin with, consider putting them on a training schedule with no physical training.  Acceleration and Pace do add an extra dimension to this player, but without it, they might simply make more passes.

There is a somewhat-hidden factor this position.  It's possible to get world-class players that for whatever reason simply don't deliver, like there's a random factor that boosts or reduces their effectiveness.  It is hard to explain, but as a rule of thumb, in a world-class squad:

- This player should either be your top goalscorer, or second behind your corner exploit receiver.
- This player should score at last 40 goals in all competitions as a bare minimum.  Aspirationally, however, you should be looking for 50 goals.  Even higher is possible - I've hit 70 on one player.
- If you find a player is scoring at a rate of above 1 goal per game, consider persisting with them.
- If you have a world-class player that isn't hitting above 1 goal per game, consider "demoting" them to striker.

Players in this role should be at least accomplished at both AMC and ST.  These players are, of course, possible to be played as a striker in any of these formations as you see fit.

### Strikers

This refers to the central strikers in the standard tactics, and the two wide AMCs and the striker in the "kimz, vs. 3" tactic.

The strikers are actually more creative than the attacking midfielder described in the section above.  These players will usually have roughly-equal numbers of goals and assists, and in a world-class squad, they should average 1 goal or assist per game.  If they are corner takers, this will skew it further.

These players should be similar to the attacking midfielders described above, except that they need physical attributes (although you can get away with playing an enganche-like player there to some extent), and they should also be decent at crossing (they get into wide areas at times).  High Jumping can be hard to find, but I think you need at least one striker that is not completely useless at it, since a decent number of crosses do occur in these tactics.

Players in this role should be at least accomplished at both AMC and ST.

In the "kimz, vs. 3" tactic, you **need** a targetman up front to get the most out of the tactic, with high Jumping, Heading, Bravery and Finishing.  You can get away without it, but you'll be relying more on corners.  A mediocre backup targetman (who can still finish) can do wonders in this tactic.

## The tactics

### All tactics

Your best centre-back (aerially) should be on the right.  Feel free to swap set-piece if you find, say, an appropriate striker who is better and are willing to use them.  Note that you must **swap** - the corner exploit setup needs this exact configuration of set-piece roles.

#### Set pieces

- Corners should be inswingers (left-footed on right corner and vice versa).
- For some reason, Football Manager often generates centre-backs with really high Corners attributes.  Don't use them.  Get a lesser corner-taker and let your centre-backs stay in the box.  The left-sided centre-back occasionally chips in with goals as well.
- Free-kicks should be outswingers, although quite frankly, these are awful in Football Manager 2008, often overshooting like mad.  This is why I prefer outswingers, because at least it's likely to go out for a throw-in instead of a goal kick.
- For some reason, Technique isn't always as important as Free Kicks when it comes to the free kick set piece.  I'm not sure what the exact relation is, but high Technique can be useful for scoring direct free kicks.  High Technique + High Free Kicks is a good rule of thumb either way.

### kimz

<img src="https://raw.githubusercontent.com/x42bn6/fm08-kimz-tactics/main/kimz.png" alt="kimz" />

This tactic should be the default.  It will work for most games, although some of the other tactics may work better than others in some cases.

Consider switching if:

- The opponent is weaker, but still able to press high-up to the extent that your full-backs and central midfielder struggle to pass forwards - switch to "[kimz, left bias](#kimz-left-bias)"
  - In commentary-only view, you will see this manifest if your back 5 have large numbers of passes, but your front 5 are starved
- The opponent switches to 3-3-2-1-1 - switch to "[kimz, full press](#kimz-full-press)"
- The opponent is playing a back three without wing-backs - switch to "[kimz, vs. 3](#kimz-vs-3)"

### kimz, left bias

<img src="https://raw.githubusercontent.com/x42bn6/fm08-kimz-tactics/main/kimz%20left%20bias.png" alt="kimz, left bias" />

This tactic should be employed if you're struggling to get the ball to your front 5.  This is caused when the opponent presses high.

This tactic uses your left-back as a dribbling outlet to move the ball forward.  The central midfielder is also skewed to the left.  The idea is that the full-back should get further-forwards than they usually do, but they start from a deeper position.

For the left-back, this is risky, because if they are intercepted, they can attack the flank.  Thankfully, in Football Manager 2008, this is not that strong, unless there is genuinely no full-back or wing-back (hence why "kimz, vs. 3" is good in this scenario), but it is still riskier than "kimz".

Why did I choose the left-back?  This is because Football Manager 2008 has a 4-4-2 tactic where the right-sided central midfielder drops back.  If you play against this formation, this means that your left-back will have a little more space to dribble, and is less likely to be intercepted.  If you wish, you can flip the full-back instructions and move the central midfielder to the right - just note that I've found this to be less efficient on average.

Consider switching if:

- This feels too aggressive - consider going back to "kimz", or if you ran into problems getting the ball forwards previously, consider switching to "[kimz, vs. 3](#kimz-vs-3)", and move back to this tactic if you score a few goals (in the hope that the opposition stops pressing as much)
- You think you can turn the screw even further - switch to "[kimz, full press](#kimz-full-press)"
- You're still struggling to pass the ball forwards - you need better players.  But consider "[kimz, vs. 3](#kimz-vs-3)" - this overloads the midfield differently, so you might get more joy with the AI marking different players.

### kimz, full press

<img src="https://raw.githubusercontent.com/x42bn6/fm08-kimz-tactics/main/kimz%20full%20press.png" alt="kimz, full press" />

This should only be employed against the dreaded 3-3-2-1-1 tactic, or if you are massively superior, or if you really need a goal.

The 3-3-2-1-1 is the AI's most defensive tactic, and it is a nightmare to crack, even for this tactic.  If you use "kimz" or "kimz, left bias" against this, you'll find that it is defensively overkill.  When the opponent has the ball, they will attack with 2 (AMC and ST), but you will have 7 players back (back 4, MC, FL, and FR).  You simply don't need this.  You do need players to move the ball forwards from full-back, but you don't need the wingers to track back.  Thus this tactic forgoes most defensive activity.  With the wingers no longer tracking back, they effectively mark the opposition full-backs, reducing the number of safe defensive passing options for the opposition.  With the full-backs being converted to wing-backs, this means they start higher-up the pitch.  Players also run with the ball more often, as there's going to be acres of space.

The left bias aspect is also employed if you want to use this against a weaker side using a 4-4-2 for similar reasons to "kimz, left bias".  Against the 3-3-2-1-1, it makes little difference.

You can downgrade to less-extreme variants if you wish, but I personally take the view that if you choose this formation and want to switch back, you shouldn't have switched to this formation to begin with.  Once you have the opponent in the 3-3-2-1-1, you should suffocate them.  You might still concede the odd goal over the top, but by-and-large, if you switch to this formation, you should have already won.  The only exception is if you're chasing the game, and you succeed in scoring the winner - in which case, switching to "kimz" or "kimz, left bias" works fine.

### kimz, full press (vs. no forwards)

<img src="https://raw.githubusercontent.com/x42bn6/fm08-kimz-tactics/main/kimz%20full%20press%20vs%20no%20forwards.png" alt="kimz, full press (vs. no forwards)" />

This is an extreme version where the wing-backs in "kimz, full press" are flipped into attacking midfielders that track back to wing-back, rather than wing-backs that run forwards to attacking midfield.  This is should be only employed if the opponent is down to 9 men and has no strikers.  In this case, even "kimz, full press" is defensively overkill (the opponent attacks with 0 players, and you defend with 4).

Despite being defensively overkill, however, "kimz, full press" does not compress so many players into the centre of the pitch, so it might actually create more goals.  I've left this tactic ("kimz, full press (vs. no forwards)") uploaded just in case you need to truly overload an opponent.

I still recommend two centre-backs because the AI sometimes plays 4-4-0, and a pacy winger can sometimes cause you some grief in a 1v1 situation.  Nevertheless, it is technically possible to make this even more aggressive, with one centre-back, promoting the other centre-back to defensive midfield (skew right, backwards arrow to centre-back), with always running with the ball.  I do think this is sub-optimal, however, because this player ends up with the ball a lot, and might be tempted to whip crosses in, but it makes little sense when the opponent is defending deep.

### kimz, vs. 3

<img src="https://raw.githubusercontent.com/x42bn6/fm08-kimz-tactics/main/kimz%20vs%203.png" alt="kimz, vs. 3" />

This is not an extreme version of "kimz".  It is a different variation that should only be employed when the opponent has a back three, no full-backs, and no wing-backs (e.g. 3-4-3 with ML and MR).

This tactic works best when the wingers have high Pace, Acceleration and Aggression; and when the striker has high Jumping and Heading.  The two wide AMCs should still be considered strikers, but like all such players in these tactics, the two roles are largely-interchangeable.

This tactic has an extra attacking pattern.  What sometimes happens is that one of the wide centre-backs may attempt to mark or close down one of the wide AMCs, allowing a key pass to be threaded into the space vacated for the central striker to run on to.  For this reason, it can occasionally be useful if the other kimz tactics don't seem to work, as it might encourage different defensive movement from the AI.
