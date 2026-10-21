# Set User Setting

## Description
This project contains a Python function to save a setting for a user, such as their theme.

## Function
`set_user_setting(user_id, key, value)`

- `user_id`: Unique ID of the user.
- `key`: Name of the setting, such as `theme`.
- `value`: New value for the setting.

## Return Value
- `True` if the setting is saved.
- `False` if it is not saved.

## Errors
- `KeyError`: The setting name is not valid.
- `ValueError`: The value is not valid for that setting.

## Example
```python
set_user_setting("u123", "theme", "dark")
```

## Note
The uploaded file contains a placeholder instead of the function's full implementation.
