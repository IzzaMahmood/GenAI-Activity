# User Settings Interface

A simple web page that shows the documented Python interface for saving a user setting.

## Overview

This project shows a Python function, `set_user_setting`, with a clear docstring. The docstring explains what the function does, what it needs, what it returns, and what errors it can raise. The code is displayed in a clean HTML page.

The function body is not written yet. It is a placeholder (`...`), so you can add your own logic.

## Features

- Clear docstring in Google style
- Type hints for all inputs and the return value
- Documented errors: `KeyError` and `ValueError`
- Includes a usage example
- Simple, readable HTML page to view the code

## The Function

```python
def set_user_setting(user_id: str, key: str, value: Any) -> bool:
```

| Parameter | Type  | Description                      |
|-----------|-------|----------------------------------|
| `user_id` | `str` | Unique ID of the user            |
| `key`     | `str` | Name of the setting, e.g. `theme` |
| `value`   | `Any` | New value for the setting        |

**Returns:** `True` if the setting was saved, `False` otherwise.

**Raises:**
- `KeyError` if `key` is not a valid setting name
- `ValueError` if `value` is not valid for the given `key`

## Example

```python
>>> set_user_setting("u123", "theme", "dark")
True
```

## Usage

1. Open the HTML file in any web browser to view the interface.
2. Copy the function into your Python project.
3. Replace `...` with your own code to save the setting.

## Requirements

- A web browser (to view the page)
- Python 3.5 or higher (for type hints)

## License

Add your license here (for example, MIT).
