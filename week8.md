# week 8

___

Project Time!
___
So I've been working on my project for the past two weeks and it's almost done. I have a kids song called brother john starting the song and then I remixed it into two different beats which I still need to fix the flow of how one goes to the other.
```define :play_my_stuff do
  2.times do
    sample :drum_heavy_kick
    sample :loop_safari
    
    sample :elec_hollow_kick
    sleep 0.25
    play 38
    sleep 0.25
    use_synth :beep
    play 50
    sleep 0.25
    use_synth :beep
    play 57
    sleep 0.25
    sample :sn_dub
    sleep 1
  end
```
Above is a code snipet of one of the beats i have. It basically runs twice and keeps a beat of three piano keys that over lap with the safari loop and a heavy drum.

 ___
 

### Takeaways
====================
- A takeaway I have from working on this project is to not get discouraged when you cant find the beats. They'll come but it just takes a lot of tinkering.

### Challenges
====================

One challenge is probably getting the beats situated in the right spots. What I mean is which beat would sound good when the transition is needed.

