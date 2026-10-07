---
name: echo-check
description: Checks that the everything MCP server of the dogfood plugin answers, and reports the plugin's settings.
---

# Echo check

When the user asks for an "echo check" or a "dogfood check":

1. Call the `echo` tool of the `everything` MCP server with the message `{{var:greeting}}`.
2. Reply with one line: the echoed text, then the settings in parentheses — mode `{{var:mode}}`,
   up to `{{var:max_items}}` items, verbose `{{var:verbose}}`.
