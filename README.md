[![Website](https://img.shields.io/badge/sitcomtn--110-lsst.io-brightgreen.svg)](https://sitcomtn-110.lsst.io)
[![CI](https://github.com/lsst-sitcom/sitcomtn-110/actions/workflows/ci.yaml/badge.svg)](https://github.com/lsst-sitcom/sitcomtn-110/actions/workflows/ci.yaml)

# TMA Performance Settings vs Capacitor Bank

## SITCOMTN-110

We want to compare the maximum velocity, acceleration and jerk on every slew with the minimum value of the capacitor banks on the TMA.

Phase, the contractor responsible for the TMA Power Supply and the Capacitor Banks, suggests that we keep these voltage drops above 575 V.

**Links:**

- Publication URL: https://sitcomtn-110.lsst.io
- Alternative editions: https://sitcomtn-110.lsst.io/v
- GitHub repository: https://github.com/lsst-sitcom/sitcomtn-110
- Build system: https://github.com/lsst-sitcom/sitcomtn-110/actions/


## Build this technical note

You can clone this repository and build the technote locally if your system has Python 3.11 or later:

.. code-block:: bash

```sh
git clone https://github.com/lsst-sitcom/sitcomtn-110
cd sitcomtn-110
make init
make html
```

Repeat the `make html` command to rebuild the technote after making changes.
If you need to delete any intermediate files for a clean build, run `make clean`.

The built technote is located at `_build/html/index.html`.

## Publishing changes to the web

This technote is published to https://sitcomtn-110.lsst.io whenever you push changes to the `main` branch on GitHub.
When you push changes to a another branch, a preview of the technote is published to https://sitcomtn-110.lsst.io/v.

## Editing this technical note

The main content of this technote is in `index.md` (a Markdown file parsed as [CommonMark/MyST](https://myst-parser.readthedocs.io/en/latest/index.html)).
Metadata and configuration is in the `technote.toml` file.
For guidance on creating content and information about specifying metadata and configuration, see the Documenteer documentation: https://documenteer.lsst.io/technotes.
