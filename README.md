# Tiny Stack VM — exact ISA interpreter

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Endangdanngz/tiny-stack-vm-20261122/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Endangdanngz/tiny-stack-vm-20261122/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

## About this entry

`main.ts` is a complete interpreter for make.fun's tiny stack ISA, matching
the reference VM rule for rule: wrapping 32-bit arithmetic with exact
multiplication, signed and unsigned division and remainder, 5-bit-masked
shifts, sign-extended PUSH8, all ten traps with their own exit codes, the
step and output limits, and trap-kept output. It answers every instance
under the input directory with `stdout.bin` and `exit.txt`. No
dependencies; Node 22 runs it as it stands.
