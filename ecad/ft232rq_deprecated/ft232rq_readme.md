USB-Cereal ECAD files for FT232RQ variant.

**Note:** The design contains several mistakes - the CC1/CC2 share a legacy mode resistor, while they should be split into two. The overvoltage clamp presents too much capacitance on the TX/RX lines which prevents datarates above 576000.

**The design is frozen and deprecated. FT232RQ is an NRND component.** Please see updated FT232RNQ variant for the latest designs.