# GenLauncher

## How to add and update your mod:

#### Create a PR to `Mods.yaml` with a link to your mod.
    1. PR example for Zero Hour mod:
        ```yaml
        Mod:
          MyAwesomeMod:
            link: http://awesome-mod.com/Mod.yaml
        ```
        
    2. PR example for an addon to existing mod:
        ```yaml
        Mod:
          MyAwesomeMod:
            CommmunityPatch:
              link: http://awesome-mod-patch.com/Mod.yaml
        ```
#### Create a file `Mod.yaml` in your github repository or your webpage, with link to `.zip`, containing the mod's `.big` files.
    1. `Mod.yaml` example:
         ```yaml
         link: http://awesome-mod.com/BigFiles.zip
         version: 1.0.0
         ```

#### Updating your mod is simple and does not require any additional PRs:
    1. Modify your files in `http://awesome-mod.com/BigFiles.zip`.
    2. Bump the version in `http://awesome-mod.com/BigFiles.zip`.

Congratulations. Now everyone can see and use your mod!
