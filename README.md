# Physics lab in Python

Data analysis for a university physics lab course: I-V curves, Ohm's law and Lissajous figures.

**Status:** coursework (2021)

## Why I built it

This was the lab work for my physics course. I did it with my classmate Júlio César, so it
is shared work, and he is credited as a co-author. The notebooks are in Portuguese.

## Quick start

Each notebook has the lab's measurements typed in, so it runs on its own:

```sh
uv run --with pandas --with numpy --with scipy --with scikit-learn --with matplotlib --with jupyter jupyter lab
```

## What's in it

| Notebook | What it does |
| --- | --- |
| [`experimento_1/`](experimento_1) | **Linear and non-linear resistors.** I-V curves of a resistor, a lamp and a diode, with error bars, linear regression and the fitted resistance. |
| [`experimento_2/`](experimento_2) | **Ohm's law and resistivity.** Voltage against current for several wires, each wire's resistance with its uncertainty, and the material's resistivity. |
| [`figuras_lissajous/`](figuras_lissajous) | **Lissajous figures.** Simple harmonic motion and the figures formed by combining two perpendicular oscillations. |

## Credits

Done together with Júlio César, my classmate in the course.

## License

MIT, see [LICENSE](LICENSE). The copyright line names me only; this was done with Júlio César.
