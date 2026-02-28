# Lockrion Reserve (LRV)
## Treasury Charter v1.1

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
- Investment contract
- Legal claim over underlying assets

LRV represents participation within a transparent treasury structure governed by predefined structural rules.

---

## 2. Token Structure

### 2.1 Fixed Supply

S_total = 10,000,000 LRV

- Total supply is permanently fixed
- Minting is permanently disabled
- Burning is permanently disabled
- No inflation or deflation mechanism exists

### 2.2 Circulation and Vault Model

S_circ ≈ A_total

Where:

- S_circ = number of LRV tokens in circulation
- A_total = total number of asset units held in treasury
- Allowed deviation tolerance = ±20 units

Vault balance:

S_vault = S_total − S_circ

The vault holds non-circulating LRV tokens.

If deviation exceeds tolerance, alignment must be restored within 24 hours.

---

## 3. Asset Unit Definition

- Each unit of any eligible token held in treasury counts as 1 asset unit
- Asset unit accounting is independent of market price
- NFT assets are not eligible
- LP tokens are not eligible
- Yield-bearing or derivative positions are not eligible
- Only direct token holdings qualify as asset units

Asset unit accounting applies strictly to quantity, not valuation.

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

If stable allocation falls below 25%:

- Circulation expansion is suspended
- Only rebalancing operations are permitted

Portfolio Value is calculated in USD using public market pricing data.

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
All actions are discretionary and manually executed.

In extraordinary market conditions, no action may be taken.
Treasury management prioritizes disciplined response over reactive intervention.

---

## 6. Portfolio Valuation Framework

Portfolio Value is calculated in USD.

Valuation is based on publicly available market pricing data sourced from CoinGecko API.

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
- Avg(Portfolio Value_last_90_days) is the 90-day rolling average of total treasury value

The release date is determined by the Treasury Operator.

Released capital is deployed exclusively through Lockrion deterministic issuance structures.

Parameter k may be adjusted no more than once per quarter.

If calculation error is discovered after snapshot:

- Correction is permitted
- Updated report must be published transparently

---

## 8. Management Model

Treasury management is centralized.

LRV grants no governance rights.

All treasury addresses are publicly disclosed.

Circulation and asset alignment are publicly auditable.

All operational actions are documented and published.

Transparency is prioritized over automation.

---

## 9. Risk Framework

LRV is exposed to the following risks:

- Market volatility
- Liquidity constraints
- Reflexive price dynamics
- Simultaneous portfolio drawdowns
- Stablecoin counterparty risk
- Pricing data dependency risk

No price stabilization guarantee is provided.

No obligation exists to defend or support market price.

Treasury management may choose to take no action during extreme market conditions.

In extraordinary situations (exchange outages, data failure, market dislocation), the default response is operational pause and observation.

---

## 10. Structural Discipline

The following structural principles govern LRV:

1. No supply inflation.
2. No algorithmic stabilization.
3. No automatic liquidation.
4. No guaranteed returns.
5. Manual, disciplined treasury management.
6. Transparent reporting of all treasury operations.
7. Asset unit symmetry between circulation and treasury.
8. Priority of stability over reaction.

Structural alignment between S_circ and A_total must be restored within 24 hours if tolerance is exceeded.

---

## 11. Relationship to Lockrion

LRV operates independently from the Lockrion protocol.

Lockrion functions as a deterministic issuance infrastructure.

LRV may allocate capital into Lockrion issuance structures but does not control, govern, or modify the Lockrion protocol.

Lockrion may operate without LRV.

LRV serves as a treasury layer interacting with Lockrion through capital deployment only.

---

Version: v1.1  
Status: Foundational Treasury Framework  
Document Type: Treasury Charter