# Unprocedural

About

Forum thread:
License:

## Installation

### Dependencies

### Manual Steps

- Delete `GameData\RealismOverhaul\RO_SuggestedMods\Bluedog_DB`

## Notes

### Changes from SkyPhoenix999's RO Configs

- The Vanguard second stage (Able) is sized down to 0.76m (should be 0.84m) in order to maintain BDB's proportions so that interstage works properly. Since Thor-Able is scaled up to 1m (again from 0.84m) to fit on Thor, there's an unrealistic jump in size between two stages that should be identical. But hey, they both look pretty sitting on top of their respective boosters!
- Specific Changes:
  - Rescale Vanguard Second Stage in `RO_Vanguard.cfg` and `RO_Vanguard_SAF.cfg`
  - Rescale `bluedog_Vanguard_GE405` to match the 1.14m version in ROEngines.
  - Fix a duplicate part edit in `RO_Able_SAF.cfg` to create a new `bluedog_Able_Fairing_SAF` part instead.
  - Fix a duplicate part edit in `RO_GeneralBDB_SAF.cfg` to create a new `bluedog_generic_FairingBase_1p25m` part instead.

### Duplicate Parts

- Most engines will be pruned by ROEngines. Engines with unique models (ie. shrouds that RO expects you to build yourself) are preserved by the patches in `SaveEngines.cfg`.

- Some configs only apply when ROCapsules is not installed.
