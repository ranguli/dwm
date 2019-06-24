# dwm

My fork of dwm with patches for configuration changes. I keep the source code itself 'vanilla' within git, 
and maintain a set of patches that can be applied. This way it's easier to apply/remove them.

## Patches

### Creating

To create a patch:

```bash
git diff -up > patch
```

### Applying

In order to apply a patch:

```bash
git apply patch
```

## Building
```bash
cd ./dwm && make && sudo make install
```

## Methodology
The changes in both `dwm.c` and `config.h` made by patches should _not_ be tracked into version control. This gives us the flexibility to apply/remove patches freely.
