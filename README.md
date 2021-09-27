# tsuduki

Tsuduki is an experimental language featuring first-class interrupts (i.e. algebraic effects) built on top of [Continuation Calculus](https://arxiv.org/abs/1309.1257) by Bram Geron and Herman Geuvers.

```
LHS ::= N | LHS.V
Exp ::== N | V | Rule | Exp.Exp
Rule ::= Rho.LHS.Exp
