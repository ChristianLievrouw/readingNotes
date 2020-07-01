# Read: 14a css transformations, transitions, and animation
- transforms have two different settings, two dimensional and three dimensional each of them have their own properties and values
## 2D transforms 
- 2D work on a x and y axis 
- 2D rotate
  - rotate element from 0 to 360 degrees
  - positive number (rotate clockwise), negative numbers (rotate counterclockwise)
- 2D scale
  - scale value makes elements smaller
  - 1 default .01 - 1
- 2D translate 
  - will change the object on the x and y plans
- best way to tell a class is in a transition state is with a ``` :hover :focus :active : target ``` pseudo-class
- four transition related properties
1. transition-property
  - determines which properties will be altered
2. transition-duration
  - duration of the changing properties, you can set different times fo different properties
3. transition-timing-function
  - speed of the transition 
4. transition-delay
## animations
when transitions need to have multiple states that is where animations take over
```@keyframes``` indicates a animation
if you want your animation to run more than one you use the ```animation-iteration-count```

Animation direction ``` animation-direction ```
  - normal, reverse, alternate, alternate-reverse

Animation play state
  - allows animation to be paused with keywords running and paused


