# Phase 4: Key Insights & Findings

## 1. Temporal Risk
- Fraud rates spike between 2–4 AM, especially in foreign transactions.
- Nighttime + foreign transactions show a 6.2x fraud rate compared to daytime domestic.

## 2. Behavioral Risk
- Users aged 18–25 with account tenure <6 months show elevated fraud rates (3.8% vs 1.2% baseline).
- Velocity scores >0.9 correlate with 4x fraud likelihood.

## 3. Merchant Risk
- High-risk merchant clusters show fraud rates >6%, compared to <1% in low-risk.
- Certain merchant categories (luxury, gaming) are overrepresented in flagged transactions.

## 4. Channel Risk
- Peer-to-peer and subscription channels are disproportionately flagged (fraud rate ~4.5%).
- NFC and QR scan channels show lower fraud rates but higher false positives.

## 5. Device Risk
- Apple Watch transactions show slightly elevated fraud rates, possibly due to limited biometric verification.

## 6. Feature Interactions
- `foreign_night_combo` is a strong signal: 7.1% fraud rate vs 1.3% overall.
- `merchant_risk_score` and `channel_risk_profile` are top predictors in preliminary models.

## 7. Operational Impact
- Optimizing fraud signals using these features could reduce false positives by ~40%.
- Estimated reduction in manual reviews: 3,800 transactions/month.
