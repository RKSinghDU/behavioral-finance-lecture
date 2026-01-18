# Example Diagram Mockups & Specifications

This document provides **text-based mockups** and **detailed descriptions** of what each diagram should look like. Use these as blueprints when creating actual visual files.

---

## 📊 Diagram 1: Prospect Theory Value Function

### Visual Description

**What it looks like:**
Imagine an S-shaped curve on a graph with two distinct sides:

```
         Subjective Value
              ↑
              |
         +10  |     ___----  (Gains - Gentle curve upward)
              |  __/
          +5  | /
              |/
    ←─────────┼─────────→  Reference Point (0,0)
     Losses   |         Gains
              |\
          -5  | \__
              |    \___
        -10   |        ----___  (Losses - Steep curve downward)
              |
```

**Key Visual Elements:**

**Left Side (Losses in RED):**
- Steeper slope than right side
- Convex shape (curves outward)
- Extends deeper below x-axis
- Formula overlay: v(x) = -2.25×(-x)^0.88

**Right Side (Gains in GREEN):**
- Gentler slope
- Concave shape (curves inward)
- Rises less dramatically
- Formula overlay: v(x) = x^0.88

**Annotations:**
- Arrow pointing to origin: "Reference Point - Where you evaluate from"
- Horizontal comparison lines showing loss aversion
- Text box: "Losing ₹500 hurts ~2.25× more than gaining ₹500 feels good"

**Example Implementation (ASCII Art):**

```
                    VALUE
                      ↑
    GAINS        +10  |        /‾‾‾‾
                      |     __/      (Diminishing sensitivity)
                 +5   |   _/
                      | _/
    ←────────────────┼────────────→  LOSSES vs GAINS
    -₹1000          0|         +₹1000
                    /|
                  _/ |
            -5  _/   |
              _/     |              (Steeper = Loss aversion)
        -10  /       |
            ↓
      More pain per rupee lost
```

---

## 📅 Diagram 2: Behavioral Finance Timeline

### Visual Description

**Layout:** Horizontal timeline spanning 80 years (1944-2024)

**Structure:**
```
CLASSICAL ERA (Gray)          BEHAVIORAL ERA (Colorful)
     ↓                                 ↓
═════●═════●═════════════●═════●═════●═════●═════●═════●═════
1944     1970          1974  1979  2002  2008  2017  2023
```

**Key Milestones with Icons:**

```
1944 📘 von Neumann & Morgenstern
     Expected Utility Theory
     ────────────────────────────────

1970 📈 Fama
     Efficient Market Hypothesis
     ────────────────────────────────

1974 🧠 Tversky & Kahneman         ← PARADIGM SHIFT
     "Judgment Under Uncertainty"
     ════════════════════════════════

1979 ⚡ Kahneman & Tversky
     PROSPECT THEORY
     ════════════════════════════════

1985 💰 Thaler
     Mental Accounting
     ════════════════════════════════

2002 🏆 KAHNEMAN NOBEL PRIZE
     "Integrated psychology into economics"
     ════════════════════════════════

2008 🌍 Global Financial Crisis
     Rational models fail
     ════════════════════════════════

2017 🏆 THALER NOBEL PRIZE
     "Contributions to behavioural economics"
     ════════════════════════════════

2023 📊 SEBI Study
     89% of traders lose money
     ════════════════════════════════
```

**Color Coding:**
- Pre-1974: Gray scale (rational era)
- Post-1974: Vibrant blues, oranges, golds (behavioral era)
- Nobel Prizes: Gold with glow effect
- Crises: Red

---

## 🕸️ Diagram 3: Bias Interaction Web

### Visual Description

**Layout:** Hexagon with center node

```
                    📅 RECENCY
                   "Stock up 40%"
                        ↓
                        ↓
    😰 LOSS AVERSION ←  ●  → 👥 HERD
    "Can't sell at loss" ↓ "Everyone buying"
                         ↓
                  [INVESTOR DECISION]
                         ↓
                  "Buy this IPO?"
                         ↓
    ⚓ ANCHORING   ←  ●  → 💪 OVERCONFIDENCE
    "IPO price=fair"     ↓  "I understand this"
                         ↓
                         ↓
                  ✓ CONFIRMATION
               "Only read bullish news"
```

**Arrow Types:**
- Dotted (→) = Triggers
- Solid (→) = Reinforces
- Thick (⇒) = Locks in

