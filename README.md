# Kensho optional micro engine — source publication

YaneuraOu engine source at revision 0f421391ae311df9df57dcfcb2b4a78a1972bdf8, with the Android micro build changes.
Engine license: GPLv3, full text in engine/LICENSE. Original copyright notices
are retained throughout engine/. Redistribution rights are governed by those
licenses; this source publication does not add a non-commercial restriction.

Engine binary reference: c0c1409ad31762bd0eb8ceee4bb23a3af3df3fec2928356e081b46560096bb41 (1413448 bytes, ARM64/API24 PIE).
Read BUILDING.md, CHANGES.md, RUNTIME-SCOPE.md and SOURCE-BINARY.json.
Only engine/build/toolchain notices are included. No proprietary Kensho app,
teaching content, model data, credentials or binary is published in this archive.
Optional model: Tsuyouraou11micro, separately MIT-licensed by its author.
This source release does not decide the GPL scope of a combined application.

## vc7 runtime source supplement (090)

Use `kensho-micro-engine-source-089.zip` together with
[kensho-runtime-source-090.zip](https://raw.githubusercontent.com/Sekimosoft/kensho-micro-engine-source/75958aa245fa272b383075b9ea727b2b2fa4601e/kensho-runtime-source-090.zip).
Verify `SHA256SUMS-089.txt` and `SHA256SUMS-090.txt`.
The supplement includes fixed Android LLVM C++/ABI/unwind/compiler-runtime sources,
original build scripts and licenses, and SHA256/symbol/strip-equivalence evidence
for engine c0c1409ad31762bd0eb8ceee4bb23a3af3df3fec2928356e081b46560096bb41.
OS bionic libc/libm/libdl and system linker are device-provided. Standard Android
CRT link-input hashes are recorded; their System Library classification is separate
from conservatively supplied LLVM sources. General build tools are not bundled.
The combined application's licensing decision remains separate from this technical
source publication. No proprietary application or model data is published here.
