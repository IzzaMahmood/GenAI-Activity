# Python Docstring: `set_user_setting`

A single-page HTML document that displays a documented Python function signature and docstring for `set_user_setting`, styled for easy reading in the browser.

## Overview

The page shows the docstring for a function that sets a single setting for a user. The function body is a placeholder (`...`); this page documents the interface only and does not include an implementation.

## Function Reference

```python
from typing import Any

def set_user_setting(user_id: str, key: str, value: Any) -> bool:
    """Sets a single setting for a user.

    Args:
        user_id (str): Unique ID of the user.
        key (str): Name of the setting, e.g. "theme".
        value (Any): New value for the setting.

    Returns:
        bool: True if the setting was saved, False otherwise.

    Raises:
        KeyError: If `key` is not a valid setting name.
        ValueError: If `value` is not valid for the given `key`.

    Example:
        >>> set_user_setting("u123", "theme", "dark")
        True
    """
    ...
```

## Usage

Open the HTML file in any web browser. No build step, dependencies, or server is required.

## Styling

The page uses inline CSS with the following design choices:

| Element | Style |
| --- | --- |
| Page background | Lavender `#E6E6FA` |
| Font | Arial, sans-serif |
| Heading color | `#333` |
| Code block | White background, `1px` solid `#E89A63` border, `6px` rounded corners |
| Code font | Consolas, monospace, `14px` |

To change the page background, edit the `background` value in the `body` rule inside the `<style>` block.
