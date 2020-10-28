# Code to go in `pack.mcmeta`

```json
{
    "pack": {
      "pack_format": 6,
      "description": "Something interesting"
    }
}
```

- Replace `6` with a number corrosponding with the version of Minecraft your pack is for.
- Replace `Something interesting` with a short description of your pack. It will be shown in the tooltip of your pack in `/datapack list` and in the Datapack GUI.

## `pack_format` values

- 1.13.x: `3`
- 1.14.x: `4`
- 1.15.x: `5`
- 1.16.2 to 1.16.4: `6`

## Troubleshooting

- CHeck jour JSON syntax for errors (<https://jsonlint.com>)
