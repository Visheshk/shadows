##Shadows
This is intended to be a more wide covering game or set of games or simulations, that cover a variety of 3 to 2 dimension projections, and ideally in the future, 4 to 3 dimension projections as well.

It would be interesting to see what places this can go. Hopefully something interesting?

###Current State
Currently, shadow1.html is a very simple, and poorly coded simulation of how the shadow of a cubical frame would change, if a point source of light in front of a cube moves. The controls w, a, s, d move the point source of light up (northward), down, left, and right respectively. The cube creating the shadow and the source of light are behind you. The point is that you can only see the sadow, and you're supposed to see patterns by observing what happens with different shadows.

The calculations have been manually calculated for a cube, with a fair chance of mistake, especially in lateral stretching. Which, by my calculation, doesn't happen at all. Though in my imagination, it does.
Tell me if you can what I'm doing wrong, and where.
Also, the figures don't look shadowy at all. Maybe some blurs and stuff. Aand, maybe the projection system I've used is not very correct for a point source of light. Need to ensure its accuracy, among other stuff.

And the shadow is not at all, being created dynamically from one source object, which for starters, is how things should be.

###Possible future steps
After creating the shadow by simply defining the source object's face, I'd want to provide support for seeing the shadow by rotating the object. Along different axes.

Of course moving to further dimensions is desirable after that, but visibly distant.



