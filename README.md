# OpenGL Interactive Birthday Card

Individual computer-graphics coursework (C++ / OpenGL / FreeGLUT) by **Mengxuan Shen**.

**Portfolio page:** https://shine574269.github.io/projects/cpt205-opengl.html

A real-time 2D scene built entirely from geometric primitives (no images or textures), with timer-driven animation, transformations and five kinds of interaction.

| Input | Result |
|---|---|
| Right click | Switch between day and night |
| Left click | Fade the candle flame (10 clicks to blow it out) |
| W/A/S/D, R, Q/E | Move, rotate and scale the butterfly |
| Space | Release the balloons |
| Enter | Show the birthday message |

## Files
| File | Contents |
|---|---|
| `birthday-card.cpp` | Complete source of the birthday card |
| `birthday-card-source.zip` | Source as submitted |
| `birthday-card-report.pdf` | Report: primitives, interaction and animation |
| `birthday-card-screens.jpg` | Day and night screenshots |
| `castle-*` | Materials from a separate 3D scene exercise in the same module (not shown on the portfolio) |

## Building
Compile `birthday-card.cpp` with any C++ compiler linked against OpenGL and FreeGLUT, for example:
```bash
g++ birthday-card.cpp -o birthday-card -lGL -lGLU -lglut
```
