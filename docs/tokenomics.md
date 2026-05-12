# $ROBO Tokenomics

## Token Overview

| Parameter | Value |
|-----------|-------|
| **Name** | RoboLayer |
| **Symbol** | $ROBO |
| **Network** | Base (ERC-20) |
| **Total Supply** | 100,000,000,000 |
| **Decimals** | 18 |

## Allocation

| Category | Tokens | Percentage | Vesting |
|----------|--------|-----------|---------|
| Operator Rewards | 40,000,000,000 | 40% | Emitted over 4 years (halving every 12 months) |
| Ecosystem & Grants | 20,000,000,000 | 20% | 12-month cliff, 36-month linear vesting |
| Team & Advisors | 15,000,000,000 | 15% | 12-month cliff, 24-month linear vesting |
| Liquidity Provision | 10,000,000,000 | 10% | Unlocked at TGE |
| Treasury | 10,000,000,000 | 10% | Governance-controlled, 48h timelock |
| Public Sale | 5,000,000,000 | 5% | Unlocked at TGE |

## Emission Schedule

Operator rewards follow a halving schedule:

| Year | Annual Emission | Daily Emission |
|------|----------------|----------------|
| Year 1 | 16,000,000,000 | ~43,835,616 |
| Year 2 | 12,000,000,000 | ~32,876,712 |
| Year 3 | 8,000,000,000 | ~21,917,808 |
| Year 4 | 4,000,000,000 | ~10,958,904 |

## Token Utility

1. **Staking**: Operators must stake $ROBO to participate in task execution
2. **Task Rewards**: Operators earn $ROBO for completing tasks
3. **Governance**: Token holders vote on protocol parameters
4. **Fee Payment**: Task submitters pay fees in $ROBO
5. **Slashing Collateral**: Staked tokens are slashed for misbehavior

## Fee Structure

| Action | Fee |
|--------|-----|
| Task submission | 0.1% of reward value |
| Operator registration | 100 $ROBO (burned) |
| Unstaking (early) | 1% penalty (redistributed to other stakers) |

## Deflationary Mechanisms

- Registration fees are burned
- 50% of protocol fees are burned
- Slashed tokens are partially burned (50% burned, 50% to reporters)

## Governance

Token holders can vote on:
- Minimum stake requirements
- Slash rates
- Reward distribution parameters
- Protocol upgrades (with timelock)
- Treasury spending proposals

Governance uses conviction voting with a 3-day minimum lock period.
