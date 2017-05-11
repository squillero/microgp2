MicroGP v2
==========

[![License: GPL](https://img.shields.io/badge/license-gpl--2.0-green.svg)](https://opensource.org/licenses/GPL-2.0)
[![Status: Obsolete](https://img.shields.io/badge/status-obsolete-red.svg)](https://github.com/squillero/microgp3)
![Language: C](https://img.shields.io/badge/language-C-blue.svg)

MicroGP v2 (µGPv2, uGP2, ugp2, `&micro;GP v2`) is an evolutionary tool for generating assembly programs tweaked for a specific microprocessor — hence the Greek letter micro in its name. µGPv2 first fosters a set of random programs, then iteratively refines and enhance them in order to maximize a given metric. It uses the result of an external evaluation, together with some internal information, to efficiently explore the search space (DOI: [10.1007/s10710-005-2985-x](https://link.springer.com/article/10.1007/s10710-005-2985-x)).

µGPv2 was developed in 2002 and maintained since 2006; the first version was codenamed *Chicken Pox*, because the isolation caused by that infection allowed me to write most of the code in a single week. µGPv2 added several new features and significantly broadened the applicability of the original version 1: it was able to load a list of parametric code fragments, called *macros*, and to optimize both their order inside a test program and their parameters. 

While µGPv2 was mainly exploited for test and verification of small microprocessors, in a collaboration with Intel it scaled up tackling a real Pentium 4 (DOI: [10.1109/MTV.2004.5](http://dx.doi.org/10.1109/MTV.2004.5)). And in a far less mundane research, it created the first *machine-written programs* ever able to become *King of the Hill* in all the main international *core-war* competitions (DOI: [10.1109/TEVC.2005.856207](http://dx.doi.org/10.1109/TEVC.2005.856207)). With time, µGPv2 has been coerced into solving problems it was not meant for, and ultimately was [re-implemented from scratch](https://github.com/squillero/microgp3).

**Copyright © 2002-2006 Giovanni Squillero**

µGPv2 is free software: you can redistribute it and/or modify it under the terms of the [GNU General Public License](http://www.gnu.org/licenses/) as published by the *Free Software Foundation*, either [version 2](https://opensource.org/licenses/GPL-2.0) of the License, or (at your option) any later version.
