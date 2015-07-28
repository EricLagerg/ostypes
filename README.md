# ostypes
A very stupid (but basically the only) way to determine the HOST_OPERATING_SYSTEM like GNU does it.

Basically, use it like this:

//go:generate ostypes

And then access the result using the variable, 'HostOS'.