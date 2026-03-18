Fanstel EV-BM15
###############

Fanstel EV-BM15 is an evaluation board based on the Nordic Semiconductor
nRF54L15 SoC.

Hardware
********

- SoC: Nordic nRF54L15
- CPU: Arm Cortex-M33
- Debug interface: SWD

Supported targets
*****************

- ``fanstel_ev_bm15/nrf54l15/cpuapp`` (Arm Cortex-M33)

Building
********

To build the sample application::

  west build -b fanstel_ev_bm15/nrf54l15/cpuapp samples/hello_world

Flashing
********

To flash the image to the board::

  west flash

Notes
*****

This board has been tested with nRF Connect SDK v3.2.2.

If the board files are located outside the Zephyr tree,
use the ``BOARD_ROOT`` CMake variable to specify the directory
containing the ``boards/`` folder.