# Episode 6: Thermal Processing — Killing Microbes with Math

*FNH 200 — The Podcast. Episode 6: canning, pasteurization, and the numbers that keep botulism out of your soup.*

---

**MAYA:** Dev, here's the uncomfortable truth about canned food: you can never prove a can is sterile.

**DEV:** That's… not reassuring. I have four cans of beans.

**MAYA:** Because "sterile" would mean *zero* microbes, and you can't prove a negative without opening every can. So the industry does something wilder: it uses **logarithms** to make the probability of survival so small it stops mattering. Today we do the math that makes canned food safe — D-values, Z-values, F-values — and I promise it's more fun than it sounds.

**DEV:** You've promised that before.

**MAYA:** This time there's a number called **12D** and it's beautiful. Let's go.

---

## Three heat treatments, three targets

**MAYA:** Start with the lineup. Three thermal processes, and the exam tests them by **what they target** 🎯:

- **Blanching** — mild heat. Target: **enzymes**. Remember dipping apple slices in hot water to stop browning? That's blanching, killing **polyphenol oxidase**. Also what you do to vegetables before freezing.
- **Pasteurization** — moderate heat. Target: **pathogenic (ugly) microorganisms**. The known question: what's the main purpose of pasteurizing milk? **To eliminate pathogens.** Not spoilage organisms, not psychrotrophs, not enzymes. Pasteurized milk still spoils — that's why it lives in your fridge with a short shelf life.
- **Commercial sterilization** — heavy heat. Target: essentially *everything*, aimed squarely at ***Clostridium botulinum* spores**. This is canning and UHT.

**DEV:** Pasteurization makes it safe; sterilization makes it shelf-stable.

**MAYA:** Exactly the distinction. Now — precision question 🎯: what does commercial sterilization target? Spoilage organisms ✓, pathogens ✓, spores ✓… and **thermophilic spores**? **No.** Thermophiles need 50 °C-plus to grow, so surviving thermophilic spores just sit there harmlessly in your pantry. We don't waste heat killing them. That's *why* it's called **commercial** sterility rather than absolute sterility.

## Canning vs UHT: order of operations

**MAYA:** Two ways to commercially sterilize, and the difference is one exam question 🎯:

- **Canning** — food goes into the container *first*, gets sealed, *then* the whole package is heated. Food in, then heat.
- **UHT (Ultra-High Temperature)** — the food is **heated first**, flash-treated at very high temperature, *then* filled into the container. Heat first, then package.

**DEV:** So with UHT the container never goes through the cooker… which means the container has to be sterile already.

**MAYA:** And that's the whole game — it's called **aseptic packaging**. Both the food and the package are sterilized separately, then married in a sterile environment. Which raises the sanitation question 🎯: canning containers just need to be clean, because the retort sterilizes everything afterward. UHT containers must be **fully sterilized beforehand**.

Products: canning gives you SPAM, canned tuna, soup, canned peaches. UHT-aseptic gives you shelf-stable milk (Parmalat), ketchup, sriracha, protein shakes, those latte pouches — all sitting unrefrigerated on a shelf.

**DEV:** Shelf-stable milk always felt like a crime against nature.

**MAYA:** It's a crime against *psychrotrophs*. Speaking of packaging — that juice box has a proper name 🎯: it's a **Tetra Pak**. And how do you sterilize a Tetra Pak, given you can't exactly boil cardboard? **Hydrogen peroxide.** Not steam, not ascorbic acid — hydrogen peroxide. Then the packaging materials get compared on pros and cons: **tin cans** (durable, cheap, opaque, but heavy and can corrode), **glass jars** (inert, resealable, see-through, but heavy and breakable), **Tetra Pak** (light, cheap to ship, but not resealable and hard to recycle), **retortable pouches** (light, heat fast, but puncture), and **plastic bottles**.

## D-value: the decimal reduction time

**MAYA:** Now the math. Microbes don't die all at once — they die **logarithmically**. Every fixed interval of heating kills the same *percentage*, not the same number. So we plot survivors on a **logarithmic** y-axis against time, and get a straight line: the **thermal death rate curve**.

**DEV:** And the log axis is the one where the gridlines bunch up — 1, 10, 100, 1000.

