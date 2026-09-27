# Open Wide! / Ouvre grand !

A small browser game: feed a wriggly baby with a spoon before their mood runs out.
Available in English and French (picked from your browser's language settings).

**Play:** https://fallais.github.io/openwide/

It's a single self-contained `index.html` file (HTML, CSS, vanilla JS and canvas, with sound from the Web Audio API). Open it in any browser to play offline.

## Controls
- **Mouse:** move the spoon, click to feed, click the bowl to refill.
- **Touch:** drag the spoon and lift your finger to feed. Tap the bowl to refill.
- **SPACE** or 😜: pull a funny face to make the baby laugh. Dropping food restarts its cooldown.
- **A** (or 👃 on mobile) during a sneeze: pinch the nose to stop it.
- **M:** mute. **FR/EN** button: switch language for this visit.

## Mechanics
- **Levels** are 7 bites. The longer a level takes, the harder the baby gets. Finish under par for a speed bonus.
- **Food viscosity:** soups are runny, so they drip and spill at lower spoon speeds. Compotes are thick and forgiving.
- **Airplane:** draw the shape shown in the baby's thought bubble (circle, triangle or square) with a full spoon. The baby gets curious and opens wide for longer. From level 4 the shape changes during the level.
- **Grab:** hold the spoon still near the baby too long and they grab it. Click, tap or press keys fast to win the tug-of-war, or the food ends up in their hair.
- **Burp:** every 3 bites the baby needs a burp (💨 in the top bar, plus a ×3 target on the tummy). Click the tummy (the blue onesie) 3 times quickly, or tap it on mobile. Skip it and the next sneeze is a spit-up.
- **Bad days:** some levels the baby has a cold (sneezes much more) or is teething (blows a lot more raspberries).

## Tuning
All gameplay values (baby speed, mouth timing, difficulty, meters, shape recognition, and so on) are in the `CONFIG` object at the top of the script. All text is in the `I18N` object.
