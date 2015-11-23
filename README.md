# Apply Patches to Freescale MQX 4.1

Clone the patch file into MQX sources root folder.

``` bash
cd udooneo-dev/mqx/
git clone https://github.com/UDOOboard/udooneo_mqx41_patch/
```

Then apply patches to the sources.

``` bash
patch -p1 < ./udooneo_mqx41_patch/mqx4.1_udooneo.patch
```
