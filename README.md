# litebsd-gcc-4.8.1-patch
LiteBSD gcc 4.8.1 patch for successful compilation.<br>
Usage:<br>
`cd binutils-2.23.2`<br>
`gzip -dc binutils-2.23.2.patch.gz | patch -p 1`<br>
`cd gcc-4.8.1`<br>
`gzip -dc gcc-4.8.1.patch.gz | patch -p 1`<br>
`cd qemu`<br>
`gzip -dc qemu.patch.gz | patch -p 1`
