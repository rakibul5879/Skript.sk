# Compatibility

Skript.sk targets a range of Minecraft server environments where practical, but compatibility must be established per script.

## What Every Script Must Report

| Field | Required Information |
|---|---|
| Minecraft | Exact version(s) tested |
| Server | Software and exact version |
| Java | Runtime version, when relevant |
| Skript | Exact version |
| Addons | Names and exact versions |
| Status | Tested, untested, or incompatible |

## Compatibility Rules

- Do not infer compatibility from a Minecraft version alone.
- Skript syntax and addon APIs can change between releases.
- Legacy forks and modern Skript builds may behave differently.
- Mark an environment as **untested** until the script has been run there.
- Record known errors and workarounds.

## Compatibility Variants

When one implementation cannot reasonably support both legacy and modern environments, keep separate variants under the appropriate `compatibility/` subdirectory.

Explain the differences between variants.
