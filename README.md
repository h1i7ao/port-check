# port-check

A small utility that checks TCP reachability with configurable timeouts.

## Why

The existing libraries were either abandoned or pulled in a large dependency tree.

## Install

```bash
pip install port-check
```

## Usage

```python
from port_check import portCheck

result = portCheck("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
