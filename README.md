# 📈 Option Greeks & Pricing Analysis  

This repository provides an in-depth analysis of **Option Greeks**, their interactions, and **option pricing calculations** using the **Black-Scholes model**. We explore how Greeks behave under different market conditions, how they impact **option pricing and risk management**, and provide tools for **implied volatility calculations**.  

---

## 🚀 Overview  

This repository covers:  
✅ **Option Greeks Calculation** (Delta, Gamma, Theta, Vega, Rho).  
✅ **Black-Scholes Pricing Model** for call and put options.  
✅ **Implied Volatility Calculation** using the Newton-Raphson method.  
✅ **Visualizing Greeks Behavior & Interactions** under different conditions.  

---

## 📌 Option Greeks  

| Greek  | Definition | Key Insights |
|--------|------------|--------------|
| **Delta (Δ)**  | Sensitivity of option price to stock price changes. | High for ITM options, near 0 for OTM options. Call Delta is positive, Put Delta is negative. |
| **Gamma (Γ)**  | Rate of change of Delta. | Highest for ATM options and near expiry. Indicates risk from Delta fluctuations. |
| **Theta (Θ)**  | Measures time decay of option value. | Most negative for ATM options near expiry. Short-term options decay faster. |
| **Vega (ν)**  | Sensitivity to changes in implied volatility. | Highest for ATM options and longer expiries. IV changes affect Vega significantly. |
| **Rho (ρ)**  | Sensitivity to interest rate changes. | Call options increase with rate hikes, puts decrease. Impact is small for near-expiry options. |

---

## 📊 Analyses & Visualizations  

### 🔹 1. **Greek Behavior vs. Stock Price**  
📌 Examines how Delta, Gamma, Theta, Vega, and Rho fluctuate as the stock price moves.  

### 🔹 2. **Greek Interactions & Market Conditions**  
✔️ **Delta & Gamma Interaction:** High Gamma → Rapid Delta changes.  
✔️ **Delta & Vega Interaction:** High Vega → Larger Delta swings with volatility.  
✔️ **Gamma & Theta Interaction:** High Gamma → Faster Theta decay.  
✔️ **Vega & Theta Interaction:** Options with high Vega lose value slower due to Theta decay.  
✔️ **Rho & Vega Interaction:** Interest rate changes impact Vega for long-term options.  

### 🔹 3. **Black-Scholes Model & Option Pricing**  
📌 Calculate **call & put prices** using the **Black-Scholes formula**.  
📌 Estimate **implied volatility** using **Newton-Raphson**.  

### 🔹 4. **Effect of Time to Expiry (T) & Strike Price (K)**  
📌 **Theta Decay vs. Gamma Spikes:** ATM options experience the fastest Theta decay.  
📌 **IV Smile & Skew:** IV varies across strikes, impacting Vega & Gamma.  
📌 **Sensitivity of Greeks to Time Decay:** Theta, Gamma, Vega, and Delta change as expiry nears.  
📌 **Impact of Strike Price on Greeks:** ATM options have the highest Gamma and Vega.  

### 🔹 5. **Implied Volatility & Its Effect on Greeks**  
📌 **Impact of IV on Greeks:** Higher IV increases Vega, decreases Gamma, and increases Theta decay.  
📌 **Skewness & Smile in IV:** Higher IV for ITM and OTM options impacts Vega, Gamma, and Theta.  

### 🔹 6. **Risk-Free Rate & Greeks**  
📌 **Impact of R on Greeks:** Delta, Rho, and Theta shift when interest rates change.  

### 🔹 7. **Hedging & Portfolio Stability**  
📌 **Effect of Gamma on Hedging:** High Gamma requires frequent rebalancing.  
📌 **Theta Decay & Gamma Spikes:** Expiry leads to accelerated Theta decay and increased Gamma risk.  

📢 Conclusion
Understanding Option Greeks and option pricing is crucial for traders and risk managers. This repository provides:
✅ A practical tool to analyze Greeks & price options.
✅ Visualizations for better insights into market behavior.
✅ Code implementation of the Black-Scholes pricing model & implied volatility calculations.

🤝 Contributing
We welcome contributions! If you have suggestions, feel free to:
🔹 Open an issue to discuss improvements or bugs.
🔹 Submit a pull request with enhancements or fixes.

📌 Let's build a better options analytics toolkit together!

⭐ If you find this repo useful, consider giving it a star! ⭐

⚠️ Disclaimer
This repository is provided for educational purposes only. Options trading involves significant risks, and this script does not constitute financial advice. Use it at your own discretion and conduct proper risk management before trading.

