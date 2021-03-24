# circuitpythonacronisproblemrpipico
Describes a problem when using Circuitpython on an RPI Pico whilst having Arconis True Image installed.

When using an RPI Pico and Circuitpython under Windows 10, an Acronis process running as mms_mini.exe causes a continuous reboot loop on the Pico as there appears to be an access/read/write to the RPI drive. Disabling this service has little effect on Acronis under most circumstances.

See https://kb.acronis.com/content/65464 for info.
