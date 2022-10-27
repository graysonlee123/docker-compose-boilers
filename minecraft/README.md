# Spigot and Autopause

Spigot runs its own Watchdog which needs to be disabled when using Autopause functionality. Set `timeout-time` in `spigot.yml` to `-1` ([more information](https://www.spigotmc.org/wiki/spigot-configuration/)).
