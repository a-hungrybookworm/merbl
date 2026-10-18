# merbl-run
A custom 3D-printed marble race, designed from scratch! 
<img width="797" height="791" alt="Cover" src="https://github.com/user-attachments/assets/6be1c351-1518-4a37-9ec3-2aec9b188c5d" />

# features
- 3 marble tracks
- compact design
- custom assembly and supports
- custom tracks

# why was it built?
This project was built for the second week of the Hack Club YSWS Half-life!

# design process
I first tried out the starter tracks in the Half-life tutorial, following which I researched a lot about how to use the different tools in Onshape.

I eventually decided that I was going to make a circular, sloping, cylindrical track - a bit like the classic helter-skelter theme park ride. I spent a lot of time doing this - before I realised that it wasn't really possible - not with my limited knowledge of Onshape.

Then I started making the first track of my merbl-run, and eventually the project grew to become the finished version it is today. I have three marble tracks, each separate 3D-printable parts, and a *lot* of supports, also separate 3D printable parts. I plan on insertin gthe supports into the base during assembly, and placing the tracks on top of them.

I did face a lot of problems while designing the merbl-run - especially that of plane orientation. Each time I created a new plane, the resulting track would bend awkwardly at a weird place, and filleting wouldn't fix it. 
<img width="342" height="190" alt="Bends" src="https://github.com/user-attachments/assets/e0f23e19-8af7-4959-b6da-ed5a3b972999" />
The weird bends in my first track. 
<img width="972" height="825" alt="Orange track" src="https://github.com/user-attachments/assets/bd92326b-24d9-481d-8786-b4ccd2120361" />
I eventually fixed this (in the last track I designed, the orange one ↑) by making sure that each new curve in my sketch would be tangential to the previous one, and that each new plane would only tilt from the line tangent to the previous curve :).

Another problem I faced - as I changed the plane orientation multiple times, the track would turn upside down. I fixed this one by changing the sweep profile for each new plane, and I cheated a bit in some curves :), by making the neck of the track 7mm wide for the 8mm marble - so it wouldn't fall out.

The marbles from the first two tracks fall into a custom plinko track, attached to the base.
<img width="825" height="752" alt="Plinko" src="https://github.com/user-attachments/assets/c28eaa99-3e83-471f-81c5-ba78841b7136" />

For the last track (light grey), it falls into a sloping, wavy track.
<img width="968" height="781" alt="Wavy" src="https://github.com/user-attachments/assets/6437a1f9-a6b7-4410-86dd-3ac6f903d162" />

As of now, that's where they'll stay, but I'm planning on designing a mechanism to lift the marbles to the top again sometime soon.

# what I learnt
I learnt a lot about CAD in Onshape - including how to use various tools like revolve, sweep and split, use different kinds on planes, and make fully defined (as much as possible!) sketches using various constraints.

# notes on attachments
The .stl and .step files are uploaded in the repo, and each file contains:
- one 'merbl run' file - that contains the whole 3D design
- a 'base' file - the base of the merbl-run
- three 'curve' files - the 3 marble tracks
- 'rod', 'rods', 'stack' and 'stacks' files - the supports

# images
This is the merbl-run!
<img width="797" height="791" alt="Cover" src="https://github.com/user-attachments/assets/8d584bd4-95f7-4e2e-b94c-fe7c888e16fa" />

And its backside - 
<img width="1120" height="870" alt="Back" src="https://github.com/user-attachments/assets/4f216fe4-7770-4020-aff0-d2d3a11f0837" />

# acknowledgements
This project would not have been possible without the constant guidance and support of the Half-life community - thank yall so much!

