# ShellGrab
A terminal shellcode grabber. Uses shellstorm API for searching the database and requests module for grabbing the shellcode from the database.

## Example

`./shellgrab -s netcat`

Returns a colored and numbered list of available shellcodes in the shellstorm database. The numbers along the shellcode can be further used to grab the shellcode as:

`./shellgrab -s netcat -g 1`
