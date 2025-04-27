# Prisoner's Dilemma Strategy

This strategy is for the Iterated Prisoner's Dilemma. It analyzes the opponent’s behavior over time and tries to classify their strategy (e.g. Tit-for-Tat, Grim Trigger, Pavlov, Always Defect, Random, etc.).

## Logic Summary

- **Round 1**: Always cooperate.
- **Last round**: Defect, if total rounds are known.
- **Pattern detection**: Matches over 25 known strategies using heuristics.
- **Response**: Reacts based on detected behavior (e.g., mirrors Tit-for-Tat, punishes defectors, cooperates with cooperators).
- **Fallback**: Defaults to defect if no clear pattern is found and opponent defected last.

