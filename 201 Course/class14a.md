# Transforms

### Transform Syntax
The actual syntax for the transform property is quite simple, including the transform property followed by the value.
The value specifies the transform type followed by a specific amount inside parentheses.

div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}


# Transitions
As mentioned, for a transition to take place, an element must have a change in state,
and different styles must be identified for each state. The easiest way for determining styles for different states 
is by using the :hover, :focus, :active, and :target pseudo-classes.



# Animations
Transitions do a great job of building out visual interactions from one state to another, 
and are perfect for these kinds of single state changes. However, when more control is required, 
transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.