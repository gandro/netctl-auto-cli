netctl-auto-cli
===============

Command line interface for the netctl-auto service. It can be used to manage
wireless profiles when using the netctl-auto.service file from netctl.


    Usage: nacli {COMMAND} [PROFILE]
                 [--help|--version]
    
    Commands:
      list                 List available profiles
      current              List currently active profiles
      reconnect            Reconnect all interfaces
      disconnect           Disconnect all interfaces
      enable-all           Enable all profiles for automatic connection
      disable-all          Disable all profiles for automatic connection
      enable [PROFILE]     Enable a single profile for automatic connection
      disable [PROFILE]    Disable a single profile for automatic connection
      switch-to [PROFILE]  Switch to a profile, disable all others
