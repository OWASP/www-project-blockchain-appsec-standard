# Social Engineering on the Blockchain


## Common Targets and Attacker Incentives

Attackers use social engineering, because people and processes are the easiest route to secrets, keys and privileged tooling. Targets include maintainers, developers, DevOps/CI, customer-support staff, exchange employees and end users. The result is theft of funds, code-supply-chain compromises, loss of access to admin tools, or persistent backdoors in software dependencies.
Attacker incentives may include the following. 

* **Direct theft of crypto:** Move funds from hot wallets, bridges, or exchanges to attacker addresses.
**Long-term access / espionage:** get ongoing access to private keys, CI secrets, or proprietary code (useful for later theft or extortion).
* **Supply-chain leverage:** Compromise a widely used package or build pipeline so malicious code propagates broadly.
* **Market manipulation & reputation attacks:** publish false info or take over high-profile accounts to move markets or erode confidence.

These incentives map directly to attacker tactics: short, noisy coups to cash out vs. stealthy persistence to escalate later.


## Attack Surface Analysis

The attack surface for social engineering attacks on the blockchain consists largely of the following.  
* Email and spear-phishing (fake invoices, support requests, credential-recovery links).
* Voice (vishing) and SMS scams—operators or carriers tricked into SIM porting, or staff persuaded to provide OTPs.
* Impersonation of infrastructure vendors (CI/CD, npm, GitHub, wallet vendors) to request “urgent” credential re-auth.
* Compromised or malicious open-source maintainers — attackers either take over maintainer accounts or convince maintainers to accept malicious dependences/PRs.
* Insider recruitment / job scams — fake job offers to entice access or trick interviewees into running code.
* Physical parcels — fake hardware wallets or trojanized devices sent to known users.


## Examples in the News

There have been many hacks covered in the news that have involved some combination of cryptocurrency payments / accounts and social engineering techniques. Below are some examples. 
* **Twitter (July 2020):** Attackers used coordinated social-engineering against Twitter employees to gain access to internal admin tools and hijack many verified accounts to post a bitcoin scam. This shows how targeting a small number of staff with internal privileges can produce a high-impact crypto scam. 
* **SIM-swap / carrier attacks (multiple cases, high dollar losses):** Criminals social-engineer mobile carriers or the account recovery process to port phone numbers and intercept 2FA, leading to multi-million dollar crypto thefts (notably cases brought to courts and civil suits for tens of millions). SIM swapping remains a frequent enabling step for attackers stealing exchange or wallet access. 
* **Ledger follow-ups & hardware-wallet scams:** After Ledger’s data breach (customer contact details leaked), attackers launched highly convincing phishing and even mailed fake hardware wallets to victims designed to steal seed phrases. This highlights how leaked user data enables targeted social engineering. 
* **Open-source maintainer takeover:** Event-stream/npm (2018) — attackers gained control of an npm package’s maintainer role (or its dependency) and published malicious code that later affected a Bitcoin wallet (Copay). That incident is a classic example of leveraging trust in maintainers to inject malware into the supply chain. 
* **Recent platform account compromises tied to phone/2FA social engineering:** For example, a high-profile account for the SEC on X was briefly compromised in Jan 2024 through social engineering of phone/2FA recovery, causing market impact. This shows even regulatory accounts are vulnerable and that social engineering can produce market moves. 



## How to protect against social engineering attacks

Protecting against social engineering primarily relies on vigilance and skepticism, as it targets human behavior.

* **Be suspicious of urgent requests:** Scammers use fear, urgency, and greed to get you to act impulsively. Always verify requests independently, even if they appear to come from a trusted source.
* **Verify sources:** Never click on links in unexpected emails or messages. If a message from an exchange or wallet provider seems suspicious, go directly to their official website by typing the URL yourself.
* **Enable strong authentication:** Use hardware security keys (physical security tokens) for multi-factor authentication (MFA) instead of SMS or authenticator apps, which are more susceptible to SIM-swapping attacks.
* **Safeguard your wallet:** Never share your private keys, seed phrase, or recovery phrase with anyone. Legitimate support staff will never ask for this information. Consider using a hardware wallet for cold storage of your assets.
* **Educate yourself:** Stay up-to-date on the latest scams and tactics. Many legitimate platforms and security firms publish articles on emerging threats.
* **Use caution with third-party apps:** Be wary of browser extensions or other software that require access to your wallet or personal information. Only use reputable, well-vetted applications.
* **Check wallet addresses carefully:** Always double-check the recipient's wallet address before sending a transaction, especially if you are copy-pasting from a transaction history. The address poisoning scam preys on inattention. 

## Related Articles

* ACM - [Exploiting the Human Factor: Social Engineering Attacks on Cryptocurrency Users](https://dl.acm.org/doi/10.1007/978-3-030-50506-6_45)
