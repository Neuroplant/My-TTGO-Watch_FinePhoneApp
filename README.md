this is an Addon to https://github.com/sharandac/My-TTGO-Watch

### for Finding Watch

in "src/gui/mainbar/setup_tile/bluetooth_settings/bluetooth_settings.cpp"

add lines

Line 28:

```
#include "bluetooth_FindPhone.h"
```

Line 175:

```
bluetoothFindPhonetile_setup();
```

copy files in "bluetooth_settings" to "src/gui/mainbar/setup_tile/bluetooth_settings/"

### for Finding Phone

in "src/my-ttgo-watch.ino"

add Lines

Line 53:

```
#include "app/FindPhone/FindPhone.h"
```

Line 111:

```
FindPhone_setup();
```

copy folder "FindPhone" to "src/pp"
