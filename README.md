# User Configuration Manager

A simple Python-based user configuration manager that allows users to:

* Add new settings
* Update existing settings
* Delete settings
* View all current settings

This project demonstrates the use of:

* Python functions
* Dictionaries
* Tuples
* Conditional statements
* String formatting
* Loops

## Features

### Add Settings

Add a new setting to the dictionary.

Example:

```python
add_setting(settings, ("theme", "dark"))
```

---

### Update Settings

Update an existing setting.

Example:

```python
update_setting(settings, ("theme", "light"))
```

---

### Delete Settings

Delete a setting from the dictionary.

Example:

```python
delete_setting(settings, "theme")
```

---

### View Settings

Display all current settings in a formatted way.

Example:

```python
print(view_settings(settings))
```

---

## Technologies Used

* Python 3

---

## Concepts Practiced

* Functions
* Dictionaries
* Tuples
* String methods (`lower()`, `capitalize()`)
* Dictionary methods
* Conditional logic
* Loops

---

## Sample Output

```python
Current User Settings:
Theme: dark
Notifications: enabled
Volume: high
```

---

## Author

Created as a beginner Python practice project.
