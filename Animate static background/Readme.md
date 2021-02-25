# How to animate background image simply ?
****************************************************************

# The idea here is to animate the background position property.

  @keyframes animateBackground {
    100% {
        background-position: 0px -3000px;
    }
  }

# Remomber to select an appropriate perspective and perspective origin.

  perspective: (value)px;
  perspective-origin: 50% 50%; // adjust as u need the origin 