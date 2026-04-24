<div align="center">
  <img src="{LOGO_PATH}" alt="Logo" width="400" style="display: block; margin: 0 auto;">
  
  **{FIRM_NAME}**
  *When trustless fails, we don't!*
  
  ---
  
  ### {PROJECT_NAME} Security Review
  **Version 1.0**
  
  ---
  
  **Conducted by:**  
  **{AUDITOR_NAME}**  
  {ROLE}  
  {FIRM_NAME}  
  {START_DATE} – {END_DATE}
  
  ---
  
  *This report contains confidential information and is intended solely for the client. Unauthorized distribution is prohibited.*
</div>

---

### About

**{FIRM_NAME}** is a smart contract security research firm focused on blockchain and DeFi protocols. We strive to provide high‑quality, actionable security reviews and best‑effort assurance for your protocol. Check our previous work [here]({FIRM_URL}) or reach out on X [@{FIRM_HANDLE}]({FIRM_X_URL}).

#### Disclaimer

A smart contract security review can never verify the complete absence of vulnerabilities. This is a time, resource, and expertise‑bound effort where we try to find as many vulnerabilities as possible. We cannot guarantee 100% security after the review, or even that the review will find any issues. Subsequent security reviews, bug bounty programs, and on‑chain monitoring are strongly recommended.

#### Introduction

A time‑boxed security review of the **{REPO_NAME}** repository was performed by **{FIRM_NAME}**, with a focus on the security aspects of the protocol’s smart contracts implementation. There were <strong>YY</strong> issues uncovered.

#### About {PROJECT_NAME}

{PROJECT_NAME} is a {SHORT_DESCRIPTION} (e.g., Ethereum L2 rollup, DeFi protocol, NFT system).  
The **{CORE_ASSET_NAME}** is a {DESCRIPTION_OF_ASSET} essential for operating {CORE_USE_CASE} on the {NETWORK_NAME} network.

##### Risk Classification

| Severity                | Impact: High        | Impact: Medium        | Impact: Low        |
|-------------------------|---------------------|------------------------|--------------------|
| **Likelihood: High**    | Critical            | High                  | Medium             |
| **Likelihood: Medium**  | High               | Medium                | Low                |
| **Likelihood: Low**     | Medium             | Low                   | Low                |

##### Impact

- **High** – leads to a significant material loss of assets in the protocol or significantly harms a group of users.  
- **Medium** – leads to a moderate material loss of assets in the protocol or moderately harms a group of users.  
- **Low** – leads to a minor material loss of assets in the protocol or harms a small group of users.

##### Likelihood

- **High** – attack path is possible with reasonable assumptions that mimic on‑chain conditions, and the cost of the attack is relatively low compared to the amount of funds that can be stolen or lost.  
- **Medium** – only a conditionally incentivized attack vector, but still relatively likely.  
- **Low** – has too many or unlikely assumptions, or requires a significant stake by the attacker with little or no incentive.

##### Action required for severity levels

- **Critical** – must fix as soon as possible (if already deployed).  
- **High** – must fix (before deployment, if not already deployed).  
- **Medium** – should fix.  
- **Low** – could fix.

---

### Security Assessment Summary

**Review commit hash** – [`{REVIEW_COMMIT_HASH}`]({GITHUB_TREE_URL}/{REVIEW_COMMIT_HASH})  
**Fixes review commit hash** – [`{FIXES_COMMIT_HASH}`]({GITHUB_TREE_URL}/{FIXES_COMMIT_HASH})

##### Scope

The following smart contracts were in scope of the audit:

- {ContractName1}
- {ContractName2}
- {ContractName3}
- {ContractName4}
- {ContractName5}

---

### Findings

#### [H-01] {High‑severity finding title}

**Impact:** High  
**Likelihood:** Medium  

##### Description

{Concise description of the vulnerability and how it arises in the code. Highlight the function, variables, and conditions involved. Optionally, include an inline Solidity snippet like:}

```solidity
function exampleFunction(...) public {...}
