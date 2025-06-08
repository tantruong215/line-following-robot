# Pseudocode – Line Following Robot

## Goal
Use IR sensors to follow a black line on a white surface using motor control logic.

## Flow
- [ ] Read 3–5 IR sensors (analog or digital)
- [ ] Based on sensor state:
  - Centered: move forward
  - Slight left: turn left
  - Slight right: turn right
  - Lost: stop or reverse
- [ ] Use PWM for speed control
- [ ] Tune PID if smoother turning is desired
