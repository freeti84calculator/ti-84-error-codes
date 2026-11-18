# TI-84 Error Codes — Complete List With Fixes

Every common **TI-84 error message** in plain English: what it means, why it happens, and how to fix it. Most of these take under a minute once you know what the code is telling you.

**Full guides with step-by-step fixes:** https://freeti84calculator.com/ti-84-error-codes/
**Practise the fixes safely:** [free TI-84 calculator online](https://freeti84calculator.com/) — no download, nothing on your own calculator at risk.

## First, read any error the right way

When an error screen appears you get two options:

- **1:Quit** — back to the home screen; your entry is discarded.
- **2:Goto** — the cursor jumps straight to the spot in your entry where the calculator thinks the problem is. This is almost always the fastest route to a fix.

Pressing **2nd + Enter** on the home screen recalls your last entry so you can edit it instead of retyping.

## The 25 errors

| Error | What it means | Most common cause |
|---|---|---|
| ERR:SYNTAX | The calculator cannot parse what you typed. | Unmatched parentheses, or using the minus key where the negation key (-) belongs. |
| ERR:DOMAIN | A function got an input outside its allowed range. | Square root or log of a negative number, or a probability outside 0 to 1. |
| ERR:INVALID DIM | A list or matrix has the wrong size for the operation. | Running stats or a plot on an empty list, or mismatched matrix dimensions. |
| ERR:DIM MISMATCH | Two lists used together have different lengths. | Running a regression or plot with lists of unequal length. |
| ERR:WINDOW RANGE | Your graphing window values do not make sense. | Xmin is not less than Xmax (same for Y), or Xscl/Yscl is set to 0. Quick fix: ZOOM → 6:ZStandard. |
| ERR:DATA TYPE | You fed a function the wrong kind of data. | Passing a list to a function that expects a single number, or vice versa. |
| ERR:BAD TOKEN | A character or keypress is not allowed where you put it. | Pressing variable or function keys in an invalid context, or leftover characters from a transferred file. |
| ERR:NONREAL ANS | The answer is a complex number, but the calculator is in Real mode. | Square root of a negative with a+bi off — switch MODE to a+bi if you want the complex answer. |
| ERR:ARGUMENT | A function or command got the wrong number or type of arguments. | Leaving out a required argument, or adding one the command does not accept. |
| ERR:MEMORY | Not enough free memory for the operation. | RAM or Archive is full — delete items or archive them via 2nd → MEM → Mem Mgmt/Del. |
| ERR:SINGULAR MAT | The matrix has no inverse because its determinant is 0. | Using the inverse key on a singular matrix while solving an equation. |
| ERR:NO SIGN CHG | The solver found no sign change in the interval you gave. | The function has the same sign at both bounds — widen the interval or change the guess. |
| ERR:STAT | A statistical calculation is invalid. | Running 1-Var Stats or a regression on an empty list, or on lists of different lengths. |
| ERR:OVERFLOW | The result is too large for the calculator to store. | Numbers beyond about 10^99 — break the calculation into smaller steps. |
| ERR:DIVIDE BY 0 | You divided by zero, or by an expression that equals zero. | A denominator variable or bracket that works out to 0. |
| ERR:BOUND | Your lower and upper bounds are in the wrong order. | Setting the solver bound so the left value is greater than the right. |
| ERR:INVALID | That command cannot be carried out there. | Referencing a variable, list or program in a context where it cannot be used. |
| ERR:UNDEFINED | You used a variable or list that has never been given a value. | Typing a list name that is empty, or a variable that was never stored. |
| ERR:MODE | A mode setting clashes with what you asked for. | An operation the current graphing mode (Func, Par, Pol, Seq) does not allow. |
| ERR:SCALE | The axis scale (Xscl or Yscl) is set to an unusable value. | Xscl or Yscl is 0, or too large for the window. |
| ERR:STAT PLOT | A stat plot is defined in a way the calculator cannot draw. | A plot points at an empty list or a list name that does not exist. |
| ERR:TOL NOT MET | The solver could not reach the requested accuracy. | A very tight tolerance with a rough guess — loosen the tolerance or improve the guess. |
| ERR:ITERATIONS | The solver gave up after too many tries. | No reachable solution from your starting guess — change the guess. |
| ERR:BAD GUESS | Your starting guess cannot be used. | The guess is outside the bounds, or lands where the function is undefined. |
| Validating OS (stuck screen) | Not an ERR code: the calculator is stuck checking its operating system. | An interrupted or corrupted OS update. |

## Full step-by-step fix guides

- [ERR:SYNTAX fix](https://freeti84calculator.com/ti-84-err-syntax-fix/)
- [ERR:DOMAIN fix](https://freeti84calculator.com/ti-84-err-domain-fix/)
- [ERR:INVALID DIM fix](https://freeti84calculator.com/ti-84-err-invalid-dim-fix/)
- [ERR:DIM MISMATCH fix](https://freeti84calculator.com/ti-84-err-dim-mismatch-fix/)
- [ERR:WINDOW RANGE fix](https://freeti84calculator.com/ti-84-err-window-range-fix/)
- [ERR:DATA TYPE fix](https://freeti84calculator.com/ti-84-err-data-type-fix/)
- [ERR:BAD TOKEN fix](https://freeti84calculator.com/ti-84-err-bad-token/)
- [Validating OS fix](https://freeti84calculator.com/ti-84-validating-os-fix/)
- [How to reset a TI-84](https://freeti84calculator.com/how-to-reset-ti-84/)
- [All TI-84 guides](https://freeti84calculator.com/guides/)

## When to reset (last resort, in this order)

1. Choose **2:Goto** and fix the flagged entry.
2. Press **ZOOM → 6:ZStandard** for graphing errors.
3. Clear RAM: **2nd → + → 7:Reset → 1:All RAM** — clears variables, lists and programs, but keeps the OS and apps.
4. Still misbehaving? Follow the [full reset walkthrough](https://freeti84calculator.com/how-to-reset-ti-84/).

## Disclaimer

freeti84calculator.com is an independent educational resource and is not affiliated with, endorsed by, or sponsored by Texas Instruments. TI-84 is a trademark of Texas Instruments.
