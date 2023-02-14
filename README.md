# Martingale experiment
The **Optional Stopping Theorem** would suggest that martingale betting would not actually lead to any real world profit, but requires the assumption that the player has a finite lifetime. Thus we don't need to run a simulation if the number of bets is fixed (because the theorem would already tell us the expected ending money is the same as the starting money. However, even if take off this condition and allow for an infinite lifetime (i.e. only stop on a win, thus invalidating Optional Stopping Theorem) BUT keep the finite money condition, this seems worth experimenting.

# Result
Even without betting limits (but still finite but large bankroll and no finite stopping) you're still expected to stay equal. Code can be found in `Martingale.ipynb`.
