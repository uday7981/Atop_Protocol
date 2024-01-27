# Storage

![Compatibility](https://img.shields.io/badge/compatibility-0.6.25-blue)

This example provides a few basic functions to store and retrieve user asset.

## Prerequisites

Verify the following before running this demo:

*  You have downloaded and installed the [DFINITY Canister
   SDK](https://sdk.dfinity.org).

*  You have stopped any Internet Computer or other network process that would
   create a port conflict on 8000.

*  For specific tutorials, please visit [here](https://sdk.dfinity.org/docs/rust-guide/rust-quickstart.html).

## Demo

1. Start a local internet computer.

   ```text
   dfx start
   ```

2. Open a new terminal window.

3. Reserve an identifier for your canister.

   ```text
   dfx canister create all
   ```

4. Build your canister.

   ```text
   dfx build
   ```

5. Deploy your canister.

   ```text
   dfx canister install all
   ```
