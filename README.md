# Roblox Group-Based Product Whitelist System

A secure, server-sided whitelist and protection system for Roblox developers distributing private assets. This system uses Roblox group membership to verify buyers and protects the product from unauthorized access or tampering.

# Features

- Verifies if a player is in a specific Roblox group (optional: with a minimum rank)
- Destroys the product and kicks unauthorized users
- Includes a tamper-detection watcher that destroys the product and shuts down the game if the whitelist script is removed


# Setup Instructions

# 1. File Placement
Place the following scripts in `ServerScriptService`:
`Main WL Script`
`WL Tamper Detector`


## How to place the scripts?

### 1. Go into your Roblox project in Roblox Studio and go to ServerScriptService

Create a script named `WhitelistChecker` and Copy+Paste the code from `Main WL Script`.

Create one more script named `WhitelistWatcher` and Copy+Paste the code from the `WL Tamper Detector`.

