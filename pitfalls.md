# Trading Analysis Pitfalls

8 analytical biases to avoid when evaluating directional/options trades. Derived from real trade experience.

---

## 1. Do not treat "price at analyst consensus" as a bearish signal

**Rule**: Analyst consensus is a **trailing indicator**. Price leads analysts, not the reverse. When stock reaches consensus target, consensus is usually being revised higher.

**Why it matters**: Anchoring bearish because "price = consensus" ignores that the consensus itself has been rising. If last-month avg >> last-quarter avg, analysts are catching up to momentum, not capping it.

**How to apply**: Check the *velocity* of consensus revisions. Rising consensus with rising price = trend intact, not exhaustion.

---

## 2. A single large options trade ≠ "smart money" signal

**Rule**: One big institutional order reflects **one desk's positioning**, not market consensus. Institutions lose too.

**Why it matters**: A $800k+ LEAP call seller can be wrong. Using "they sold big at strike X" as a directional edge is flawed when the underlying fundamentals shift.

**How to apply**:
- Require *confluence* — multiple institutions same direction + price action same direction
- Aggressive sweeps > sitting orders
- Options flow is a **positioning snapshot**, not a **directional prediction**

---

## 3. Tape > opinion > DCF for short-term trades

**Rule**: For trades held <30 days, prioritize:
1. Price action (what the tape is doing)
2. Sentiment / catalysts (what's driving flow)
3. Valuation (DCF, multiples)

**Why it matters**: Starting with DCF and forcing the tape to fit leads to fighting trends. A stock can stay "overvalued" for months on momentum.

**How to apply**: Open every short-term analysis by describing the tape first (last 3 daily closes, volume profile, support/resistance), then layer sentiment, then valuation.

---

## 4. When thesis premise is invalidated, FLIP — don't hold

**Rule**: If the *precondition* for your thesis stops being true, exit or reverse. Holding through invalidation is sunk-cost bias.

**Why it matters**: Example — "sell-the-news" requires weak tape. If the stock holds strong through expected weakness, the setup is dead. Flipping early > stubborn holding.

**How to apply**:
- Write down the thesis *preconditions* at entry
- Review them each time new info arrives
- If a precondition breaks, trigger position review immediately
- Reversing a position is not weakness — it's the highest-order trading skill

---

## 5. Don't overreact to a single news event — check if it's priced in

**Rule**: Post-market news that moves stock <3% is often already 60-80% priced in. A small reaction doesn't mean the news is unimportant — it means the market already expected it.

**Why it matters**: Flipping strategies based on "big news" that the market barely responds to is overreaction. The magnitude of reaction tells you how much was unexpected.

**How to apply**: Estimate NPV of news → compare to actual price reaction → if reaction ≈ NPV, news is correctly priced. Recommend action only if reaction is materially off.

---

## 6. "Finding clever structures" signals fading conviction

**Rule**: When your instinct shifts from vanilla spreads to ratio spreads, butterflies, diagonals, ask: **Am I being clever because the simple structure is optimal, or because my conviction is dropping?**

**Why it matters**: Complex structures can mask uncertainty. Better to reduce size or close than dress up diminishing conviction in sophistication.

**How to apply**: When recommending a complex structure, explicitly check: "Is this really optimal, or am I hedging for a thesis I no longer fully believe?" If the latter, close instead of restructure.

---

## 7. IV crush benefits SHORT premium structures, not long ones

**Rule**: High IV Rank (>70) favors **selling** premium (credit spreads, short puts, iron condors). It hurts long premium (debit spreads, naked long options), even if direction is right.

**Why it matters**: A long put at IV 95% with IV crush to 50% can lose money even on a correct bearish call. Direction right + structure wrong = loss.

**How to apply**:
- High IV Rank + directional view → default to credit structures (sell premium)
- Only buy premium when IV is low OR directional conviction is very high
- Always ask: "Does my structure benefit from or suffer from IV crush?"

---

## 8. "Priced in" is not binary — estimate the percentage

**Rule**: Events are partially priced in. Use "what % is priced in" framing rather than "is it priced in yes/no".

**Why it matters**: 70% priced in is very different from 100% priced in. The 30% residual uncertainty still drives multi-day price action.

**How to apply**: For any news event:
- Estimate theoretical NPV of the news
- Compare to actual price reaction
- If reaction ≈ NPV × X%, then (100 - X)% is still unpriced
- Size positions to the residual uncertainty, not the nominal news
