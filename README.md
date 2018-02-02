# Building interfaces from the future

The slides for my talk at [GUADEC 2017](https://2017.guadec.org/talks-and-events/#abstract-16-building_interfaces_from_the_future)

Video recording of the talk on [Youtube](https://youtu.be/x1GayrNL-RY)

### Abstract

Animations are the future of interface design. They enable developers to make interfaces more understandable by offloading processes from the user’s brain to the screen. However, in many cases animations are simply added as transitions between independently designed screens. This can result in animations contradicting each other spatially. I co-wrote an [article](https://alistapart.com/article/motion-with-meaning-semantic-animation-in-interface-design) about why this is a problem and outlined a solution: Designing semantic components which change over time, and then using these to compose interfaces.

Even though the industry seems to largely agree that this is the way forward, there are very few interfaces implementing these ideas. I believe the main reason for this is that the current generation of layout technologies is built for static layouts with strict hierarchies. This makes it prohibitively difficult to build interfaces where components move fluidly between different states.

I will show some interface prototypes I built and explain why they were so difficult to implement with current technology. Finally, I will outline some ideas for a better layout API, to make building awesome, fluid interfaces from the future more feasible.

### Further Reading

[Motion with Meaning: Semantic Animation in Interface Design](https://alistapart.com/article/motion-with-meaning-semantic-animation-in-interface-design) by Amin Al Hazwani and myself

[The Principles of UX Choreography](https://medium.freecodecamp.org/the-principles-of-ux-choreography-69c91c2cbc2a) by Rebecca Ussai Henderson

[Transitional Interfaces](https://medium.com/@pasql/transitional-interfaces-926eb80d64e3) by Pasquale D’Silva

[Spatial Interfaces](https://medium.com/elepath-exports/spatial-interfaces-886bccc5d1e9) by Pasquale D’Silva

[Material Design Guidelines (section on motion)](https://material.io/guidelines/motion/material-motion.html) by Google

[Creating Usability with Motion: The UX in Motion Manifesto](https://medium.com/ux-in-motion/creating-usability-with-motion-the-ux-in-motion-manifesto-a87a4584ddc) by Issara Willenskomer
