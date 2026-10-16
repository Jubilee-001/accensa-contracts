# Roadmap

## Issue #443: stACC liquid staking derivative minting

- [x] Implement stACC liquid staking derivative minting (#443)
  - New `liquid_staking` module in `contracts/governance/src/liquid_staking.rs`
  - 1:1 mint/burn of stACC against locked underlying tokens
  - Exchange rate progression and lock-epoch-based redemption
  - CHANGELOG.md entry added

## Issue #646: DailyLimitSet event coverage on limit set and clear

- [x] Assert the `DailyLimitSet` event on limit set and clear (#646)
  - New XDR event tests in `contracts/multisig-account/src/limits.rs`
  - Pins set, overwrite, clear (`limit == 0`) and the no-event rejection