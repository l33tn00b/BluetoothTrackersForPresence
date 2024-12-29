# BluetoothTrackersForPresence
Which Bluetooth Trackers to use for HomeAssistant/whatever Presence Detection
This is just a quick writeup / scratchpad for Bluetooth/BLE Trackers I've tried for local presence detection.

# Gigaset G-Tag/Keeper (2017)
Works fine, has a static MAC Address. Battery can be changed (3 Torx screws). Battery life approx. 1 year. HW lives much longer (quite a beast). Wish I had bought more of these.

# Chipolo One
May work. There's a report on the HA forums that pairing the tracker and removing it from the app while out out reach will leave the tracker active (haven't tested this).

# Chipolo One Point (2024)
Doesn't work. Will broadcast MAC only when activated (in pairing mode). If paired, will switch to MAC address randomization scheme as per Google's find my device network. AFAIK cannot be tricked into continuous broadcast mode.

# Tile Pro (2019)
Works like a charm. HW died as of 12/2024 (took quite some abuse being carried around all day, every day).

# Tile Pro (2020)
Works like a charm. 

# Tile EC-13001 (Mate 1-pack, 2018)
Exchangeable battery. Works fine. HW died after approx. 3 years (having been carried around every day).

# Tile EC-13004 (Mate 4-pack, 2019)
Exchangeable battery. Works fine. HW same as above.
