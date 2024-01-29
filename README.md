# UDS Protocol manipulation by using c++

The UDS protocol is performed in a client-server relationship - with the client being a tester-tool and the server being a vehicle ECU.
For example, you can connect a CAN bus interface to the OBD2 connector of a car and send UDS requests into the vehicle. the targeted ECU will respond accordingly.

This enables various use cases:

    -Read/clear diagnostic trouble codes (DTC) for troubleshooting vehicle issues
    -Extract parameter data values such as temperatures, state of charge, VIN etc
    -Initiate diagnostic sessions to e.g. test safety-critical features
    -Modify ECU behavior via resets, firmware flashing and settings modification
