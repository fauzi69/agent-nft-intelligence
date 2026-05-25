# Example Run — NFT Intelligence Desk

This artifact records a deterministic reviewer demo run for the MiMo approval pattern.

- Project: **NFT Intelligence Desk**
- Domain: NFT analytics
- Scenario: `collection shows rising floor but circular trades among new wallets`
- Status: `completed`
- Mode: `deterministic-reviewer-demo`
- Specialist agents: 5
- Estimated tokens: **49,835**
- Daily projection: **4,784,160 tokens/day**

## Findings

### Liquidity Scout
- Role: tracks pool depth, volatility spikes, and suspicious flow concentration
- Severity: `critical`
- Confidence: `0.83`
- Estimated tokens: `12791`
- Finding: Liquidity Scout reviewed DeFi risk monitoring signal: collection shows rising floor but circular trades among new wallets. Risk pattern=critical confidence=0.83.
- Recommendation: Run liquidity scout follow-up pass, capture artifacts, then prioritize critical items first.

### Exploit Sentinel
- Role: maps events to known attack primitives and detects anomalous protocol behavior
- Severity: `high`
- Confidence: `0.91`
- Estimated tokens: `8718`
- Finding: Exploit Sentinel reviewed DeFi risk monitoring signal: collection shows rising floor but circular trades among new wallets. Risk pattern=high confidence=0.91.
- Recommendation: Run exploit sentinel follow-up pass, capture artifacts, then prioritize high items first.

### Oracle Auditor
- Role: checks oracle drift, stale feeds, and manipulation windows
- Severity: `medium`
- Confidence: `0.68`
- Estimated tokens: `4265`
- Finding: Oracle Auditor reviewed DeFi risk monitoring signal: collection shows rising floor but circular trades among new wallets. Risk pattern=medium confidence=0.68.
- Recommendation: Run oracle auditor follow-up pass, capture artifacts, then prioritize medium items first.

### Treasury Guardian
- Role: scores treasury exposure and proposes emergency controls
- Severity: `high`
- Confidence: `0.76`
- Estimated tokens: `13270`
- Finding: Treasury Guardian reviewed DeFi risk monitoring signal: collection shows rising floor but circular trades among new wallets. Risk pattern=high confidence=0.76.
- Recommendation: Run treasury guardian follow-up pass, capture artifacts, then prioritize high items first.

### Incident Reporter
- Role: synthesizes operator-grade markdown incident reports
- Severity: `critical`
- Confidence: `0.75`
- Estimated tokens: `10791`
- Finding: Incident Reporter reviewed DeFi risk monitoring signal: collection shows rising floor but circular trades among new wallets. Risk pattern=critical confidence=0.75.
- Recommendation: Run incident reporter follow-up pass, capture artifacts, then prioritize critical items first.