**Example Cascade:**
```
Step 1: RECENCY triggers HERD
   "Tech stocks up 40% last year" 
   → "Everyone at work is buying"

Step 2: HERD validates OVERCONFIDENCE
   "So many smart people buying" 
   → "I must be right about this"

Step 3: OVERCONFIDENCE seeks CONFIRMATION
   "I know this sector" 
   → "Let me find articles that agree"

Step 4: CONFIRMATION creates ANCHOR
   "All my sources say ₹500 is fair" 
   → "₹500 becomes my reference point"

Step 5: ANCHOR triggers LOSS AVERSION
   "I paid ₹500" 
   → "Can't sell below ₹500"

Step 6: LOSS AVERSION feeds RECENCY
   "Next rally will come" 
   → Hold through next cycle, repeat
```

**Color Scheme:**
- Center (Decision): White/Light gray
- RECENCY: Light blue
- HERD: Purple
- OVERCONFIDENCE: Orange
- CONFIRMATION: Green
- ANCHORING: Red
- LOSS AVERSION: Dark red

---

## 📈 Diagram 4: Indian Market Chart (Sensex 2006-2024)

### Visual Description

**Main Chart:**
```
Sensex
80,000 ────────────────────────────────────────── ⚠️ 2024
       |                                              "New highs"
70,000 |                                         ╱
       |                                    ╱────
60,000 |                              🎉╱   2021 IPO Frenzy
       |                           ╱─┘
50,000 |                      ╱───┘
       |                  ╱──┘
40,000 |              ╱──┘ 
       |          ╱──┘
30,000 |      ╱──┘         🎯 2014 Modi Rally
       |  ╱──┘
20,000 |─┘🐂 2008 Peak
       |  \___
10,000 |      \___
       |          ╲___  😰 2009 Bottom
 5,000 |              ╲   (Best buying opportunity)
       └────────────────────────────────────────→
      2006        2010        2015        2020   2024
```

**Annotation Bubbles:**

**2008 Peak (21,000):**
```
╔═══════════════════════════════╗
║   🐂 PEAK EUPHORIA (2008)     ║
║   ─────────────────────       ║
║   Herd: "Everyone owns stocks"║
║   Recency: "Only go up"       ║
║   Reality: 62% crash ahead    ║
╚═══════════════════════════════╝
```

**2009 Bottom (8,000):**
```
╔═══════════════════════════════╗
║   😰 PANIC SELLING (2009)     ║
║   ─────────────────────       ║
║   Loss Aversion: Exit market  ║
║   Herd: Redemption cascade    ║
║   Reality: 10x opportunity    ║
╚═══════════════════════════════╝
```

**2021 IPO Frenzy (58,000):**
```
╔═══════════════════════════════╗
║   🎉 IPO GOLD RUSH (2021)     ║
║   ─────────────────────       ║
║   Zomato, Nykaa, Paytm        ║
║   Anchoring: Issue prices     ║
║   Herd: "Can't miss out"      ║
╚═══════════════════════════════╝
```

**Background Shading:**
- Green zones: Bull markets (2006-07, 2014-17, 2020-21)
- Red zones: Bear markets (2008-09, 2022)
- Opacity: 20% (translucent)

---

## 🎯 Diagram 5: Three Levels Framework

### Visual Description

**Inverted Pyramid Structure:**

```
                    🌍 SYSTEMIC LEVEL
    ══════════════════════════════════════════════
    │  Market Bubbles • Crashes • Misallocation │
    │  2008 GFC • Dotcom • Crypto Mania        │
    │  Cost: ₹Lakh Crores • Years of lost growth│
    ══════════════════════════════════════════════
                         ↑
                   Synchronization
                         ↑
              🏢 ORGANIZATIONAL LEVEL
    ══════════════════════════════════════
    │  Failed M&A • Sunk Cost Projects  │
    │  Kingfisher • Tata Nano           │
    │  Cost: ₹Crores destroyed          │
    ══════════════════════════════════════
                    ↑
              Aggregation
                    ↑
          🧍 INDIVIDUAL LEVEL
    ═══════════════════════════════
    │  Portfolio Losses           │
    │  Vodafone ₹50→₹5           │
    │  Cost: ₹Lakhs lost         │
    ═══════════════════════════════
```

