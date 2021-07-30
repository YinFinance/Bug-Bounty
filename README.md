# Bug-Bounty
A bug bounty program for Yin Finance’s smart contracts is now live. We intend for hackers to look for smart contract vulnerabilities in our system that can lead to loss of funds or locked components.
## Rewards

Vulnerability reports will be scored using the CVSS v3 standard. The reward amounts for different types of vulnerabilities are:
⚡️ Critical (CVSS 9.0–10.0)
→ $5,000 - $50,000
⚠️ Major (CVSS 7.0–8.9)
→ $2,500 - $5,000​
🔔 Medium (CVSS 4.0–6.9)
→ $1,000 - $2,500
💣 Low (CVSS 1.0–3.9)
→ $500 - $1,000

Rewards will be awarded at the sole discretion of Yin Finance AG. Quality of the report and reproduction instructions can impact the reward. Rewards are denominated and paid out in USD. If both parties agree, rewards can also be paid out in crypto.

For this initial bug bounty program, there is a maximum bounty pool of $250,000.

Please responsibly disclose any findings to the development team, following these instructions:

## Emails report

In order to report a vulnerability, please write an email to security@yin.finance with [SECURITY DISCLOSURE] in the subject of the email.
We will make our best effort to reply in a timely manner and provide a timeline for resolution.
Please include a detailed report on the vulnerability with clear reproduction steps. The quality of the report can impact the reward amount.
## Github issuse report

Failure to do so will result in a finding being ineligible for any bounties.

## Scope
* In scope for the bug bounty are all the smart contract components of the Yin Finance protocol. They can be found in the following repositories:
* https://github.com/YinFinance/CHI
* https://github.com/YinFinance/YANG
* Any frontend applications or client-side code interacting with the contracts, as well as testing code.
* Mismatch of the functionality of the contracts and outdated spec documents.

## These are some examples of vulnerabilities that would be interesting:

* Stealing tokens or manipulating the token generation process.
* Locking or freezing any of the Yin Finance contracts.
* Griefing attacks: is it possible to block liquidations, redemptions, borrower operations, rewards distributions, etc?
* Do the desired constraints on borrower operations hold?
* Flash loan exploits
* YIN token exploits involving the Lockup Contracts

##  Resources
* YIN README(WIP)

## Terms for eligible bounties:

* Only unknown vulnerabilities will be awarded a bounty; in case of duplicate reports, the first report will be awarded the bounty.
* Public disclosure of the vulnerability, before explicit consent from Yin Finance AG to do so, will make the vulnerability ineligible for a bounty.
* Attempting to exploit the vulnerability in a public Ethereum network will also make it ineligible for a bounty.
