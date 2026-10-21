# ECON 102 Quiz 2 App: User Guide

The ECON 102 Quiz 2 app puts a set of surplus and tax tools on your TI-84 Plus CE. This guide shows where each tool is, what to type, and how to read what it shows, with a worked example for each one.

The app has four tools, all reached from one menu:

- **Surplus and tax:** solves a taxed market. It shows the price buyers pay and sellers get, consumer and producer surplus before and after the tax, tax revenue, deadweight loss, and who bears the tax. It can also draw the market with each area filled in.
- **WTP and cost lists:** works from a list of buyers' willingness to pay or sellers' costs. It shows who buys or sells at a price, each person's surplus and the total, and what a price change does.
- **Tax size sweep:** compares a tax T with 2T and 3T, and finds the tax that raises the most revenue.
- **Elasticity and tax:** works from elasticities instead of curves, and compares elastic and inelastic markets in a 2x2 table.

Use the tools to check your own work. A tool only knows what you type in, and it rounds what it shows to 2 decimals (see [Reading results](#reading-results)).

## Contents

1. [Start and quit](#1-start-and-quit)
2. [Getting around](#2-getting-around)
3. [Typing in values and reading results](#3-typing-in-values-and-reading-results)
4. [What's where](#4-whats-where)
5. [Tool by tool](#5-tool-by-tool)
   - [Surplus and tax](#surplus-and-tax) · [WTP and cost lists](#wtp-and-cost-lists) · [Tax size sweep](#tax-size-sweep) · [Elasticity and tax](#elasticity-and-tax)
6. [The formulas it uses](#6-the-formulas-it-uses)
7. [What it changes on your calculator](#7-what-it-changes-on-your-calculator)
8. [Limits](#8-limits)
9. [Troubleshooting](#9-troubleshooting)
10. [Setup: loading the app](#10-setup-loading-the-app)

## 1. Start and quit

### Start the app

Press **PRGM**, choose **ECONQZ**, and press **ENTER** twice. The menu **ECON 102 QUIZ 2** appears.

The other four programs (TAXSOLV, WTPSURP, TAXSWEEP, ELASTIC) are the tools. ECONQZ runs them for you, but you can also start any of them directly from **PRGM** the same way.

### Quit

- On the ECON 102 QUIZ 2 menu choose **5: QUIT**.
- **Stop right away:** press **ON**, then choose **1: Quit**. This works at any point, even in the middle of a tool. (If you do this while a graph is showing, see [Troubleshooting](#9-troubleshooting).)

### Exams

Press-to-Test (exam mode) turns off all programs, so the app can't be used during a quiz that requires it.

## 2. Getting around

The main menu, **ECON 102 QUIZ 2**:

| Key | Item | Tool |
|---|---|---|
| **1** | SURPLUS AND TAX | [Surplus and tax](#surplus-and-tax) (TAXSOLV) |
| **2** | WTP AND COST LISTS | [WTP and cost lists](#wtp-and-cost-lists) (WTPSURP) |
| **3** | TAX SIZE SWEEP | [Tax size sweep](#tax-size-sweep) (TAXSWEEP) |
| **4** | ELASTICITY AND TAX | [Elasticity and tax](#elasticity-and-tax) (ELASTIC) |
| **5** | QUIT | ends the app |

| To do this | Press |
|---|---|
| Pick a menu item | its number (or arrow to it and press **ENTER**) |
| Answer a prompt | type the number, then **ENTER** |
| Go to the next results screen | **ENTER** |
| Leave a graph | any key |
| Leave a tool's menu | its **BACK** item |
| Stop everything | **ON**, then **1: Quit** |

When a tool finishes you are back at the ECON 102 QUIZ 2 menu. If you started the tool directly from PRGM, the calculator shows `Done` instead.

## 3. Typing in values and reading results

### Numbers

| What | How |
|---|---|
| Negative number | Use the **(-)** key at the bottom of the keypad, not the minus key. |
| Decimal | Type it as usual: `.5` or `0.5`. |
| A calculation | Prompts accept anything the calculator can work out, such as `400/2` or `3*25`. |
| An empty prompt | Pressing **ENTER** with nothing typed does nothing. Type a value. |
| Bad values | If a value doesn't make sense (for example P0 higher than A), the tool shows **INPUT PROBLEM** and what it needs. Press **ENTER** and type the values again. |

### The letters in the prompts

Every tool uses straight-line curves, with quantity on the X axis and price on the Y axis:

- **Demand:** P = A - D×Q. **A** is where demand meets the price axis (the highest price anyone would pay, the choke price). **D** is the slope.
- **Supply:** P = B + S×Q. **B** is where supply meets the price axis. Enter **0** if supply starts at the origin. **S** is the slope.
- **P0, Q0:** the equilibrium price and quantity with no tax.
- **T:** the tax per unit.
- **QT:** the quantity with the tax. **PC:** the price consumers (buyers) pay. **PP:** the price producers (sellers) receive. PC - PP = T.
- **QMAX:** where demand meets the quantity axis (the most anyone would buy, at a price of 0).
- **ED, ES:** the elasticity of demand and of supply at the equilibrium.

You never type D or S; the tools work out the slopes.

### Reading results

- **Rounding:** results show at most 2 decimals. 2500 shows as `2500`, 21.6666... as `21.67`. The math inside is not rounded.
- **Negative results** show with a raised minus, like `⁻7500` for -7500 (a change in surplus is usually negative under a tax).
- **NONE:** a price that doesn't exist because the tax stops all trade.
- **OUT:** a buyer or seller who doesn't trade at that price.
- **PCT:** percent. `50` means 50%.
- **DWL RATIO:** a DWL compared with the DWL of the base tax. `4` means 4 times as big.

## 4. What's where

### Find a tool fast

The keys column is what to press from the ECON 102 QUIZ 2 menu.

| To do this | Go to | Keys |
|---|---|---|
| [Solve a taxed market from A, B, P0, Q0 and T](#surplus-and-tax) | SURPLUS AND TAX ► KNOW A,B,P0,Q0,T | 1, 1 |
| [Same, when you know QMAX instead of A](#surplus-and-tax) | SURPLUS AND TAX ► KNOW QMAX NOT A | 1, 2 |
| [Same, when you know PC, PP and QT](#surplus-and-tax) | SURPLUS AND TAX ► KNOW PC,PP,QT | 1, 3 |
| [Draw the taxed market](#the-graph) | answer **1: YES** at VIEW GRAPH? | |
| [Consumer surplus from buyers' WTP](#wtp-and-cost-lists) | WTP AND COST LISTS ► BUYERS: CS | 2, 1 |
| [Producer surplus from sellers' costs](#wtp-and-cost-lists) | WTP AND COST LISTS ► SELLERS: PS | 2, 2 |
| [What a price change does to CS](#price-change) | WTP AND COST LISTS ► BUYERS: PRICE CHANGE | 2, 3 |
| [What a price change does to PS](#price-change) | WTP AND COST LISTS ► SELLERS: PRICE CHANGE | 2, 4 |
| [Compare taxes T, 2T, 3T](#tax-size-sweep) | TAX SIZE SWEEP | 3 |
| [Find the revenue-maximizing tax](#tax-size-sweep) | TAX SIZE SWEEP | 3 |
| [Burden and DWL from elasticities](#elasticity-and-tax) | ELASTICITY AND TAX | 4 |
| [Elastic vs inelastic comparison table](#elasticity-and-tax) | ELASTICITY AND TAX (second screen) | 4 |

## 5. Tool by tool

### Surplus and tax

- **Where:** ECON 102 QUIZ 2 ► SURPLUS AND TAX (keys **1**). Program TAXSOLV.
- **First choose how the problem gives the numbers** (menu **TAX SOLVER**):

| Choice | Asks |
|---|---|
| **1: KNOW A,B,P0,Q0,T** | `A DEMAND Y-INT=`, `B SUPPLY Y-INT=`, `P0 EQUIL PRICE=`, `Q0 EQUIL QTY=`, `T TAX PER UNIT=` |
| **2: KNOW QMAX NOT A** | `QMAX DEMAND X=`, then B, P0, Q0 and T as above. A is worked out from QMAX. |
| **3: KNOW PC,PP,QT** | `A DEMAND Y-INT=`, `B SUPPLY Y-INT=`, `PC BUYERS PAY=`, `PP SELLERS GET=`, `QT WITH TAX=`. The tax T = PC - PP, and P0 and Q0 are worked out. |
| **4: BACK** | back to the main menu |

- **Shows**, on three screens (press **ENTER** between them):
  1. **EQUILIBRIUM AND TAX:** P0 and Q0 with no tax, the tax T, QT with the tax, PC (what buyers pay) and PP (what sellers get).
  2. **A table, NO TAX and WITH TAX:** CS, PS, REV (tax revenue), TS (total surplus) and DWL. Total surplus with the tax includes the tax revenue: TS = CS + PS + REV, as taught in class. DWL = TS with no tax - TS with the tax.
  3. **DWL, CHANGE IN CS, CHANGE IN PS**, then **BURDEN**: how much of each unit of tax buyers pay (PC - P0) and sellers pay (P0 - PP), per unit and as a percent of the tax. The more inelastic side pays more.
- Then **VIEW GRAPH?**: **1** YES or **2** NO.
- **If the tax is too big** (T at least A - B), no one trades: QT is 0, PC and PP say NONE, screen 1 says **MARKET DISAPPEARS**, and all of the no-tax total surplus is lost (DWL = TS with no tax). The burden shows NO TRADE.

**Example (choice 1):** A = 400, B = 0, P0 = 200, Q0 = 100, T = 200. Keys from the main menu: **1**, **1**, then `400` **ENTER** `0` **ENTER** `200` **ENTER** `100` **ENTER** `200` **ENTER**.

| Screen | Shows |
|---|---|
| 1 | P0 NO TAX 200, Q0 NO TAX 100, T TAX PER UNIT 200, QT WITH TAX 50, PC BUYERS PAY 300, PP SELLERS GET 100 |
| 2 | CS 10000 and 2500, PS 10000 and 2500, REV 0 and 10000, TS 20000 and 15000, DWL 0 and 5000 |
| 3 | DWL 5000, CHANGE IN CS ⁻7500, CHANGE IN PS ⁻7500; buyers 100 per unit, 50 PCT; sellers 100 per unit, 50 PCT |

**Example (choice 3):** A = 400, B = 0, PC = 300, PP = 100, QT = 50 gives the same three screens, with P0 200, Q0 100 and T 200 worked out.

**Example (choice 2):** QMAX = 200, B = 0, P0 = 200, Q0 = 100, T = 200 gives the same screens again (A works out to 400).

**Example with decimals:** A = 100, B = 10, P0 = 40, Q0 = 30, T = 25 gives QT 21.67, PC 56.67, PP 31.67; CS 900 and 469.44, PS 450 and 234.72, REV 541.67, TS 1350 and 1245.83, DWL 104.17; buyers pay 16.67 per unit (66.67 PCT), sellers 8.33 (33.33 PCT).

**No tax:** T = 0 gives QT = Q0, PC = PP = P0 and DWL 0.

#### The graph

The graph takes about 3 seconds to draw. Press any key to leave it.

| You see | It is |
|---|---|
| Black line from the top left down to the quantity axis | demand |
| Black line rising from the price axis | supply |
| Black cross where they meet | the no-tax equilibrium (Q0, P0) |
| **Light blue** triangle at the top, labeled CS | consumer surplus with the tax |
| **Orange** rectangle, labeled TAX | tax revenue (T × QT) |
| **Green** triangle at the bottom, labeled PS | producer surplus with the tax |
| **Red** triangle pointing at the cross, labeled DWL (to the right of the cross) | deadweight loss |
| Black lines at PC and PP, and a vertical line at QT | the tax wedge |

The window is set from your numbers: from 0 to a bit past QMAX across, and from 0 (or a bit below B, if B is negative) to a bit above A up. With a small tax or a small QT some areas are thin, and a label can sit on a line. If no one trades, the whole surplus triangle is red (all DWL).

When you leave the graph, your own window, Y= functions and graph settings are put back.

### WTP and cost lists

- **Where:** ECON 102 QUIZ 2 ► WTP AND COST LISTS (keys **2**). Program WTPSURP.
- **Menu WTP AND COST LISTS:**

| Choice | What it does |
|---|---|
| **1: BUYERS: CS** | consumer surplus from buyers' willingness to pay (WTP) at one price |
| **2: SELLERS: PS** | producer surplus from sellers' costs at one price |
| **3: BUYERS: PRICE CHANGE** | what a price change does to consumer surplus |
| **4: SELLERS: PRICE CHANGE** | what a price change does to producer surplus |
| **5: BACK** | back to the main menu |

- **Asks:** `HOW MANY (1-10)=` (the number of people), then each person's value at `BUYER 1=`, `BUYER 2=`, ... (or `SELLER 1=`, ...), then `PRICE=` (choices 1 and 2) or `OLD PRICE=` and `NEW PRICE=` (choices 3 and 4).
- **Who trades:** a buyer buys when WTP is at least the price; a seller sells when cost is at most the price. Someone whose value equals the price trades with a surplus of 0.
- **Surplus:** a buyer's is WTP - price; a seller's is price - cost.

**One price (choices 1 and 2) shows two screens:**

1. **CONSUMER SURPLUS** (or PRODUCER SURPLUS): the price, the number of buyers (or sellers), QTY BOUGHT (or QTY SOLD), and the TOTAL CS (or PS).
2. One row per person: their number, WTP (or COST), and SURPLUS, or **OUT** if they don't trade. With 10 people, person 10 is on a second page (press **ENTER**).

**Example (choice 1):** 4 buyers with WTP 1000, 800, 700, 500, price 701. Keys: **2**, **1**, `4` **ENTER**, `1000` **ENTER** `800` **ENTER** `700` **ENTER** `500` **ENTER**, `701` **ENTER**.

- Screen 1: PRICE 701, BUYERS 4, QTY BOUGHT 2, TOTAL CS 398.
- Screen 2: buyer 1 WTP 1000 SURPLUS 299; buyer 2 800, 99; buyer 3 700, OUT; buyer 4 500, OUT.

**Same list at price 700** (see [Again](#again)): QTY BOUGHT 3, surpluses 300, 100, 0, OUT, TOTAL CS 400. Buyer 3 buys at exactly their WTP and gets 0 surplus.

**Example (choice 2):** 4 sellers with costs 500, 600, 800, 900, price 601: QTY SOLD 2, surpluses 101 and 1, TOTAL PS 102. At price 700: 200 + 100 = 300.

#### Price change

Choices 3 and 4 show one screen:

| Row | Means |
|---|---|
| OLD PRICE, NEW PRICE | what you typed |
| CS AT OLD, CS AT NEW (or PS) | total surplus at each price |
| CHANGE | new total - old total |
| IN AT BOTH | the change for people who trade at both prices: each one gains (or loses) the price difference |
| NEW ENTRANTS | the surplus of people who trade only at the new price |
| LEFT MARKET | the surplus lost by people who traded only at the old price (negative) |
| QTY OLD, NEW | how many trade at each price |

IN AT BOTH + NEW ENTRANTS + LEFT MARKET = CHANGE.

**Example (choice 3):** the 4 buyers above, OLD PRICE 801, NEW PRICE 701: CS AT OLD 199 (only buyer 1 buys), CS AT NEW 398, CHANGE 199, IN AT BOTH 100 (buyer 1 pays 100 less), NEW ENTRANTS 99 (buyer 2 joins), LEFT MARKET 0, QTY OLD 1, NEW 2.

**Example (choice 4):** the 4 sellers above, OLD PRICE 601, NEW PRICE 801: PS AT OLD 102, PS AT NEW 503, CHANGE 401, IN AT BOTH 400 (two sellers get 200 more each), NEW ENTRANTS 1 (the 800 seller joins), LEFT MARKET 0.

#### Again

After the results, the **AGAIN?** menu:

| Choice | Does |
|---|---|
| **1: SAME LIST, NEW PRICE** | keeps the list and asks only for the price(s) |
| **2: NEW LIST** | asks HOW MANY and the values again |
| **3: WTP/COST MENU** | back to the WTP AND COST LISTS menu |
| **4: DONE** | back to the main menu |

### Tax size sweep

- **Where:** ECON 102 QUIZ 2 ► TAX SIZE SWEEP (keys **3**). Program TAXSWEEP.
- **Asks:** A, B, P0, Q0 (as in [Surplus and tax](#surplus-and-tax)), then `BASE TAX T=` (above 0).
- **Shows**, on one screen: for the taxes T, 2T and 3T, the TAX, QT, REV (revenue) and DWL; then **DWL RATIO**, each DWL compared with the DWL at T; then the tax that raises the most revenue (**MAX REV AT TAX**), that revenue (**MAX REVENUE**), and the smallest tax at which no one trades (**NO MARKET IF T≥**).
- Then **REVENUE GRAPH?**: **1** YES or **2** NO. The graph shows revenue (up) against the size of the tax (across) from 0 to a bit past A - B: a hill with its top marked MAX, and your three taxes marked T, 2T and 3T. It takes about 4 seconds; press any key to leave.

**Example:** A = 400, B = 0, P0 = 200, Q0 = 100, base tax 100. Keys: **3**, `400` **ENTER** `0` **ENTER** `200` **ENTER** `100` **ENTER** `100` **ENTER**.

| Tax | QT | REV | DWL |
|---|---|---|---|
| 100 | 75 | 7500 | 1250 |
| 200 | 50 | 10000 | 5000 |
| 300 | 25 | 7500 | 11250 |

DWL RATIO 1, 4, 9. MAX REV AT TAX 200, MAX REVENUE 10000, NO MARKET IF T≥ 400.

**What to notice:** doubling the tax makes the DWL 4 times as big and tripling it 9 times (DWL grows with the square of the tax). Revenue rises, peaks halfway to A - B, then falls back to 0 when the market disappears.

### Elasticity and tax

- **Where:** ECON 102 QUIZ 2 ► ELASTICITY AND TAX (keys **4**). Program ELASTIC.
- **Asks:** `P0 EQUIL PRICE=`, `Q0 EQUIL QTY=`, `T TAX PER UNIT=`, `ED DEMAND ELAS=`, `ES SUPPLY ELAS=`. Type the elasticities at the no-tax equilibrium. A negative ED (like -0.5) is read as 0.5.
- **Shows**, on two screens:
  1. **ELASTICITY RESULTS:** QT WITH TAX, PC BUYERS PAY, PP SELLERS GET, BUYER SHARE PCT and SELLER SHARE PCT (of the tax), TAX REVENUE and DWL.
  2. **A 2x2 table** with the same P0, Q0 and T, where each elasticity is 0.5 (INEL, inelastic) or 2 (EL, elastic). For each CASE it shows **BUY** (the buyers' share of the tax, in percent) and the **DWL**.

**Example:** P0 = 200, Q0 = 100, T = 40, ED = 0.5, ES = 2. Keys: **4**, `200` **ENTER** `100` **ENTER** `40` **ENTER** `.5` **ENTER** `2` **ENTER**.

- Screen 1: QT 92, PC 232, PP 192, BUYER SHARE PCT 80, SELLER SHARE PCT 20, TAX REVENUE 3680, DWL 160.
- Screen 2:

| CASE | BUY | DWL |
|---|---|---|
| D INEL S INEL | 50 | 100 |
| D INEL S EL | 80 | 160 |
| D EL S INEL | 20 | 160 |
| D EL S EL | 50 | 400 |

With ED = 1 and ES = 1 instead: QT 90, PC 220, PP 180, buyers 50 PCT, revenue 3600, DWL 200.

**What to notice:** the side that is more inelastic pays more of the tax (inelastic demand with elastic supply: buyers pay 80%). The more elastic the curves, the bigger the DWL (both elastic: 400; both inelastic: 100).

## 6. The formulas it uses

Demand P = A - D×Q, supply P = B + S×Q.

| Quantity | Formula |
|---|---|
| Demand slope | D = (A - P0)/Q0, or P0/(QMAX - Q0) when you give QMAX, or P0/(Q0×ED) from an elasticity |
| Supply slope | S = (P0 - B)/Q0, or P0/(Q0×ES) from an elasticity |
| Quantity with the tax | QT = Q0 - T/(D+S), and 0 if T is at least A - B |
| Price buyers pay | PC = P0 + T×D/(D+S) |
| Price sellers get | PP = PC - T |
| Buyers' share of the tax | D/(D+S) (equal to ES/(ED+ES)) |
| CS, PS with no tax | (A - P0)×Q0/2 and (P0 - B)×Q0/2 |
| CS, PS with the tax | (A - PC)×QT/2 and (PP - B)×QT/2 |
| Tax revenue | T×QT |
| Total surplus with the tax | CS + PS + revenue |
| DWL | TS with no tax - TS with the tax, which is T×(Q0 - QT)/2 |
| Revenue-maximizing tax | (A - B)/2, with revenue (A - B)×Q0/4 |

## 7. What it changes on your calculator

- **Variables A to Z:** the tools use them and delete them when they finish, so anything you had stored in A to Z is gone. The graph tools also delete X and Y.
- **Lists and strings:** WTP AND COST LISTS keeps the values in a list named `ʟWTP` and its prompt in `Str1`, and deletes both at the end. L1 to L6 are never touched.
- **Graph settings:** the graphs save your window, Y= functions and graph format, and put them all back when you leave the graph. Your Y= functions are never changed. Two things are not put back: **stat plots are turned off**, and the screen is set to **Full** (not split).
- **MODE settings** are never changed.

## 8. Limits

- Straight-line supply and demand only, with A above P0 and P0 above B.
- Up to 10 people in WTP AND COST LISTS.
- Each number on a results screen has room for at least 9 characters (like 123456.78). Much bigger numbers can run into the next column.
- Results show at most 2 decimals. Round your final answer the way the problem asks.
- Tested on a TI-84 Plus CE emulator running OS 5.3 and 5.8.5. It needs a color TI-84 Plus CE with OS 5.3 or newer; it won't run on the black and white TI-84 Plus.

## 9. Troubleshooting

| What you see | What to do |
|---|---|
| **INPUT PROBLEM** | A value doesn't fit. The screen says what's needed (for example NEED A>P0>B, P0>0, Q0>0 AND T≥0). Press **ENTER** and type the values again. |
| `ERR:SYNTAX` right after typing a number | Usually a negative number typed with the minus key instead of **(-)**. Choose **1: Quit**, start again, and use **(-)**. |
| `ERR:UNDEFINED` right after choosing a menu item | One of the five programs is missing. Load all five again (see [Setup](#10-setup-loading-the-app)). |
| `ERR:ARCHIVED`, or a program marked `*` in PRGM | The program is in Archive. Press **2nd**, **MEM**, **2: Mem Mgmt/Del**, **7: Prgm**, highlight it and press **ENTER** to move it to RAM. |
| Stat plots are off after a graph | The graphs turn them off. Turn them back on with **2nd**, **STAT PLOT**. |
| You pressed **ON** while a graph was showing | Your graph settings weren't put back. On the home screen type `RecallGDB 9` (from the CATALOG) and press **ENTER**, or reset the window with **ZOOM**, **6: ZStandard**. |
| Results show as fractions, or with a fixed number of decimals | Press **MODE** and set **NORMAL**, **FLOAT**, and ANSWERS **AUTO** or **DEC**. |
| A label sits on a line in the graph | That area is thin for your numbers. The numbers on the results screens are what count. |
| An answer looks wrong | Check which numbers the problem gives (A or QMAX? P0 and Q0, or PC, PP and QT?), use **(-)** for negatives, and check the tax is per unit. |

## 10. Setup: loading the app

1. Install **TI Connect CE** (free from Texas Instruments) on a computer.
2. Connect the calculator with its USB cable and open the **Calculator Explorer**.
3. Drag in all five files from the `dist` folder: `ECONQZ.8xp`, `TAXSOLV.8xp`, `WTPSURP.8xp`, `TAXSWEEP.8xp` and `ELASTIC.8xp`.
4. If asked, send them to **RAM**, not Archive.
5. Press **PRGM** and check that all five are listed.
6. Quick check: run ECONQZ, press **1**, **1**, and type `400`, `0`, `200`, `100`, `200`. Screen 1 should show QT WITH TAX 50, PC BUYERS PAY 300 and PP SELLERS GET 100.

More detail, including what to check on the graph, is in the README that comes with the program files (`dist/README.md`).
