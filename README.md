# pd-monome

A collection of pure data objects designed for connecting to and communicating with monome devices.

You’ll need to [install monome serialosc](https://monome.org/docs/serialosc/setup/) if you haven’t already.

[Download the repository](https://github.com/barnabywalters/pd-monome/archive/refs/heads/main.zip) and move the  `monome/` folder to somewhere in your puredata path.

Use the `[monome]` object to connect to grids and arcs.

Use the various `[monome/grid/*]` objects to quickly create grid instruments.

Take a look at the `examples/` (`grid-kb.pd` is a good start) and the built-in help patches to see how.

Please note that due to pure data’s OSC limitations, the grid UI elements currently only work with devices where the prefix is set to `/monome`. This might change in the future — please let me know if this is an issue for you! See `[monome/_prefix-warning]` for more details.

More grid UI elements, utils and arc objects coming soon!

Having problems? Got ideas? File a new issue. Please include as much relevant information as possible, e.g. operating system, pd version, grid hardware, output from `/sys/info`, etc.

## What it looks like

![](https://barnabywalters.github.io/pd-monome/pd-monome-help.png)

![](https://barnabywalters.github.io/pd-monome/pd-monome-grid-ui-demo.jpeg)

![](https://barnabywalters.github.io/pd-monome/pd-monome-grid-ui-demo-patch.png)
