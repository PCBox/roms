# PCBox ROM repository

This repository contains all ROMs needed by the [PCBox](https://github.com/PCBox/PCBox) emulator. For development versions of PCBox, the recommended way to use this repository is to clone it instead of downloading the tagged releases.

Note that some ROMs in this repository may be for dev-branched machines and devices, meaning that they will not do anything on regular release builds. If you are confused why some device does not appear despite the ROM being present in the set, check that you are using an appropriate build of PCBox before reporting issues.

## Contributing ROMs
Before new ROMs can be accepted in this repository, the code that uses the ROMs needs to be in the upstream PCBox repository. Once you've made an PCBox pull request, open a pull request here. This applies to removals as well in inverse. 

Note that your ROM(s) will not be merged to master until the code is in PCBox master. However, if the development is happening in an upstream PCBox branch, a corresponding branch can be created here until the feature is ready for master.

## Committing guidelines
- Do not use vague commit messages.

  **Acceptable:**
  - "Add ASUS P2B-VM ROM"
  - "Remove ASUS P5B-VM ROM".

  **Unacceptable:**
  - "Add files via upload"
  - "Romset update"
  - "Delete ROM"

- Separate additions and removals to different commits.
- The subject line shouldn't be longer than 50 characters. If you're having trouble fitting what you did in the subject, consider splitting your changes to multiple commits. If you genuinely need to give a lot of background information and splitting is not appropriate, write it in the description.

If you make no effort to follow these guidelines, your contribution will not be merged until you correct highlighted issues. Don't be ashamed to ask for help if you've made a mistake and don't know how to correct it.

## Licensing for the Bochs VBE BIOS
The Bochs VBE BIOS comes from [this repo](https://github.com/bochs-emu/VGABIOS) and is under the LGPLv2.1.
