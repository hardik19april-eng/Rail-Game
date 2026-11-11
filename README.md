# Midnight Express

A small 3D train game that runs in the browser. You drive a steam locomotive along a foggy, rainy line at night, stop at four stations, and try not to run over whatever is standing on the tracks.

Play it here: https://hardik19april-eng.github.io/Rail-Game/

## Running it

You don't need to install anything. Download `index.html` and open it in Chrome or Edge.

It loads Three.js from a CDN, so you need to be online the first time you open it. If you get a blank page, press F12 and check the console.

## Controls

- W / S: throttle up and down
- Space: brake
- X: emergency brake (the passengers will hate it)
- H: whistle
- C: change camera (cab, chase, trackside)
- R: rain on/off
- P: pause
- Mouse: look around in the cab

## How the game works

The route has four stations. You get points for stopping near the red STOP board, and a bonus if you arrive on time. Overshoot a station and you lose points.

There are speed limits too. They drop on sharp curves, over the bridge, in the tunnel, at the level crossing and near stations. Go over the limit for too long and you get fined.

Some signals along the way start out red. If you get close they turn green after a few seconds, but passing one while it's still red costs you.

Passenger comfort goes down if you brake too hard or speed. It counts toward your final score, so brake early. A "BRAKE NOW" warning shows up when you're about to overshoot a station.

The horror part: three times on the route there's a pale figure standing on the track. If you stop and wait, it disappears. If you drive into it, you get a jumpscare.

The game ends at the last station and gives you a grade from S to D.

## Tech

Everything is in one HTML file. The 3D is Three.js. The speedometer, sounds and textures are all made in code, so there are no image or audio files. The track is a spline curve, and the trees, hills and poles are generated along it.

## Things that are a bit rough

- The braking physics are simple, not realistic
- The level crossing barriers might look off from some angles

## About how I made it

I thought that I should make a game related to trains, and then I got this idea...I worked towards it for an hour, then I got a satisfied result. 
I took help from ChatGPT just to correct some errors and to stop my game from malfunctioning. I coded the complete game in VS Code.
(I used AI in a limit)


<img width="1912" height="1021" alt="Screenshot 2026-11-07 162216" src="https://github.com/user-attachments/assets/c7a5673a-d423-4a8b-87dd-c8c252b0af6b" />
<img width="1852" height="973" alt="Screenshot 2026-11-08 005104" src="https://github.com/user-attachments/assets/5f0ad2ef-440c-4361-ba57-45cc9cebae22" />
<img width="1897" height="1021" alt="Screenshot 2026-11-08 005118" src="https://github.com/user-attachments/assets/4c82d79b-856b-4a1c-8867-7fb2bb6a3790" />
