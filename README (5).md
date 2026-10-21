# set_user_setting – Python Docstring Reference Page

A lightweight, single-file HTML page that documents the `set_user_setting` Python function, including its signature, a Google-style docstring, and a usage example. The code is presented in a clean, styled code box with a gold border, rounded corners, padding, and a soft shadow.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Preview](#preview)
- [Getting Started](#getting-started)
- [Function Reference](#function-reference)
- [Customization](#customization)
- [Project Structure](#project-structure)
- [Browser Support](#browser-support)
- [License](#license)

---

## Overview

This project displays the documentation for a Python function that updates a single setting for a given user. It is a static page with no dependencies, no build step, and no JavaScript, so it can be opened locally or hosted anywhere.

## Features

- **Zero dependencies:** one self-contained `index.html` file
- **Clear documentation:** Google-style docstring with `Args`, `Returns`, `Raises`, and `Example` sections
- **Styled code box:** gold (`#FFD700`) border, 12px rounded corners, 20px padding, and a subtle drop shadow
- **Responsive:** viewport meta tag included, and long lines scroll horizontally inside the code box
- **Readable typography:** Arial for page text, Consolas (monospace) for code

## Preview

| Element        | Style                                  |
| -------------- | -------------------------------------- |
| Page background | Peach (`#FFDAB9`)                      |
| Code box       | White background, gold 2px border      |
| Corners        | `border-radius: 12px`                  |
| Shadow         | `0 4px 12px rgba(0, 0, 0, 0.2)`        |

## Getting Started

### Option 1: Open locally

1. Save the HTML file as `index.html`.
2. Double-click the file, or open it in your browser via **File → Open**.

### Option 2: Serve with a local server

```bash
# Python 3
python -m http.server 8000
```

Then visit <http://localhost:8000>.

### Option 3: Deploy

Because the page is fully static, it can be hosted on GitHub Pages, Netlify, Vercel, or any static web host by uploading `index.html`.

## Function Reference

```python
def set_user_setting(user_id: str, key: str, value: Any) -> bool
```

Sets a single setting for a user.

### Parameters

| Name      | Type  | Description                                  |
| --------- | ----- | -------------------------------------------- |
| `user_id` | `str` | Unique ID of the user.                       |
| `key`     | `str` | Name of the setting, e.g. `"theme"`.         |
| `value`   | `Any` | New value for the setting.                   |

### Returns

| Type   | Description                                      |
| ------ | ------------------------------------------------ |
| `bool` | `True` if the setting was saved, `False` otherwise. |

### Raises

| Exception    | Condition                                        |
| ------------ | ------------------------------------------------ |
| `KeyError`   | `key` is not a valid setting name.               |
| `ValueError` | `value` is not valid for the given `key`.        |

### Example

```python
>>> set_user_setting("u123", "theme", "dark")
True
```

> **Note:** The function body in the page is a placeholder (`...`). Implement the persistence and validation logic to suit your application.

## Customization

All styling lives in the `<style>` block at the top of the file.

**Change the code box border color**

```css
pre {
  border: 2px solid #FFC107; /* amber */
}
```

**Adjust corners, padding, or shadow**

```css
pre {
  border-radius: 8px;
  padding: 24px;
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.25);
}
```

**Change the page background**

```css
body {
  background: #FFDAB9;
}
```

## Project Structure

```
.
├── index.html   # The documentation page (HTML + CSS)
└── README.md    # Project documentation
```

## Browser Support

Works in all modern browsers, including Chrome, Firefox, Safari, and Edge.

## License

This project is released under the [MIT License](LICENSE). Replace with the license that fits your project.
