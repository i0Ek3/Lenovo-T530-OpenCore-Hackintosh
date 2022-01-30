# Lenovo-T530-OpenCore-Hackintosh

OpenCore hackintosh for Lenovo T530(i7-3630).

## Here The Thing

I do not config OpenCore EFI for T530 for now, but I was used [https://github.com/5T33Z0/Lenovo-T530-Hackintosh-OpenCore](https://github.com/5T33Z0/Lenovo-T530-Hackintosh-OpenCore) for a couple days, that's really amazing, and the degree of completion of EFI is also very high, basically very stable. Meanwhile, I found an issue on it(I'm not sure whether the others have the same one): **mouse cursor floating**. Sometimes I just clean NVRAM cache and everything will be ok, sometimes not. So I read the official document to find how to solve it, and I get the answer: **use SSDT-Thinkpad_Trackpad.aml to avoid this issue**. But I didn't test it(you should test it by yourself, pick -1 or -2 under the ACPI/), cause of I reinstalled Windows on T530, maybe somedays I will try it again.

So, you can referenced 5T33Z0's version totally, because of his work is very detailed, thanks to him.

## Configuration

- CPU: i7-3630
- Graphic: HD Graphics 4000
- Memory: 4 GB * 2
- Disk: 128 GB SSD + 1 TB HHD
- Other: the stock one

## ACPI

Under the ACPI/, it contains two SSDT-Thinkpad_Trackpad.aml files and one original DSDT.aml, you can use it directly to compile.

\# TODO

## Credit

- [5T33Z0](https://github.com/5T33Z0)