**Side Panel (Your Role):**
```
╔═══════════════════════════════════╗
║  🎯 AS HR-OB PROFESSIONALS        ║
╠═══════════════════════════════════╣
║                                   ║
║  INDIVIDUAL LEVEL:                ║
║  ✓ Financial wellness programs    ║
║  ✓ Investor education             ║
║                                   ║
║  ORGANIZATIONAL LEVEL:            ║
║  ✓ Compensation design            ║
║  ✓ Benefits choice architecture   ║
║                                   ║
║  SYSTEMIC LEVEL:                  ║
║  ✓ Policy advocacy                ║
║  ✓ Regulatory feedback            ║
║                                   ║
║  ────────────────────────────     ║
║  Every design either:             ║
║  🔴 EXPLOITS biases               ║
║  🟢 MITIGATES biases              ║
║                                   ║
║  Choose wisely.                   ║
╚═══════════════════════════════════╝
```

---

## 💰 Diagram 6: Mental Accounting

### Visual Description

**Split-Screen Comparison:**

```
LEFT SIDE: "Found Money"          RIGHT SIDE: "Earned Money"
───────────────────────────────────────────────────────────
  🎰 Won ₹5,000                    💼 Earned ₹5,000
     in lottery                        in overtime
         ↓                                  ↓
                                           
[  WINDFALL ACCOUNT  ]           ╔═ INCOME ACCOUNT ═╗
   "Fun money"                    ║ "Hard-earned"   ║
   "House money"                  ║ "My sweat"      ║
   Low ownership                  ║ High ownership  ║
                                  ╚═════════════════╝
         ↓                                  ↓

Treatment:                        Treatment:
🍽️ Fancy dinner                  🏦 Savings deposit
🎬 Movies                         📊 Mutual fund
🛍️ Impulse buys                  💳 Pay credit card
         ↓                                  ↓

Emotional State:                  Emotional State:
😊 "Okay to splurge!"            🤔 "Be responsible"
```

**Center Warning Box:**
```
        ⚠️  ═══════════════════════  ⚠️
            SAME ₹5,000
            DIFFERENT TREATMENT
            
            Economically: IDENTICAL
            Psychologically: COMPLETELY DIFFERENT
            
            This is MENTAL ACCOUNTING
            Money is fungible—your brain isn't
        ═══════════════════════════════════
```

**Bottom Examples:**
```
Portfolio Mental Accounts:

[SAFE MONEY]     [GROWTH MONEY]    [PLAY MONEY]
  Fixed Dep        Large-cap         Penny stocks
  EPF              Blue-chip         Crypto
  PPF              SIP funds         F&O trading
  ─────            ─────             ─────
  0% risk          15% risk          100% risk
  tolerance        tolerance         tolerance

Same person. Same net worth. Different risk appetite PER ACCOUNT.
```

---

## 📉 Diagram 7: Disposition Effect Portfolio

### Visual Description

**Portfolio Grid (3×4 cards):**

```
╔═══════════════╗  ╔═══════════════╗  ╔═══════════════╗
║ ✓ INFOSYS    ║  ║ ✓ TCS        ║  ║ ✓ HDFC BANK  ║
║ Buy: ₹1,200  ║  ║ Buy: ₹2,800  ║  ║ Buy: ₹1,500  ║
║ Sold: ₹1,680 ║  ║ Sold: ₹3,640 ║  ║ Sold: ₹1,800 ║
║ +40% GAIN ✓  ║  ║ +30% GAIN ✓  ║  ║ +20% GAIN ✓  ║
║ Held: 6 mon  ║  ║ Held: 8 mon  ║  ║ Held: 4 mon  ║
╚═══════════════╝  ╚═══════════════╝  ╚═══════════════╝
  (Faded gray)       (Faded gray)       (Faded gray)
   Winners SOLD       Winners SOLD       Winners SOLD

╔═══════════════╗  ╔═══════════════╗  ╔═══════════════╗
║ ⚠ VODAFONE   ║  ║ ⚠ YES BANK   ║  ║ ⚠ SUZLON     ║
║ Buy: ₹50     ║  ║ Buy: ₹220    ║  ║ Buy: ₹25     ║
║ Now: ₹5      ║  ║ Now: ₹18     ║  ║ Now: ₹3      ║
║ -90% 📉      ║  ║ -92% 📉      ║  ║ -88% 📉      ║
║ Held: 5 YEARS║  ║ Held: 6 YEARS║  ║ Held: 8 YEARS║
╚═══════════════╝  ╚═══════════════╝  ╚═══════════════╝
  (Bright red)       (Bright red)       (Bright red)
   Losers HELD        Losers HELD        Losers HELD

... 6 more bright red loser cards ...
```

**Portfolio Summary:**
```
╔════════════════════════════════════════╗
║      📊 PORTFOLIO PERFORMANCE          ║
╠════════════════════════════════════════╣
║  Total Invested:        ₹6,00,000     ║
║  Current Value:         ₹2,10,000     ║
║  Loss:                  -₹3,90,000    ║
║  Return:                -65% 📉        ║
╠════════════════════════════════════════╣
║  Winners Sold (early):  3 positions    ║
║  → Avg hold: 6 months                  ║
║  → Missed subsequent 50%+ gains        ║
║                                        ║
║  Losers Still Held:     9 positions    ║
║  → Avg hold: 7.4 YEARS                ║
║  → Avg loss: -87%                      ║
╚════════════════════════════════════════╝
```

**Counterfactual Box:**
```
🔄 WHAT IF YOU DID THE OPPOSITE?

If you had:
• Let winners run → +100%, +85%, +40% gains
• Cut losers at -20% → Saved ₹35, ₹158, ₹17 per share

Counterfactual: ₹6L → ₹11.5L (+92%)
Actual Portfolio: ₹6L → ₹2.1L (-65%)

Disposition Effect Cost: ₹9.4 LAKH
```

---

## 🌊 Diagram 8: Informational Cascade

### Visual Description

**Left-to-Right Flow:**

```
STAGE 1          STAGE 2         STAGE 3           STAGE 4
Individual       Follower        Cascade Begins     Full Mania
────────────────────────────────────────────────────────────

👤 Person A      👤 Person B     👥 Persons C-E    👥👥👥 Persons F-P
  ↓                ↓                 ↓                  ↓
[Analysis]      [Sees A buy]    [Sees A & B]      [EVERYONE buying]
  ↓                ↓                 ↓                  ↓
"Growth         "A is smart"    "They must        "FOMO!!!
 looks good"                     know something"    Can't miss out!"
  ↓                ↓                 ↓                  ↓
 BUY              BUY              BUY               BUY BUY BUY
 (Own            (Inference)      (Social proof)    (Panic buying)
  research)
  
  
Information Quality Over Time:
Person A:    ████████░░ 80% signal
Person B:    ██████░░░░ 60% signal  
Persons C-E: ████░░░░░░ 40% signal
Persons F-P: ██░░░░░░░░ 20% signal
Final buyers:░░░░░░░░░░  0% signal (100% noise)
```

**The Bubble:**
```
           🎈
       ___/  \___
      /          \
     |  BUBBLE    |  ← Price detached from fundamentals
     |  STATE     |    100+ participants
     |            |    1 informed (A), 99 following
      \          /
       ╲________╱
           ║
         FRAGILE
```

**The Collapse:**
```
Trigger: Any bad news
    ↓
    💥 EXPLOSION
    ↓
Reverse Cascade (same speed, opposite direction)
    ↓
Everyone sells → Panic → Crash
```

---

## ⚓ Diagram 9: Anchoring Effect Graph

### Visual Description

**Scatter Plot:**

```
Willingness
to Pay (₹)
   1000 │                                    ●
        │                               ●  ● ●
    800 │                          ●  ●
        │                     ●  ●
    600 │                ●  ●           [Regression Line]
        │           ●  ●                y = 2.8x + 180
    400 │      ●  ●                     R² = 0.42
        │  ● ●
    200 │●●
        └─────────────────────────────────────────→
         0    20   40   60   80   100
              Last 2 Digits of Phone Number
                      (Anchor)


LOW ANCHOR GROUP              HIGH ANCHOR GROUP
(00-25)                       (75-99)
Average: ₹222                 Average: ₹426
"Seems reasonable"            "Seems reasonable"
    ↓                              ↓
        SAME PEN • 90% PRICE GAP
```

**Experimental Protocol Box:**
```
┌─────────────────────────────────────┐
│  STEP 1: Set Anchor                 │
│  "Last 2 digits of phone: __92__"   │
│  "Would you pay ₹92?"  ⃞ Yes ☑ No  │
├─────────────────────────────────────┤
│  STEP 2: Actual Bid                 │
│  "Maximum you'd pay: ₹___437___"    │
└─────────────────────────────────────┘

Result: Number 92 anchored bid at ₹437
```

---

## 🎯 Diagram 10: Choice Architecture Framework

