#dwm

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
