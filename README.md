# race-config

Race configurations for the [Slop Crew](https://github.com/SlopCrew/SlopCrew) server.

# How does it work ?

A race is a mode in which you have to pass through all the blue checkpoints. A ranking is established at the end, with participants ordered from the fastest to the slowest.

A race configuration (race config) is a JSON object containing:

- A stage ID
- The ordered positions of all the checkpoints in the race
- A starting position

To simplify the process of creating races, you can utilize [BRCreator](https://github.com/Fcornaire/BRCreator) which offers a Unity plugin to assist in generating the JSON configuration.
