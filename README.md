
# pyrobloxbot

[![Documentation badge](https://readthedocs.org/projects/pyrobloxbot/badge/?version=latest&style=flat-default)](https://pyrobloxbot.readthedocs.io/en/latest/pyrobloxbot.html)
[![PyPI Version](https://img.shields.io/pypi/v/pyrobloxbot?label=pypi%20package)](https://pypi.python.org/pypi/pyrobloxbot)
[![PyPI Downloads](https://img.shields.io/pypi/dm/pyrobloxbot)](https://pypi.python.org/pypi/pyrobloxbot)

A python library to control the roblox character and interact with game ui through keyboard inputs

This library uses ```pydirectinput``` to control the keyboard

It has a decorator to ensure that the roblox window is in focus before sending keyboard inputs

There is also a global failsafe that can be triggered using _**control + m**_ to avoid your bot getting out of control
-   The failsafe hotkey can be changed using `set_failsafe_hotkey`

    Example:
    ```python
    #Sets the failsafe hotkey to control + shift + y
    set_failsafe_hotkey("ctrl", "shift", "y")
    ```

If you have any issues while using the library, please reach out through my discord (mews75)

## Installation

Install pyrobloxbot using ```pip install pyrobloxbot```

## Usage/Examples

```python
import pyrobloxbot as bot

#Send a message in chat
bot.chat("Hello world!")

#Walk forward for 5 seconds
bot.walk_forward(5)

#Reset player character
bot.reset_player()
```

## [Documentation](https://pyrobloxbot.readthedocs.io/en/latest/pyrobloxbot.html)

## [Changelog](https://github.com/Mews/py-roblox-bot/blob/main/CHANGELOG.md)
