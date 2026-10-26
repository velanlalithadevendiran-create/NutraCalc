# NutraCalc

A calculator for nutraceutical formulation. It converts label claims into the raw
material needed per unit, applying salt-form factor, overage and assay, and scales
the result to a batch size.

**Live demo:** https://velanlalithadevendiran-create.github.io/NutraCalc/

## Features
- Label claims in g, mg, mcg and IU
- 13 preloaded salt and mineral forms
- Overage and assay corrections
- Batch quantity in kg and excipient balance
- Daily dose check against a limit you enter

## Formulas
- Active to add (mg) = label claim x (1 + overage / 100)
- Factor = 1 / ((active in source / 100) x (assay / 100))
- Raw material (mg) = active to add x factor

## Roadmap
1. Tested calculation module with unit tests
2. Installable web app with saved formulas
3. Market-specific regulatory rules
4. Accounts and shared ingredient libraries

## Note
Verify conversion factors and limits against the current pharmacopoeia and the
regulations of the market you file in.
