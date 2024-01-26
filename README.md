# heft-node-rig-tutorial

This is a copy of the
[heft-node-rig-tutorial](https://github.com/microsoft/rushstack-samples/tree/main/heft/heft-node-rig-tutorial)
tutorial project from the [rushstack-samples](https://github.com/microsoft/rushstack-samples) repo.

# Building

Install the Heft CLI:

```bash
npm install -g @rushstack/heft
```

Build the project:

```bash
heft build
```

Update Jest snapshots:

```bash
heft test --update-snapshots
```

Watch mode:

```bash
heft build-watch
```
