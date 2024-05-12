aarch64 openbsd

patch

```patch
aarch64-*-openbsd*)	targ_emul=aarch64fbsd
			targ_extra_emuls="aarch64fbsdb aarch64elf"
			;;
```

openbsd gcc patches

- https://github.com/openbsd/ports/blob/master/lang/gcc/8/patches/patch-gcc_config_gcc
- https://raw.githubusercontent.com/openbsd/ports/master/lang/gcc/11/patches/patch-gcc_config_aarch64_openbsd_h
