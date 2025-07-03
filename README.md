# pyodide-numpy-2.0-rebuilds

> [!IMPORTANT]
> This repository has been archived and is no longer ascertained to be necessary, as all packages
> in the Pyodide distribution are built against NumPy>=2.0.0 post the Pyodide 0.27 release.

> [!TIP]
> The PyArrow recipe is accredited to [`@joemarshall`'s work](https://github.com/joemarshall/pyarrow-pyodide).

Rebuilds against NumPy v2 for certain Pyodide packages. Please see [pyodide/pyodide#4925][1]
and the [Releases section for this repository][2] for more information.

[1]: https://github.com/pyodide/pyodide/pull/4925
[2]: https://github.com/agriyakhetarpal/pyodide-numpy-2.0-rebuilds/releases

Please refer to the license information for the original packages. This repository only hosts
a WebAssembly-based binary distribution (wheel) for them for use with Pyodide.

1. [LightGBM](https://github.com/microsoft/LightGBM/blob/3f7e6081275624edfca1f9b3096bea7a81a744ed/LICENSE)
2. [PyArrow](https://github.com/apache/arrow/blob/6a0414bd9a91e890ec6a45369bf61f405180628c/LICENSE.txt)
