Hello everyone. This is my buildlog for a 6x6 dactyl manuform mini, based on the l4u version with a few modifications.

The first thing I noticed, as a first-time builder, was a lack of information on l4u's page about how exactly to change the configuration. After installing Clojure, Leiningen and OpenSCAD, I was aware that I could type 'lein generate' to generate a new scad file, but unaware of how to change those results. So, the first important piece of information I'll include is how to find that file. It's called dacyl.clj and it's in src/dactyl_keyboard. 

The coded patches (5x6, 6x6, etc) do a good job of getting you started, (just substitute the differences, from here it should be pretty intuitive) but I liked playing around with some other factors, especially the keyboard height, and specifics of the walls. I personally thickened the walls and added a bit of height to my keyboard, because I tilted mine a bit more than standard and wanted to make sure I had enough room underneath. However, playing around with these parameters in openSCAD is nice to look at.

The second issue I came across was the lack of a proper base plate. After playing around with the file for a bit I realized that i could generate new outputs using split, and used that to generate a base plate specific to my model. The files are there, make sure you check that they still work if you use a different configuration. 

I've sent the files off to a friend to be printed, so I'll continue this buildlog once they arrive, and I'll include here some notes about switch and keycap choice.

One of the main issues that I had with this build (I didn't really want to spend too much) was keycaps. Generally the sets I saw on MK and drop were pretty expensive, so at this point I'm thinking I'll use resin-printed DSA or XDA keycaps. I'm a fan of a bit of a larger profile so I'm leaning toward XDA, but my research has also told me that SA keycaps were originally intended for use, so I might try 3d printing them all and just seeing what works best, especially before potentially buying a set.

(opinionated statements ahead)
Ah, switches. I'm partial to low-resistance linears myself, and this might be the only section of this build that I splurge, since I'm really eyeing the cherry mx silvers, and since I need 80, might end up spending around 1/2-3/4 of the build cost on either a 90-pack (just the closest number) or a 60-pack and a few 10-packs. Wholesale distribution would be so great to know about right now.
(my current build is a Ducky one 2 TKL on cherry MX reds. and I like it although definitely think that sometimes I would like a bit less resistance. 
