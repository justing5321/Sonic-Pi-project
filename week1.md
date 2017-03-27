# Week 1 vlog:

___

* Welcome to my first week vlog. My project is going to be about Sonic Pi.
<br>
* Basically Sonic Pi is an open sourse program that allows people like me and you to use code to create music.
* We'll start with the actual program below
 <img src="http://cdn.liliputing.com/wp-content/uploads/2016/02/sonic-pi.jpg">
This is just an example of the platform you'll be using most of your time.
### First starting
When I started I wondered why the platform used numbers as sounds. Later on in the examples they told me that the numbers are like a key on a piano.

C 
D
E
F
G
A
B
<br>
60
62
64
65
67
69
71
<br>
<br>
 Looks a little messy but those numbers above corrospond with the letter.
 This is probably this most helpful thing to know because once you get to remebering the Music Notes to MIDI Note Values, it'll be easier to make beats.
  * When creating beats you would _play_ ( to play your MIDI notes) and _Sleep_ (Which gives a break after a input time)
  * Creating loops is quite simple as well 
  ```use_synth :fm
2.times do
  play 60
  sleep 0.5
  play 67
  sleep 0.5
end

 * This code snipet above ^ would run the loop 2 times and after that it will stop.
 

