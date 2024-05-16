# HW Scripts | Carlock

This resource provides a car locking system for your FiveM server, allowing players to lock and unlock their personal vehicles. The system supports ox_target integration and includes various configuration options such as notifications, sounds, and logs.

## Features
- Lock and unlock personal vehicles.
- Visual and auditory feedback for locking/unlocking actions.
- ox_target integration for interactive vehicle locking.
- Configurable notifications and sounds.
- Logging system with webhook support for Discord.

## Requirements
- [es_extended](https://github.com/esx-framework/es_extended) (ESX)
- [mysql-async](https://github.com/brouznouf/fivem-mysql-async)
- [ox_target](https://github.com/overextended/ox_target) (optional, for target support)

## Usage
- Command: Players can lock or unlock their vehicles using the configured command (default: carlock). The default key mapping is L.
- Target Integration: If ox_target support is enabled, players can interactively lock/unlock vehicles by targeting them and selecting the appropriate option.

## :wrench: Download & Installation
Follow these steps to set up the script on your ESX server:

1. **Download the Files**: Download the script files from the provided source.
2. **Copy to Server Resource Directory**: Place the `hw_carlock` folder in the server resource directory.
3. **Update `server.cfg`**: Add the following line to your `server.cfg` file:
    ```cfg
    start hw_carlock
    ```
4. **Start Your Server**: Restart or start your ESX server to load the `hw_carlock` resource.

If help is needed, you can contact me via Discord. A link for that will be provided in the console upon restarting the script. Alternatively, you can search for HenkW00 on Google, GitHub, or CFX.

Enjoy the script, and I hope you find it useful! ❤️
