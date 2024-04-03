# Chapter 2 Notes
## Ex. 2.7
| Production | Semantic Rule |
| *seq* -> *seq* *instr* | *seq.x* := *seq.x* + *instr.x* & *seq.y* := *seq.y* + *instr.y* |
| *seq* -> **begin** | *seq.x* := 0 & *seq.y* := 0 |
| *instr* -> **east** | *seq.x* := 1 & *seq.y* := 0 |
| *instr* -> **north** | *seq.x* := 0 & *seq.y* := 1 |
| *instr* -> **west** | *seq.x* := -1 & *seq.y* := 0 |
| *instr* -> **south** | *seq.x* := 0 & *seq.y* := -1 |
