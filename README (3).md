# Python Docstring Page

A simple web page that shows the docstring of a Python function called `set_user_setting`.

## What it shows

- A title: `set_user_setting`
- A code box with the function and its docstring (Args, Returns, Raises, Example)

## How to use

1. Save the code as `index.html`.
2. Open the file in any web browser.

No install or setup is needed.

## Layout and style

- The content is centered, with a maximum width of 800px.
- Colors and spacing are set in one place (CSS variables at the top of the `<style>` section).
- It works on phones, tablets and desktops.
- Long lines of code scroll inside the code box.

## How to change it

| What | Where |
|------|-------|
| Colors | `--bg`, `--surface`, `--border`, `--text` in `:root` |
| Spacing | `--space-sm`, `--space-md`, `--space-lg`, `--space-xl` in `:root` |
| Page width | `max-width` in `main` |
| Code text | Inside `<pre><code>` |

## Note

Inside the code box, use `&gt;` instead of `>`. This makes the text show correctly in HTML.
