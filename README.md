# mbed-webserial-utility

The site can be accessed here: https://eddie-hunckler-dmc.github.io/mbed-webserial-utility/

Discussion can be accessed here: https://www.dmcinfo.com/blog/id/13661/customizing-the-embedded-serial-interface

## Functional Requirements

This inteface assumes a connected target running the mbde_os framework mbde-client-cli.
[code](features/frameworks/mbed-client-cli) 
[docs](https://os.mbed.com/docs/mbed-os/v6.16/mbed-os-api-doxy/ns__cmdline_8h.html)

The following macros must also be defined as follows.
```
#define MBED_CONF_CMDLINE_ENABLE_INTERNAL_COMMANDS 1
#define MBED_CONF_CMDLINE_USE_DUMMY_SET_ECHO_COMMANDS 0
```
