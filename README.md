# Roblox Group-Based Product Whitelist System

A secure, server-sided whitelist and protection system for Roblox developers distributing private assets. This system uses Roblox group membership to verify buyers and protects the product from unauthorized access or tampering.

# Features

- Verifies if a player is in a specific Roblox group (optional: with a minimum rank)
- Destroys the product and kicks unauthorized users
- Includes a tamper-detection watcher that destroys the product and shuts down the game if the whitelist script is removed


# Setup Instructions

# 1. File Placement

Place the following scripts in `ServerScriptService`:
