# Stella's ARB STIP Info

This repository store static files for Stella's ARB STIP info: ARB rewards data for lending and strategy in each period.

## Lending Reward
Show amount of ARB STIP reward being distributed to each Stella's lending pool in each period.

JSON File: [lending-reward.json](https://raw.githubusercontent.com/stellaxyz/arb-stip-info/main/reward/lending-reward.json)

Schema:
```typescript
[ 
  {
    "period": number,
    "startTimestamp": number,
    "endTimestamp": number,
    "amount": number,
    "poolAddress": string
  }
]
```


## Strategy Reward
Show amount of ARB STIP reward being distributed to Stella's strategy in each period.

JSON File: [strategy-reward.json](https://raw.githubusercontent.com/stellaxyz/arb-stip-info/main/reward/strategy-reward.json)

Schema:
```typescript
[ 
  {
    "period": number,
    "startTimestamp": number,
    "endTimestamp": number,
    "amount": number
  }
]
```

