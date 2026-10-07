# Marketplace Dogfood MCP

A test plugin for dogfooding the marketplace and the agent's plugin commands. It ships one MCP
server (`everything`, the public MCP example server) with two run modes — `npx` and `docker` —
and declares every kind of plugin variable: a required secret, an optional secret defaulting to an
environment variable, a string with choices, a number, a boolean and an optional string. The
server does nothing with the values; they exist so the agent's install and config flows have
something to ask for.
