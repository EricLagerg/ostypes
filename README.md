# ostypes
A very stupid (but basically the only) way to determine the HOST_OPERATING_SYSTEM like GNU does it.

Basically, use it like this:

`//go:generate ostypes name`

Where `name` is the name of your package (e.g., main). 
Yeah. I'm that lazy that I didn't figure it out myself. OH WELL.
You'll live.

Access the result using the variable, 'HostOS'.
(Obviously using a package prefix if needed.)