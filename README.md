netctl-auto-cli
===============

Command line interface for the netctl-auto service. It can be used to manage
wireless profiles when using the netctl-auto service, which is part of netctl.


    Usage: nacli {COMMAND} [PROFILE]
                 [--help|--version]
    
    Commands:
      list                 List available profiles (active='*', disabled='!')
      current              List currently active profiles
      switch-to [PROFILE]  Switch to a profile, enable it if necessary
      enable [PROFILE]     Enable a single profile for automatic connection
      disable [PROFILE]    Disable a single profile for automatic connection
      enable-all           Enable all profiles for automatic connection
      disable-all          Disable all profiles for automatic connection


