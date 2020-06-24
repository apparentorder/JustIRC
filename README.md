![PyPI](https://img.shields.io/pypi/v/JustIRC)
![License](https://img.shields.io/github/license/gkbrk/JustIRC)

# What is JustIRC
JustIRC is a single-file IRC library that allows you to write simple IRC bots
without having to deal with large frameworks. It's designed to be simple rather
than feature-rich. That doesn't mean it doesn't have the necessary feautures for
an IRC bot though.

[Documentation](https://justirc.readthedocs.io/en/latest/)

JustIRC is

* Event-based.
* Handles pings automatically so you don't have to
* Written in pure Python. Uses sockets instead of heavy frameworks.
* Has simple functions for most IRC functionality. You don't have to touch a
  line of socket code.

# Examples
* [ParrotBot](examples/parrotbot.py) - A bot that replies to you with the same message, just like a parrot.  
* [HelloBot](examples/hellobot.py) - A bot that greets people who say "Hi" or "Hello".  
* [WeatherBot](examples/weatherbot.py) - A bot that responds to "!weather Istanbul" with the current weather.  
* [TitleBot](examples/titlebot.py) - A bot that responds with the titles of URLs
  posted to the channel.

# Documentation and Examples
The library is quite new so I haven't found the time to document it yet. I will
try adding some examples soon.
