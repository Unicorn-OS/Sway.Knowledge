sch: https://www.google.com/search?q=manjaro+sway+disable+screen+lock

# Solution:
https://www.reddit.com/r/ManjaroLinux/comments/1iwpymi/cant_figure_out_how_to_turn_off_screen_locking_on/
>Well I just commented out the "set $locking" line in `/etc/sway/definitions` and then renamed `/etc/sway/idle.yaml` to idle.yaml.bak. Then restarted. That seemed to have been a ugly way to stop the screen locking, screen turn off and sleep.
