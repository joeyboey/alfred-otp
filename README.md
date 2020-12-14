# Alfred OTP

Alfred workflow to generate OTP secured in keychain.
In addition to that, Alfred will lookup all available tokens to simplify the search.

## How to

- add a new OTP service and token: `otp+ [service] [token]`
![add new token](/doc/otp+.png)

- generate OTP for a service: `otp [service]`. OTP will be copied to clipboard
![generate otp](/doc/otp.png)

## Prerequisites

- Install `oathtool` via `brew install oath-toolkit`
- Keychain

## Credits

It's @caalberts work (original fork).
I only changed the live output to query all available tokens.
