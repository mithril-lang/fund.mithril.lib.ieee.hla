# fund.mithril.ieee.hla

Independent specification plugin for Mithril JSON RPC v1. Plugin ID `fund.mithril.ieee.hla`.

Operations: hla-exercise.

Install with `python -m pip install -e .`; discovery uses the `mithril.interop.plugins` entry-point group.

Build native OpenRTI with `./scripts/build-hla.sh`. In-process IEEE 1516e has been verified; TCP timed out on macOS. No RF or RPR FOM support is claimed.

[Detailed boundaries](https://github.com/mithril-lang/fund.mithril.interop/blob/main/docs/design.md)
