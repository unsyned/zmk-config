# Layouts

![corne](./cornetto.png)

![zen](./zen.png)

TODO: create layout for bluetooth le chiffre to use keymap drawer

## Versions
Every version before is "archival" and considered sub v1 I guess...

A brief history:

My introduction to layers was from the Anne Pro 2 with "magic caps". To put it shortly, it was the start of a glorious relationship. I loved having arrow keys right under my fingertips. When I got my iris, I put the "removed" symbols all on one layer with some navigation keys, and it stayed pretty unevolved like that for quite a while. 

The next evolution was a kind of renaissance for my interest in new keyboards (I had a rule for myself forbidding duplicate keyboards essentially). I love the MDA keycap profile, and an inoffensive keycap set came out that I bought the blanks for (MDA future suzuri). I thought "I touch type. Why the hell not?" The only issue was accuracy in stretching up to R1 for the numbers without the visual aid of number legends. So I tried moving numbers right under the home row, split my layers into navigation/function and number/symbol layers, and I actually ended up really liking it. In the end this was pretty much the last "hold out" until 40% keyboards were a viable option for me. And that brings us to the first 40% compatible key layouts.


Here are the "characterizing" features of each version:
1. Base qwerty layer, numrow/symbol layer + nav layer, and braces on combos
    - This version was born out of my desire to use a 5 col keyboard. It never *really* worked because io/ui rolls couldn't be worked out with timing, even with 30ms. I would also misfire esc on er on the left hand. But I wouldn't know until I tried.
2. Numpad + removal of bracket combos
    - This one involved a huge rework of my layers to fit all brackets onto their own row in the symbol layer, and moving the symbol layer down because of constant misfires (would hit numbers instead of symbols). I was intending to swap the num/shifted symbol rows, but was able to shuffle things to fit and try out a numpad
3. Addition of Colemak-DH layer
    - While massively messing up my muscle memory, I figured I would throw an alternate key layout in the mix *officially*.
4. Colemak-DH is base layer
    - I realized that without colemak on base layer, I would have to toggle back to that layer after waking my wireless keyboard every time... annoying.
5. Backspace is on left thumb. Centered around re-prioritizing 6 key functions: space, backspace, enter, esc, del, tab
    - I started thinking about backspace on base layer after a meetup, and tried it. This made more sense, as I would be backspacing more than hitting esc. The very same weekend I added key overrides to move delete off of my pinky. The thought process is that delete is kind of a modified backspace, and tab is also a sort of modified space, hence shift + space/backspace.



#### TROUBLESHOOTING
When flashing on Linux, make sure to mount the keyboard before copying the UF2.

- To pair:
```zsh
bluetoothctl
scan on # then wait for the name to pop up, and take note of the MAC address
pair <MAC address>
trust <MAC address>
```

