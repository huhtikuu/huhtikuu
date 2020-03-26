# huhtikuu
GSM scanner for raspberry pi. Just a proof of concept.

## Getting started

* Download huhtikuu. It is easy on a command line via curl:

`
curl -L https://github.com/huhtikuu/huhtikuu/releases/download/v1.0.1/huhtikuu -o huhtikuu
`

* run `chmod +x huhtikuu` to make it executable
* run `./huhtikuu init` to prepare your raspberry. It will take some minutes
* move to a location with no bluetooth and wifi devices nearby
* run `./huhtikuu scan` to start scanning for SMS messages
