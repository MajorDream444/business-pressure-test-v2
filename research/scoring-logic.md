# Scoring Logic Research

## Baseline

Business Pressure Test V2 should use a 0 to 100 score.

The score should map to a diagnosis band and later support leak detection and MOBS routing.

## Bands

```text
0-25    Critical
26-50   Leaking
51-75   Functional But Capped
76-100  Ready To Scale
```

## Minimum Sprint 1 Output

- total score
- diagnosis band
- short diagnosis summary
- pressure points
- next moves

## Future Sprint 3 Output

- primary leak
- secondary leak
- recommended MOB
- recommended build
- blueprint recommendation

## Guardrail

The scoring model should be simple enough for a founder to understand and stable enough for Airtable capture later.
