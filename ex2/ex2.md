# Exersice 2 : Install and test Slither for security checks

## Install Slither using pip

`pip3 install slither-analyzer`

Additional information and installation methods : https://github.com/crytic/slither/tree/master

### Install solc-select (if you do not have it already)

`pip3 install solc-select`

## Test Slither on the demo file in this repo

`solc-select install 0.8.0`
`solc-select use 0.8.0`
`slither token.sol`
