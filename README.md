Project I can bang out with a week of steady work
Cinematic Paintings in Mogwai’s image and likeness.


Justification

I have started watching a lot of films and when I do, my brain starts burning with theories. I mostly find shots I want to capture and contextualize that will serve as inspiration when I eventually become an animator. 


Inspiration 

Cinematicpaintings.com


Features 
- HomePage shows the latest uploaded shots
- A random shot generator button 
- A list of shots and shot categories, namely:
[ ] Establishing shot
[ ] Extreme longshot
[ ] Long shot
[ ] Medium shot
[ ] Closeup
[ ] Extreme close up
[ ] Down shot
[ ] Over the shoulder
[ ] 2 shot 
[ ] 3 shot
[ ] Crowd shot
[ ] Dutch angle
[ ] Eye level
[ ] Down shot 
[ ] Up shot
[ ] Indoors
[ ] Outdoors 
[ ] B&W shots
[ ] Warm
[ ] Cool 
[ ] Day
[ ] Night 
- A submit button for new entries
- A lo-res feature 

Adjacent to this, I am thinking of other features such as: 

[ ] Architecture shot 
[ ] Fight shot 
[ ] Expressions [Anger, Surprise, etc]
[ ] Live action
[ ] 3D*
[ ] 2D*
[ ] Stop motion*


Technology


Database/Backend: PostgreSQL

Structure: 

Film

- Film Title (Should be autocompletable with first entry) 
- Year of Production
- Director
- Shot categorization

Shots

- Shot ID
- Shot URL

Categorization 

- All the above categories
- Expression t/f (f by default)
- Expression list


Frontend: React (duh)

Basic, client-side rendering. No brainer. Need to spend some time doing some design research. Matter of fact, let’s make a to-do list:

[ ] Research design. Think about the core philosophy. Do I want users to be able to organize their favorite shots like a `Pinterest pin'? In which case signing up will be encouraged. Or do I want them to merely use this as a ‘grazing’ resource. One of them is more technologically tasking than the other. 
[ ] Add a randomizer button, just because.
[ ] How about a shot o’ the day feature? Probably stretch. Not because it’s difficult, but because it is extraneous. 
[ ] A search bar
[ ] Light/dark mode (teehee) - stretch goal 
[ ] A submit form for UGC - possibly a stretch goal

And that’s it. Whew. 

Frontend Inspiration

I’m very happy to completely clone Behance, but let’s keep our eyes peeled. 