### Visual Description

**2×2 Matrix:**

```
        BIAS MITIGATION
              ↑
              │
    ──────────┼──────────
    │         │         │
    │  SMART  │ ACTIVE  │  HIGH
    │ DEFAULTS│DEBIASING│  EFFORT
    │   ✅    │   🎓    │
    ├─────────┼─────────┤    ↑
    │ STATUS  │COMPLEXITY│    │
    │   QUO   │  TRAP   │    │
    │  TRAP   │   😵    │  LOW
    │   ⚠️    │         │  EFFORT
    └─────────┴─────────┘
        LOW      HIGH
         ←  EFFORT  →
```

**Quadrant Details:**

**Q1: SMART DEFAULTS (Top-Left) ✅**
```
╔══════════════════════════════════════╗
║         🎯 OPTIMAL ZONE              ║
╠══════════════════════════════════════╣
║ Default = Good choice                ║
║ User does nothing → Best outcome     ║
║                                      ║
║ Examples:                            ║
║ • Opt-out EPF enrollment (85%)       ║
║ • Age-based asset allocation         ║
║ • Recommended health insurance       ║
║                                      ║
║ Bias mitigated: Status quo, present  ║
╚══════════════════════════════════════╝
```

**Q2: ACTIVE DEBIASING (Top-Right) 🎓**
```
╔══════════════════════════════════════╗
║      📚 EDUCATIONAL ZONE             ║
╠══════════════════════════════════════╣
║ Awareness + Tools                    ║
║ User must engage                     ║
║                                      ║
║ Examples:                            ║
║ • Pre-mortem analysis                ║
║ • 48-hour cooling-off periods        ║
║ • Bias training workshops            ║
║                                      ║
║ Effort: High  Effect: Strong         ║
╚══════════════════════════════════════╝
```

**Q3: STATUS QUO TRAP (Bottom-Left) ⚠️**
```
╔══════════════════════════════════════╗
║        🚨 DANGER ZONE                ║
╠══════════════════════════════════════╣
║ Default = Profit for company         ║
║ User does nothing → Exploited        ║
║                                      ║
║ Examples (AVOID):                    ║
║ ❌ Auto-renewal subscriptions        ║
║ ❌ Pre-checked upsell boxes          ║
║ ❌ Complex hidden fees               ║
║                                      ║
║ This is dark pattern design          ║
╚══════════════════════════════════════╝
```

**Q4: COMPLEXITY TRAP (Bottom-Right) 😵**
```
╔══════════════════════════════════════╗
║       🌀 PARALYSIS ZONE              ║
╠══════════════════════════════════════╣
║ Overwhelm → Bad default accepted     ║
║ User gives up                        ║
║                                      ║
║ Examples (AVOID):                    ║
║ ❌ 59 fund options (paralysis)       ║
║ ❌ 47-page prospectus                ║
║ ❌ Opaque fee structures             ║
║                                      ║
║ Result: Status quo or worst option  ║
╚══════════════════════════════════════╝
```

---

## 🎨 Implementation Guide Summary

### Tools for Creating These Diagrams

| Diagram | Best Tool | Alternative | Complexity |
|---------|-----------|-------------|------------|
| 1. Prospect Theory | Python/Excel | PowerPoint | Medium |
| 2. Timeline | PowerPoint | Canva | Low |
| 3. Bias Web | Draw.io | Miro | Medium |
| 4. Market Chart | Excel/Python | TradingView | Medium |
| 5. Three Levels | PowerPoint | Canva | Low |
| 6. Mental Accounting | PowerPoint | Canva | Low |
| 7. Portfolio Cards | PowerPoint | Figma | Medium |
| 8. Cascade | Draw.io | PowerPoint | Medium |
| 9. Anchoring Graph | Python/Excel | Google Sheets | Low |
| 10. Choice Matrix | PowerPoint | Canva | Low |

### Color Palette (Use Consistently)

```
Gains/Positive:   #2E7D32 (Dark Green)
Losses/Negative:  #C62828 (Dark Red)
Neutral/Info:     #1565C0 (Blue)
Warning:          #F57C00 (Orange)
Emphasis:         #FFD700 (Gold)
Background:       #FFFFFF (White)
Text:             #212121 (Near Black)
Grid:             #E0E0E0 (Light Gray)
```

---

These text-based mockups provide the blueprint. Now you (or a designer) can create the actual visual files following these specifications!
