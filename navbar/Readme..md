# Music Navigation Bar with Wiggle Animation

This project introduces a vibrant redesign of the music navigation bar, enriching user interaction through a lively wiggle animation effect triggered upon hovering over each navigation link. The purpose is to visually convey the rhythm of the music beats, enhancing the overall navigation experience.

## Features

- **Wiggle Animation on Hover:** When a user hovers over a navigation link, a lively wiggle animation engages, providing a dynamic representation of music beats.

- **Color Change:** The navigation links exhibit a purple color change during the wiggle animation, creating an additional visual impact.

## Animation Details

- **Duration:** 0.5 seconds
- **Timing Function:** ease-in-out
- **Iteration:** Infinite

### Keyframes

```css
@keyframes wiggleAnimation {
  0% {
    transform: rotate(-6deg);
  }
  50% {
    transform: rotate(2deg);
  }
  100% {
    transform: rotate(4deg);
  }
}
```

This keyframe animation defines the rotation values at different percentages, contributing to the lively wiggle effect.

