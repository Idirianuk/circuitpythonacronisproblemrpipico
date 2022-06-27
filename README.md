# circuitpythonacronisproblemrpipico
Describes a problem when using Circuitpython on an RPI Pico whilst having Arconis True Image installed.

When using any Board and Circuitpython under Windows 10 (tested), an Acronis process running called mms_mini.exe causes a continuous reboot loop on the board as there appears to be an access/read/write to the CPY drive. Disabling this service has little effect on Acronis under most circumstances.

See https://kb.acronis.com/content/65464 for info.