**MAYA:** That's the one. The slope gives us the key number 🎯: the **D-value**, or **decimal reduction time** — **the time it takes to kill 90% of the microorganisms**, i.e. reduce the population by one log cycle, one factor of ten.

**DEV:** 90%, not 100%. So it's 6000 → 600 → 60 → 6…

**MAYA:** Each D-value interval, one decimal place gone. And the crucial caveat 🎯: the D-value is fixed for **the same microorganism, in the same food, at the same temperature**. Change any of those three and the D-value changes.

Reading the curves: on a thermal death rate graph, **steeper line = faster death = smaller D-value**. So if you see three lines A, B, C with C the shallowest, **C has the largest D-value** — it's the toughest bug. That's also how the lecture's graph ranks resistance: **vegetative cells** die fast (steep), ***C. botulinum* spores** are much tougher, and **thermophilic spores** are toughest of all.

**DEV:** Give me a worked one.

**MAYA:** Chicken broth. 4,000 units of bacteria; after **18 minutes** at 98 °C, **4 units** remain. 4,000 → 400 → 40 → 4 is **three log cycles** in 18 minutes, so **D = 6 minutes**. Another: 40,000 → 4,000 in 4 minutes is one log cycle, so **D = 4 minutes**; getting to 4 units is four log cycles = **16 minutes**; down to 0.4 units is five cycles = **20 minutes**.

## 5D and 12D: how long do we actually process?

**MAYA:** Now, how many log cycles is enough? This is where **pH 4.6** finally pays off 🎯:

- **pH at or above 4.6** — low-acid foods. *C. botulinum* can grow. Process for **12D — twelve times the D-value.** Twelve log reductions.
- **pH below 4.6** — high-acid foods. Botulinum can't grow. Process for **5D** — five log reductions is plenty.

**DEV:** Twelve log cycles. That's a trillion-fold reduction.

**MAYA:** That's the famous **"botulinum cook."** Start with one spore per can, and after 12D your odds of a survivor are one in a trillion. That's how you get safety without ever proving sterility.

Worked examples 🎯 — these show up verbatim:
- **Tomato juice, pH 3.8, D = 5 min at 91 °C.** High-acid → 5D → **25 minutes**.
- **Chicken broth, pH 6.2, D = 6 min.** Low-acid → 12D → **72 minutes**.

**DEV:** So acid food gets a quick bath, low-acid food gets boiled forever. That's why home-canning green beans is terrifying and jam is easy.

**MAYA:** Precisely why jam is a beginner project and low-acid vegetables need a pressure canner.

## Z-value: turning up the heat

**MAYA:** But 72 minutes wrecks the food. So we raise the temperature — and we need to know how much time that buys. Enter the **Z-value** 🎯: **the change in temperature that causes a 10× change (one log cycle) in the D-value.**

**DEV:** So Z is the exchange rate between degrees and time.

**MAYA:** Perfect phrasing. Plot **D-value against temperature** on a log axis and you get the **thermal death TIME curve** — different graph, different axes. Careful 🎯: *thermal death **rate** curve* = survivors vs time. *Thermal death **time** curve* = D-value vs temperature.

Worked example: a bug with **D = 5 min (300 s) at 91 °C** and **Z = 5 °C**. Go from 91 to 121 °C — that's **30 degrees ÷ 5 = 6 log cycles**. So D drops by 10⁶: 300 s → **0.0003 seconds**.

**DEV:** Three ten-thousandths of a second. From five minutes.

**MAYA:** Thirty degrees, six orders of magnitude. That's the entire justification for UHT — blast it hot for a heartbeat instead of stewing it for an hour, and the food survives with its flavour intact.

Another from the lecture — pineapple juice at 96 °C for 30 min. **Bacteria A**: 48,000 → 4,800, one log, so D = **30 min**; Z = 10 °C. **Bacteria B**: 150,000 → 150, three logs, so D = **10 min**; Z = 5 °C. Now raise to 106 °C: A gains one cycle → **3 min**; B gains two cycles → **0.1 min**. Drop to 86 °C instead: A → **300 min**, B → **1000 min**. Note B started tougher-sounding but is far more heat-sensitive at high temperatures — **a small Z-value means very responsive to temperature**.

## F-value: the whole process in one number

