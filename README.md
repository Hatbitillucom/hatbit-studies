# hatbit-studies

Superproject that groups HATBIT study and experimental projects as Git submodules.

Each project is an independent Git repository with its own versioning. This superproject provides a single clone point for convenience.

## Submodules

| Submodule | Description | Platform |
|-----------|-------------|----------|
| [hatbit-study-spacedevkit-satellite](https://github.com/Hatbitillucom/hatbit-study-spacedevkit-satellite) | SpaceDevKit satellite study | Arduino |
| [hatbit-study-spacedevkit-solar-panel](https://github.com/Hatbitillucom/hatbit-study-spacedevkit-solar-panel) | SpaceDevKit solar panel study | Arduino |
| [hatbit-study-mppt-arduino-uno](https://github.com/Hatbitillucom/hatbit-study-mppt-arduino-uno) | MPPT controller study | Arduino Uno |

## Usage

```bash
# Clone with all submodules
git clone --recurse-submodules https://github.com/Hatbitillucom/hatbit-studies.git

# Initialize submodules after clone
git submodule update --init --recursive
```

You can work directly inside each submodule directory and commit/push to its origin.
