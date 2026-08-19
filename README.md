Receipts
You get a receipt for a $5 cup of coffee. Why not for $20,000 of financial advice?
Receipts turns an advisory fee percentage into a printed receipt — the annual dollar cost, what that works out to per day, which services you actually received last year, and a short list of questions to bring to your next meeting.
It does not tell you whether your advisor is worth it. That is not a question a calculator can answer.
Try it
→ Open Receipts
How it works
You enter three numbers. Everything else is arithmetic you could do on a napkin:
```
advisory cost           = portfolio value × advisory fee rate
investment expense cost = portfolio value × weighted average expense ratio
total annual cost       = advisory cost + investment expense cost

monthly = annual / 12      weekly = annual / 52      daily = annual / 365
```
If you estimate how many hours of direct professional time you received, Receipts also divides the annual total by those hours. That figure is labeled carefully and carries a disclosure, because an advisory fee covers portfolio management, planning, technology, staff, compliance, trading and monitoring in addition to time spent with you. It is a comparison tool, not an hourly billing rate.
Privacy
Your entries are calculated in your browser and never sent anywhere. There is no account, no database, no analytics, and no third-party scripts. The entire application is one HTML file with no network requests of any kind.
The web host that delivers the page records ordinary access logs when it loads — IP address, browser, timestamp — as every website does. It never sees what you type.
Don't take our word for it. That is the reason this repository is public. Open `index.html` and search it for `fetch`, `XMLHttpRequest`, `script src`, or `http`. You will find none of them. The privacy claim is verifiable in about two minutes by anyone who can read.
Design principles
Receipts is built to be fair to advisors as well as useful to consumers.
Every number is reproducible. If you cannot rebuild a figure with a basic calculator from inputs you can see, it does not ship.
Unused is not wasted. Some services are on-demand by nature. A financial plan you did not need this year is not a service you were cheated out of.
Automated is not worthless. The classification question exists for transparency about how work was delivered, not to assign a discount.
Questions, not accusations. Every prompt is framed to open a conversation rather than presume wrongdoing.
No invented benchmarks. Receipts ships no market-rate comparisons, because trustworthy sourced ranges have not been established. An unsourced number is worse than no number.
Accessibility
Keyboard operable throughout, with visible focus states and semantic form labels. Errors are marked with a printed `>>` rather than color alone. Readable at 320px. Honors `prefers-reduced-motion`, which removes the print animation and its timing delays entirely.
Contributing
Corrections to the arithmetic, the disclosures, or the framing are especially welcome — including from financial advisors. If a figure reads as unfair or lacks context an advisor would reasonably want, open an issue and say so specifically.
Disclaimer
Receipts is an educational tool. It is not financial, legal, or tax advice, and it does not evaluate any particular firm or advisor. All figures are estimates derived entirely from values you enter, which Receipts does not verify.
