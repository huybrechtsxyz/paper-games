# Paper Games

Small solo games you play with **pen, paper and a set of dice**. No board, no screen and little material, so they are easy to play before bedtime, on a train or on a rainy afternoon.

## Games

| Game | Description | Dice |
|---|---|---|
| [Paper Dungeon](games/paper-dungeon.md) | Draw a dungeon one octagon at a time. Fight monsters, find items and look for the superschat | d4, d6, d8, d10, d12, d20 |
| Paper Trail | A journey game inspired by the Oregon Trail. *Coming soon* | d4-d20, percentile die |

## What you need

- Pen or pencil
- Graph paper (plain paper works too)
- A standard set of polyhedral dice: d4, d6, d8, d10, d12, d20 (and a percentile die for some games)

## Repository layout

```
paper-games/
├── README.md
├── LICENSE
├── .gitignore
├── CONTRIBUTING.md
├── games/
│   └── paper-dungeon.md      # full rules and tables
└── tools/
    └── paper-dungeon-tables.xlsx   # all tables with odds, for tweaking the balance
```

The spreadsheet in `tools/` holds the same tables as the rules. The ranges are editable, and the chances and the check cells recalculate, so you can see what a change does to the balance.

## Contributing

Ideas for new monsters, items or whole games are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

Released under the [MIT License](LICENSE).
