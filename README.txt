TradeTrack PWA — upgraded mobile version

This is an installable Progressive Web App package, not a compiled APK.

UPDATE YOUR EXISTING GITHUB REPOSITORY
1. Extract this ZIP on your phone.
2. Open your GitHub repository (TradeTrack).
3. Upload the files in this folder to the repository root, replacing the existing files with the same names.
4. Commit the changes. GitHub Pages will redeploy automatically.
5. On your phone, open https://zianimous.github.io/TradeTrack/ and refresh. If the old version remains, close the installed app/browser tab and reopen it after a minute.

Features:
- Mobile-first interface with Overview, Firm Rules, Journal, Daily Plan and Settings.
- Multiple accounts with separate balances, rule assumptions, assets, notes and journals.
- Alpha Direct rule reference: 5% trailing max drawdown, 3% daily loss, 1% open risk per asset, 10-minute same-direction re-entry chain, restricted news window, no weekend holds, no EAs, trade duration requirements, inactivity, lot exposure, 3% payout buffer + 1% extra, 15% best-day rule and 90% split.
- Manual per-asset open-loss monitor, drawdown estimates, best-day consistency and trade-duration estimates.
- Daily checklist, personal goals, journal, JSON backup/restore.
- Offline cache after first successful visit.

Important limitations:
- No live connection to Alpha Capital or your broker. You must manually update balance, equity, daily starting figures, and open floating losses.
- The app cannot identify the firm's restricted news instruments/releases, execute orders, or guarantee that a rule breach is prevented.
- Alpha Capital's current help-centre rules are linked inside the app. Your own account agreement/dashboard takes priority if its terms differ.
- Tracker calculations are estimates based on entered data; commissions, swaps, slippage and floating P/L must be included where applicable.
- Data is stored in this browser on this device. Export backups regularly.
