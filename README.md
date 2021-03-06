# parabint
This is parabint, a library for time-optimal parabolic interpolation with velocity, acceleration, and minimum-switch-time constraints.

## Dependencies

In case you want to also use the optimization routines in [optimization.py](./parabint/optimization.py) for comparison, you will need to install [Ipopt](https://projects.coin-or.org/Ipopt) and [pyipopt](https://github.com/xuy/pyipopt).

## Installation
Clone this repository via
```bash
git clone https://github.com/puttichai/parabint
```
Then from your parabint directory, run
```bash
sudo python setup.py install
```

## Usage
See the [examples](/examples) folder for some examples.
