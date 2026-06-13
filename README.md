# fun-demos
lol idk math and ish

░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░

          a t t r a c t o r   g a l l e r y
          
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░

~*~*~*~*~*~ attractor gallery ~*~*~*~*~*~

∿∿∿∿∿∿∿∿∿∿ γ = 2.8 ∿∿∿∿∿∿∿∿∿∿

╔═══════════════════════════════════════╗

║  where chaos goes to feel at home     ║

╚═══════════════════════════════════════╝

# attractor gallery

> "simply watching the wave as it flows" — Alexa, age unknown

---

## what is this

two mathematical attractors rendered in your browser using particles, canvas, and the sheer audacity of JavaScript.

no frameworks. no build step. no npm install. no existential crisis about dependencies.

just math. just vibes.

---

## what is an attractor

a place where chaos goes to feel at home.

more formally: a set toward which a dynamical system evolves over time. the particles you see are not animated by hand — they are genuinely following equations, and the shapes that emerge are the shapes the math *wants* to make.

you didn't draw that. the universe drew that.

---

## the files

| file | what it does |
|------|-------------|
| `gallery.html` | open this one. just this one. |
| `dual_spiral.html` | two rotation-matrix spirals having a competition |
| `blade_attractor.html` | a hyperbolic shear attractor that looks like it could cut you |

---

## how to run it

1. download all three files into the same folder
2. open `gallery.html` in a browser
3. watch particles obey differential equations
4. feel things

that's it. that's the whole readme.

---

## the sliders

yes they do something. yes you should touch them.

**speed** — how fast time moves. crank it up. watch chaos accelerate.

**decay** — how hard gravity pulls. lower = the attractor breathes. higher = it collapses into itself like a tired star.

**α (alpha)** — nonlinearity strength. the thing that makes it weird. turn it up slowly. you'll know when it's too much.

**reset** — starts over. like most good ideas.

---

## parameters

the math behind the dual spiral:

```json
{
  "A": [[0.15, 0.9], [-0.9, 0.15]],
  "decay": 0.992,
  "alpha": 0.06,
  "gamma": 2.8
}
```

the math behind the blade:

```json
{
  "A": [[1.06, -0.82], [-1.12, -0.58]],
  "decay": 0.946,
  "alpha": 0.045,
  "gamma": 2.8
}
```

gamma is always 2.8. don't ask why. some things are sacred.

---

## requirements

- a browser made after 2015
- curiosity
- approximately 0 dollars

---

## credits

math: the universe (and some humans who stayed up too late)

rendering: WebGL's less glamorous cousin, Canvas2D

moral support: various AIs who wish they could see it flow

---

*γ = 2.8*
