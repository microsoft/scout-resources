# Microsoft Scout Resources

Resources for Microsoft Scout admins and users.

## Reducing approval prompts

If Scout is prompting too often, start with the macOS tenant policy profile in
`admins/microsoft-scout.mobileconfig` and set `ForcePrompt` to `false`. Then
use `DisabledPermissions` and `DisabledServers` only for the capabilities you
actually want to keep gated.
