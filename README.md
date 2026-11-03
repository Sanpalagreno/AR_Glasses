# AR_Glasses
2026-11-02
Today I made the repo. Then I calculated the power draw of my ESP32s and the screen. That meant I had to find bigger batteries. 380mah drone batteries, to be specific. Then I made the first edition of my BOM.csv for the glasses themself.

<img width="398" height="190" alt="image" src="https://github.com/user-attachments/assets/2a70b37a-e6f9-4dde-92af-140589ed5b4d" />


2026-10-31
I spent this time doing research on the different methods to actually get the image onto the lens. I found two; the first is a projector that displays on a specially carved lens to capture the light.

<img width="168" height="157" alt="image" src="https://github.com/user-attachments/assets/e6f8b7b4-2d87-45fb-8365-3c42c4ad523e" />

I did not do that; the second is with a micro OLED or normal OLED that is refocused with a lens and then reflected into my right eye.

<img width="131" height="149" alt="image" src="https://github.com/user-attachments/assets/a13c9fce-9386-4ae7-886b-4cc95ffaab3b" />


I also made a list of features I want it to have and sorted them based on whether they need a new part or an AI agent to use them. Hidden display

Clock, date, battery
Tap detection(on the arms of the glasses)
Wear detection(to auto turn off when not on face)
Live captions(
Ring controller
Head-up-tilt dashboard(dashboard only appears when looking up)
Timers and stopwatch
Rearview Camera(doesnt record)
Distance readout
Height and angle(use distance and angle and trig)
Bubble level
Sound level meter
NFC contact tap(on side of glasses for my info)
Keyword triggers(if you say time, the clock appears, etc)
Conversation rewind
Translation captions
Electronic tint(power it to tint them like transitions)
earbud for music(has a port to plug an earbud in)
Auto brightness(detect the room and adjust)
HUD games(maybe an emulator eventually)
Music tuner
Metronome
Microphone
Thermal vision maybe

2026-10-30 
This was a long brainstorming session. I started by going over all the ideas I had written in my notebook and then picked out the most promising ones. I then drew them in more detail to get a full picture. The options were a self-balancing cube; it would use a PID algorithm and some physics calculations to decide how much to move a heavy flywheel to keep it balanced on its corner. It would also jump up onto its corner. The second one is a callisthenics robot. This would consist of a BUS servo chain that would move the arms to do a planche, front lever, handstand, handstand push-up, and L-sit. To get it to do this, I was thinking of using an AI training sim like Issac Lab. The last designI didn'tt choose was a micro monocopter. This would have one 1.5-2inch prop and would move by having two layers of fins perpendicular to each other. One of these layers would be split in two so it could spin. The design I settled on is a pair of AR glasses with the main goal being that they cannot tell that they are not just normal glasses. They will also have other functionality, like a bat sense which uses sensors and vibrating motors. The other features are not decided yet.
