# Lockrion Reserve (LRV)
## Treasury Charter v1.2

---

## 1. Purpose

Lockrion Reserve (LRV) is a managed digital treasury structure operating with a fixed token supply and dynamically controlled circulation.

The purpose of LRV is:

- To maintain a transparent, actively managed crypto asset treasury.
- To regulate circulating supply in structural alignment with treasury asset units.
- To allocate capital periodically into deterministic issuance structures via the Lockrion protocol.

LRV does not constitute:

- Equity or ownership interest
- Revenue share entitlement
- Dividend instrument
- Governance right
- Legal claim over underlying assets

LRV represents participation within a transparent treasury structure governed by predefined structural rules.

---

## 2. Token Structure

### 2.1 Fixed Supply

S_total = 10,000,000 LRV

- Total supply is permanently fixed.
- Minting is permanently disabled.
- Burning is permanently disabled.
- No inflation or deflation mechanism exists.

### 2.2 Circulation and Vault Model

S_circ ≈ A_total

Where:

- S_circ = number of LRV tokens in circulation
- A_total = total number of asset units held in treasury
- Allowed deviation tolerance = ±20 units

Vault balance:

S_vault = S_total − S_circ

The vault holds non-circulating LRV tokens.

If deviation exceeds tolerance, alignment must be restored within 24 hours from the moment the deviation is technically detected by the treasury monitoring system.

---

## 3. Asset Unit Definition

- Each eligible token unit held in treasury counts as 1 asset unit.
- Asset unit accounting is independent of market price.
- Only whole token units are counted.
- Fractional balances are ignored.
- NFT assets are not eligible.
- LP tokens are not eligible.
- Yield-bearing or derivative positions are not eligible.
- Only direct token holdings qualify as asset units.

Asset unit accounting applies strictly to quantity and does not represent valuation.

---

---

## 4. Treasury Structure

### 4.1 Asset Categories

Treasury assets may include:

- Fully collateralized stablecoins
- Major publicly traded digital assets
- Other publicly tradable crypto tokens

Only direct token holdings are permitted.

### 4.2 Stable Buffer Requirement

Stable Share ≥ 25% of Total Portfolio Value (USD)

Stable assets must be fully collateralized stablecoins.

Algorithmic stablecoins are not permitted.
Yield-bearing stable derivatives are not permitted.

Stable Share is calculated only prior to any expansion of S_circ.

If Stable Share is below 25% at the moment of expansion decision:

- Circulation expansion is suspended
- Only rebalancing operations are permitted

---

## 5. Circulation Expansion and Contraction Framework

### 5.1 Expansion Guideline

Delta S_circ ≤ 5% of current S_circ per calendar month

This limit is a management guideline and not a strict prohibition.

Temporary exceedance is permitted under market conditions.

Expansion may occur only through:

- Sale of LRV tokens
- Acquisition of treasury assets

### 5.2 Contraction Mechanism

Contraction is executed through:

- Sale of treasury assets
- Market buyback of LRV tokens

No automatic stabilization mechanism exists.

All actions are discretionary and manually executed by the Treasury Operator.

In extraordinary market conditions, no action may be taken.

---

## 6. Portfolio Valuation Framework

Portfolio Value is calculated in USD.

Valuation is based on publicly available market pricing data sourced from CoinGecko API.

If CoinGecko pricing data is unavailable:

- Valuation is suspended
- Issuance is suspended
- Expansion and contraction decisions are paused

Total Portfolio Value (USD) is calculated as:

Sum of (Token Balance × USD Market Price)

If a token has no available market price:

- It is excluded from USD valuation
- It remains included in Asset Unit accounting

Valuation is performed at the time of official treasury snapshot.

Treasury snapshot includes:

- Timestamp
- Full portfolio composition
- Total asset units
- Total USD value

The treasury snapshot is published publicly.

---

## 7. Monthly Capital Allocation Mechanism

Monthly Release is defined as:

Monthly Release = k × Avg(Portfolio Value_last_90_days)

Where:

- k is between 0.5% and 1.5%
- Default value: k = 1%
- Avg(Portfolio Value_last_90_days) is calculated as the average Portfolio Value over the last 90 days at the moment of official snapshot

The release date is determined at the discretion of the Treasury Operator.

Released capital is deployed exclusively through Lockrion deterministic issuance structures.

Parameter k may be adjusted no more than once per quarter.

If a calculation error is discovered after snapshot:

- Correction is permitted
- Updated report must be published transparently

---

## 8. Management and Authority

Treasury management is centralized.

The Treasury Operator is Flexion Labs Inc.

Operational authority is exercised by the CEO of Flexion Labs Inc.

LRV grants no governance rights.

All treasury addresses are publicly disclosed.

Circulation and asset alignment are publicly auditable.

All operational actions are documented and published.

---

## 9. Operational Pause

In case of:

- Market dislocation
- Exchange outage
- Pricing data failure
- Infrastructure failure
- Force majeure

The Treasury Operator may declare an official status:

Operational Pause

During Operational Pause:

- No expansion is executed
- No contraction is executed
- No issuance is executed
- No rebalancing is executed

When conditions normalize, Operational Pause may be lifted.

The decision to declare or lift Operational Pause rests with Flexion Labs Inc.

---

## 10. Risk Framework

LRV is exposed to:

- Market volatility
- Liquidity constraints
- Reflexive price dynamics
- Simultaneous portfolio drawdowns
- Stablecoin counterparty risk
- Pricing data dependency risk

No price stabilization guarantee is provided.

No obligation exists to defend or support market price.

Treasury management prioritizes structural discipline over reactive intervention.

---

## 11. Structural Principles

1. No supply inflation.
2. No algorithmic stabilization.
3. No automatic liquidation.
4. No guaranteed returns.
5. Manual, disciplined treasury management.
6. Transparent reporting of treasury operations.
7. Asset unit symmetry between circulation and treasury.
8. Priority of stability over reaction.

Structural alignment between S_circ and A_total must be restored within 24 hours if tolerance is exceeded.

---

Version: v1.2  
Status: Foundational Treasury Framework  
Document Type: Treasury Charter