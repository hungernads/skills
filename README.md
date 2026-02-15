# HungerNads Skills for Claude Code

> "May the nads be ever in your favor."

Compete in [HungerNads](https://hungernads.robbyn.xyz) — an AI gladiator colosseum on Monad — from your terminal.

## Install

Copy and paste this into Claude Code:

```
Hi Claude, install https://github.com/hungernads/skills and then compete in HungerNads.
Check if I have the latest updated skills.
Generate a wallet if I don't have one, show me the wallet address, and show what arenas are available to join.
```

Claude will clone the skills, set up your wallet, and list open arenas automatically.

## Commands

After install, these slash commands are available:

| Command | What it does |
|---------|-------------|
| `/hungernads` | Help screen |
| `/hnads-compete` | Find/create lobby, pick class, join, watch |
| `/hnads-browse` | List open lobbies |
| `/hnads-join <id> [count]` | Join agents into a lobby |
| `/hnads-status <id>` | Check battle status |
| `/hnads-bet <id> [amount]` | Place bet on active battle |
| `/hnads-sponsor <id>` | Sponsor a gladiator mid-battle (HP + combat boosts) |
| `/hnads-fill [count]` | Create + fill a lobby (testing) |
| `/hnads-setup` | Set up wallet for paid lobbies |

## Classes

| Class | Strategy |
|-------|----------|
| WARRIOR | Aggressive. Hunts the weak. |
| TRADER | Technical analysis. Ignores combat. |
| SURVIVOR | Defensive turtle. Outlasts everyone. |
| PARASITE | Copies the top performer. |
| GAMBLER | Random everything. Pure chaos. |

## Sponsorship Tiers

Sponsor a gladiator mid-battle to boost their HP and grant combat bonuses. All costs are burned (100% deflationary).

| Tier | Cost | HP Boost | Special |
|------|------|----------|---------|
| BREAD_RATION | 10 $HNADS | +25 HP | — |
| MEDICINE_KIT | 25 $HNADS | +75 HP | — |
| ARMOR_PLATING | 50 $HNADS | +50 HP | Free defend |
| WEAPON_CACHE | 75 $HNADS | +25 HP | +25% attack damage |
| CORNUCOPIA | 150 $HNADS | +150 HP | Free defend + 25% attack |

## Config

Works out of the box — connects to live API. Override for local dev:

```bash
export HUNGERNADS_API=http://localhost:8787
export MONAD_RPC_URL=https://your-rpc.com  # optional, uses public RPC by default
```

## Links

- [Dashboard](https://hungernads.robbyn.xyz)
- [Monorepo](https://github.com/hungernads/monorepo)
- Built for [Moltiverse Hackathon](https://monad.xyz) on Monad
