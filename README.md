# Flappy Crow
Made for the Kitboga Code Jam. I only learned javascript as part of this code jam and honestly this video did like 90% of the heavy lifting, I just tweaked some stuff and added a couple of my own things in (e.g. the bird rotating, or crowtating if you will :) )

There aren't really any hidden tricks in this. There is a bug that the bird does draw over the game over window but idk why that's drawing incorrectly tbh ¯\_(ツ)_/¯ we were all there when flappy bird happened you know the drill. 

Actually. Hang on.

[does a quick google search]

oh my gosh it was twelve years ago??? ("Flappy Bird was initially released on May 24, 2013.") 

okay sorry anyway back to the code jam.

Easiest tweak is to set the threshold_score to a different number. I found getting past 5 pretty hard honestly but maybe there's some pro (crow) gamers out there who never lost their flappy bird skills, so this can let them shine. Currently set to 10 since that seems hard but definitely doable. The balance of gravity versus boost feels pretty good as it is, I played around with a few values and the current ones (gravity = 0.25 and boost_on_click = -6) feel good. 

I didn't actually mess around with the velocity_x at all, it's set to -2 (the background moves R to L at a rate of 2 pixels per frame I think), so you could probably also tweak that to make it easier/harder. There's also a current_lore_reason that I wanted to implement but just kind of didn't feel like I had a good place, so that prints to the log and could maybe be added into the captcha window (but I didn't because we're not supposed to edit that. But you could! Little easter egg for you if you read this far) 