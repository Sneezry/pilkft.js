Pyramidal Implementation of the Lucas Kanade Feature Tracker (JavaScript Version)

```
var of = pilkft(u, I, J);

Parameters:
    u:        Feature Points of the 1st Image
                [
                  {x:x0, y:y0},
                  {x:x1, y:y1},
                  ...
                ]
    I:        1st Image Array
                [
                  [I00, I01, ...],
                  [I10, I11, ...],
                  ...
                ]
    J:        2nd Image Array
                [
                  [J00, J01, ...],
                  [J10, J11, ...],
                  ...
                ]

  Output:
    v:        Optical Flow
                [
                  {x:x0, y:y0, v:{x:u0, y:v0}},
                  {x:x1, y:y1, v:{x:u1, y:v1}},
                  ...
                ]
  ```
