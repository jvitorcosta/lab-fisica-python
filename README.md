# Physics lab in Python 👨🏾‍🔬 💡

Analyses from a university physics lab course (2021), done with my classmate Júlio César. Each
notebook has the lab's measurements typed in, so it runs on its own. The notebooks are in
Portuguese.

| Notebook | What it does |
| --- | --- |
| [`experimento_1/`](experimento_1) | **Linear and non-linear resistors.** I-V curves of a resistor, a lamp and a diode, with error bars, linear regression and the fitted resistance. |
| [`experimento_2/`](experimento_2) | **Ohm's law and resistivity.** Voltage against current for several wires, each wire's resistance with its uncertainty, and the material's resistivity. |
| [`figuras_lissajous/`](figuras_lissajous) | **Lissajous figures.** Simple harmonic motion and the figures formed by combining two perpendicular oscillations. |

## Run it

```sh
uv run --with pandas --with numpy --with scipy --with scikit-learn --with matplotlib --with jupyter jupyter lab
```
