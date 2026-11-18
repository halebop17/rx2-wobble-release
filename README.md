# rx2-wobble

REX importer for [Renoise](https://www.renoise.com): drop a `.rx2` / `.rex` / `.rcy` file on Renoise and
get an instrument with one slice per key plus a phrase that plays the loop in time with the song tempo.

Version 1.0: import and Write Loop to Pattern, tested in Renoise 3.5.4.

## Install

Needs Renoise 3.5 or later and macOS 11 or later (Apple silicon or Intel). Windows is not supported yet.

1. Download [`com.halebop.RX2Wobble.xrnx`](https://github.com/halebop17/rx2-wobble-release/releases/latest) and drop it on Renoise (or double-click it).
2. If the old *RX2Loader* tool is installed, remove it (*Tools > Tool Browser*): both claim `.rx2` files.
3. Drop a `.rx2`, `.rex` or `.rcy` file on Renoise.

The tool contains a small helper program. On first use it clears the macOS download flag on that helper
(`xattr -d com.apple.quarantine`, only inside the tool's own folder), so there is no security prompt.