**MAYA:** Last term 🎯. The **F-value** is the total processing time needed to sterilize a specific organism, standardized at the reference temperature **121.1 °C (250 °F)**, at the **slowest heating point** in the container.

Recipe for calculating it:
1. Convert the D-value to **121 °C** using the Z-value.
2. Check the **pH** → decide **5D or 12D**.
3. Multiply.

Worked 🎯: **ranch dressing, pH 5.3, D = 3 min (180 s) at 91 °C, Z = 10 °C.** Step 1: 30 degrees ÷ 10 = 3 log cycles, so 180 s → **0.18 s** at 121 °C. Step 2: pH 5.3 is **above** 4.6 → low-acid → **12D**. Step 3: 12 × 0.18 = **F = 2.16 seconds**.

**DEV:** The pH check is where people lose the marks, isn't it.

**MAYA:** Every time. Convert first, *then* ask 5D or 12D.

## The margin of safety, and where the cold spot hides

**MAYA:** Why trust all this? The **margin of safety** 🎯 is deliberately stacked — assume *C. botulinum* is present; assume it's in its most resistant form, **spores**; and design the process using an **even more heat-resistant relative** of it. Plus the known "all of the above": botulinum **can't grow in acid**, **sanitation minimizes the starting load**, and **the kill time is based on a highly heat-resistant spore**. Belt, braces, and a second pair of braces.

**DEV:** And "slowest heating point" — that's a real spot in the can?

**MAYA:** The **cold point**, and it depends on how heat moves 🎯:

- **Conduction** — heat crawls molecule to molecule in straight lines. Happens in **solid** foods: SPAM, pumpkin purée, cranberry sauce that gels during processing. The cold point sits at the **geometric centre**.
- **Convection** — heat rides fluid currents; liquid warms at the walls, rises, circulates. Happens in **thin liquids**: broth, juice. Much faster, and the cold point sits **lower**, below centre.

The known question: **corn chowder** — liquid with chunks in it? **Mainly convection, with some conduction.** And a can of **SPAM** — solid block — is heated by **conduction**, cold point at the geometric centre. Cranberry sauce is sneaky: it starts liquid and *gels* mid-process, so it switches from convection to conduction partway through.

**DEV:** So the engineers design the whole process around the unluckiest molecule in the can.

**MAYA:** The most protected microbe in the coldest corner. If it dies, everybody dies.

## Outro quiz — rapid fire

**MAYA:** Recap! Three treatments, three targets.

**DEV:** Blanching kills enzymes like polyphenol oxidase. Pasteurization kills pathogens. Commercial sterilization goes after everything, especially *C. botulinum* spores — but not thermophilic spores, since they can't grow at storage temperature anyway.

**MAYA:** Canning vs UHT.

**DEV:** Canning: food in the container, then heat. UHT: heat the food first, then fill into a pre-sterilized container — aseptic packaging. Tetra Pak is the official name, sterilized with hydrogen peroxide.

**MAYA:** D-value.

**DEV:** Decimal reduction time — time to kill 90%, one log cycle. Fixed for a given organism, food, and temperature. Steeper line, smaller D.

**MAYA:** 5D or 12D?

**DEV:** pH below 4.6, high-acid, 5D. pH 4.6 or above, low-acid, 12D — the botulinum cook. Tomato juice at pH 3.8 with D = 5 min → 25 minutes. Chicken broth at pH 6.2 with D = 6 min → 72 minutes.

**MAYA:** Z-value.

**DEV:** Degrees of temperature change that shift the D-value by 10×. D = 5 min at 91 °C with Z = 5: going to 121 °C is six log cycles, so 0.0003 seconds.

**MAYA:** F-value recipe.

**DEV:** Convert D to 121.1 °C using Z, check pH for 5D or 12D, multiply. Ranch dressing at pH 5.3: 0.18 s × 12 = 2.16 seconds.

**MAYA:** Cold point.

**DEV:** Conduction in solids like SPAM — cold point dead centre. Convection in liquids — cold point lower. Corn chowder is mainly convection with some conduction.

**MAYA:** Flawless. Next episode: the opposite extreme — Lesson 7, low temperature preservation. Why your ice cream gets crunchy and why slow freezing ruins strawberries.

**DEV:** Finally, a lesson I can eat during.

*[Outro music]*
