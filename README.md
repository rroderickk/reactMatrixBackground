# The React component with vanilla HTML5 canvas (using hooks)

![screenshot](/theme/screenshot.gif)
## For change the theme change your branch all console my friend
![screenshot](/theme/rightyellow.gif)

The text falls in columns each of 20px wide.

In order to get the start position of every column we will create an array.

```javascript
const columns = Math.floor(w / 20) + 1;
const startPositions = Array.from({ length: columns }).map((_, i) => ({
  x: i * 20,
  y: 0,
}));
```

In each frame of the animation, a single random character will be put at the end of each column. Initially the end (y coordinate) of each column is at 0.

In each frame we render a semi transparent black rectangle on top of the previous frame, so that the characters rendered in previous frames can look progressively dimmed.

Also we randomly reset some columns to start from the top again.

For the rest of the columns the y coordinate will be moved 20px down, so that in next frame a new character appears below the current one.

# cambiando de branch cambias el efecto.

#### g c o
alias gco=git checkout original = para volver al original 
#### g c y
alias gcy=git checkout rightYellow
![screenshot](/theme/rightyellowTrim.jpg)

#### g c l 1
![screenshot](/theme/gcl1.png)

#### g c l 2
![screenshot](/theme/gcl2.png)

#### g c l 3
![screenshot](/theme/gcl3.png)

#### g c l 4
![screenshot](/theme/gcl4.jpg)

#### g c l 5
![screenshot](/theme/gcl5.png)

#### g c l 6
![screenshot](/theme/gcl6.png)
#### g c l 7
![screenshot](/theme/gcl7.png)
#### g c l 8
![screenshot](/theme/gcl8.png)