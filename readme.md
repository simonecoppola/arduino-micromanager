An updated version of Nico Stuurman's device adapter for Micro-Manager: https://micro-manager.org/Arduino

Specifically, it addresses the issue of increasing the max sequence length (previously hardcoded to 12) to take advantage of larger memory availability in current arduinos. In this adapter it is set to 256. Ideally it will be made dynamic one day, as per [this ticket on the Micro-Manager GitHub repo](https://github.com/micro-manager/mmCoreAndDevices/issues/512).

To use, just install the updated firmware on the Arduino and then copy and paste the .dll in the micro-manager directory, substituting the previous one.
