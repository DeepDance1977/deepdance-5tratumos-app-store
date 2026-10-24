
# DeepDance 5tratumOS App Store

Public app store repository maintained by DeepDance.

## Application

DeepDance BSV Solo is an independent project for the
Bitcoin SV ecosystem and 5tratumOS.

Repository:
https://github.com/DeepDance1977/deepdance-bsv-solo

Container package:
https://github.com/users/DeepDance1977/packages/container/package/deepdance-bsv-solo

## Development status

This repository currently contains an initial store integration draft.

The application is not yet a production-ready BSV solo mining solution.

The following mining components still need to be implemented
and tested:

- Stratum V1 server
- Mining job generation
- Share validation
- BSV coinbase construction
- Valid block submission
- End-to-end testing with ASIC miners

## Before public release

- Validate the manifests against the actual 5tratumOS store format.
- Verify ARM64 compatibility.
- Verify the published container image and its tag.
- Test installation, restart, update and removal.
- Verify node RPC connectivity and security.
- Complete and test the mining implementation.

Developer: DeepDance
