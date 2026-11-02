# Interview Q&A Bank: Mercados (Power, BESS, Markets, Policy)

Tips: answer in 30 to 60 seconds. Use the pattern **Definition, why it matters, India or MP example**. Where I say "verify", the number changes often. Check it before quoting.

---

## A. Introductory and HR

**1. Tell me about yourself.**
Give 3 parts: background (education and experience), what drew you to energy (the solar-evening-peak problem and storage), and why consulting at Mercados (mix of data, regulation and project work). End with: "I have been preparing on BESS policy, especially Madhya Pradesh's tenders, and I want to apply that."

**2. Why Mercados?**
It is a specialist energy and environment consultancy, so work is focused on power markets, regulation and renewables rather than being a generic firm. Mention you read their publications and want to learn from domain experts.

**3. Why Bhopal / are you willing to relocate?**
Madhya Pradesh is one of India's most active states for solar, pumped storage and BESS tenders, so a local team is close to the clients and regulator (MPERC, MPPMCL). Be honest about your location situation.

**4. Why consulting and not a utility or developer job?**
Consulting gives exposure to many clients, regulations and project types early on. Utilities and developers go deeper into one organisation.

**5. What are your strengths and weaknesses?**
Strength: learn fast and structure messy information (give an example). Weakness: pick a real, fixable one (for example "I used to over-polish work; now I set time limits and share drafts early").

**6. Where do you see yourself in 5 years?**
Leading analysis on storage and market projects, comfortable with regulatory filings and client presentations, and building specialist knowledge.

**7. How do you handle tight deadlines or ambiguity?**
Clarify the ask, break it into parts, share an early draft, and flag risks early. Use a real example.

**8. Are you comfortable with travel and long hours?**
Yes if that is true. Consulting involves client visits and deadline-driven periods.

---

## B. Grid basics

**9. What is grid frequency and why does it matter?**
It is the grid's heartbeat, 50 Hz in India (operating band about 49.90 to 50.05 Hz). Low frequency means demand exceeds supply, high means supply exceeds demand. Large drift can trip plants and cause blackouts.

**10. How is frequency controlled?**
In layers: primary (automatic governor response, seconds), secondary (AGC, minutes), tertiary (operator-dispatched reserves, 15+ minutes). Under CERC rules the grid operator (NLDC) coordinates reserves.

**11. What is DSM?**
Deviation Settlement Mechanism. Entities that draw or inject differently from their schedule pay or receive a charge tied to grid frequency and price. It discourages harmful deviations.

**12. How can a BESS help a discom with DSM?**
It absorbs or injects power quickly to keep the discom's drawal close to schedule, reducing penalties. It also provides cheaper balancing than buying expensive spot power at the wrong moment.

**13. What is the duck curve?**
The net-demand curve (demand minus solar) dips at midday and ramps sharply in the evening, shaped like a duck. Storage fills the belly and supplies the neck.

**14. What causes the evening peak in India?**
Lights, fans, ACs and TVs come on after sunset while solar output drops to zero. India's all-time peak demand is about 250 GW (record from 2024; verify the latest).

**15. What is curtailment?**
Switching off or reducing renewable output because the grid cannot absorb it or transmission is congested. Storage lets us save that energy.

**16. What is inertia and why is it falling?**
Spinning mass in coal, hydro and gas generators resists frequency changes. Solar, wind and batteries connect through inverters and give little natural inertia, so fast-acting services (including grid-forming batteries) become valuable.

**17. What is black start?**
Restarting a grid after a total blackout without outside power. Hydro, diesel and batteries can do it. Past blackouts in India: 2001 and 2012.

**18. What is a grid-forming vs grid-following inverter?**
Grid-following inverters copy the existing grid voltage and frequency. Grid-forming inverters can set the voltage and frequency themselves, helping weak grids and black start.

---

## C. Storage technology and economics

**19. Difference between MW and MWh?**
MW is power, how fast energy can be delivered. MWh is energy, how much is stored. A 100 MW / 200 MWh battery runs 2 hours at full power.

**20. What is round-trip efficiency?**
Energy out divided by energy in over a full cycle. Lithium iron phosphate (LFP) systems are roughly 85 to 90% (verify for specific vendors).

**21. What are depth of discharge, cycle life and degradation?**
Depth of discharge is how much of the capacity is used per cycle. Cycle life is how many cycles before capacity falls to a threshold (often 70 to 80%). Degradation is the gradual capacity loss, which drives augmentation (adding cells) and warranty terms.

**22. What is C-rate?**
How fast a battery charges or discharges relative to its capacity. 0.5C means full discharge in 2 hours.

**23. Which battery chemistries matter?**
LFP is the market standard (safe, long life, falling cost). NMC has higher energy density. Sodium-ion is emerging. Flow batteries suit long duration. Pumped hydro is the large-scale long-duration option.

**24. What is LCOS?**
Levelised Cost of Storage: total lifetime cost divided by total energy discharged, so you can compare technologies and durations.

**25. What drives BESS cost?**
Cell prices (the biggest factor), power electronics, balancing of system, installation, connectivity, land, and financing cost. Global cell prices have fallen sharply in recent years.

**26. 2-hour vs 4-hour storage, which is better?**
Depends on the need. 2-hour suits fast reserves and short peaks. 4-hour suits shifting solar into the whole evening peak. MP's recent standalone tenders specify 2-hour minimum duration, while its pumped hydro policy targets 4-hour.

**27. How does a battery earn money?**
Arbitrage (buy low, sell high), ancillary services, capacity or availability payments, avoided demand charges (BTM), and avoided DSM penalties.

**28. What are the main risks in a BESS project?**
Delays in grid connectivity, import dependence for cells, performance guarantee and degradation risk, offtaker (discom) payment risk, fire safety, and policy changes.

**29. How is BESS fire risk managed?**
Quality cells, thermal management, battery management system, fire suppression, spacing and containerisation, and compliance with safety standards.

**30. What is augmentation?**
Adding cells or modules over time to keep contracted capacity as the battery degrades.

---

## D. FTM vs BTM and business models

**31. Explain FTM vs BTM.**
FTM sits on the grid side of the meter and serves the system (shifting, ancillary services, black start, firm renewables). BTM sits on the customer side and cuts that customer's bills.

**32. What are BTM use cases?**
Peak shaving to reduce demand charges, time-of-day tariff arbitrage, backup power, higher self-consumption of rooftop solar, and EV charging support.

**33. Which is more bankable, FTM or BTM?**
FTM with a long contract from a creditworthy buyer plus VGF is easier to finance. BTM needs a customer-by-customer payback case.

**34. What is a BOO model?**
Build-Own-Operate. The developer finances, builds and runs the asset and is paid under the contract (as in MPPMCL's 625 MW / 1,250 MWh tender).

**35. What is tolling?**
The buyer controls charging and dispatch and pays the owner a fixed capacity fee, while the owner delivers availability and efficiency.

**36. What is revenue stacking?**
Using the same battery for several services (arbitrage, reserves, capacity) to improve returns, subject to market rules.

---

## E. Renewable integration

**37. What is FDRE?**
Firm and Dispatchable Renewable Energy. A solar plus wind plus storage package (sometimes with backup) that commits to a delivery profile and availability level, tendered by SECI, NTPC, NHPC and SJVN.

**38. What is co-located solar plus storage and why use it?**
A battery at the same site sharing the grid connection. Benefits: lower connection and land cost, less curtailment, and evening sales at better prices.

**39. Difference between co-located and standalone BESS?**
Standalone BESS is independent and can charge from the grid. Co-located is tied to a generator and may be restricted to charging from it, depending on rules and contract.

**40. What is a hybrid project?**
Two or more generation types (solar plus wind) at one connection, with or without storage.

**41. What is the ISTS waiver?**
A waiver of inter-state transmission charges for qualifying renewable and storage projects commissioned within specified dates. Check the current cut-off.

**42. How do you integrate 500 GW of non-fossil capacity?**
Storage, transmission expansion (green corridors), flexible demand, better forecasting, flexible coal operation, and market reforms.

---

## F. Ancillary services

**43. What are ancillary services?**
Services that keep the grid stable: frequency regulation and reserves, voltage support, black start.

**44. Primary, secondary, tertiary reserves?**
Primary is automatic and immediate. Secondary restores frequency (AGC) and tertiary is operator-dispatched backup. Official CERC timings: secondary responds in about 30 seconds and lasts up to ~15 minutes, tertiary is 15+ minutes. Your notes cite 5, 5 to 10 and 15 to 30 minutes, so use the version your source or company uses and mention the difference.

**45. Which regulation governs them?**
CERC (Ancillary Services Operations) Regulations 2022, with NLDC as the nodal agency. Verify the latest amendments.

**46. Why are batteries good at ancillary services?**
Millisecond response, high ramp rates, precise control, and no fuel cost when idle.

---

## G. Market structure

**47. What are the Indian power exchanges?**
IEX, PXIL and HPX. IEX is the largest.

**48. What market segments exist?**
Day-Ahead Market (DAM), Real-Time Market (RTM, near-real-time auctions through the day, verify the exact timing), term-ahead contracts, and green markets (Green DAM). Market coupling is being introduced to find a single national clearing price. Verify its status.

**49. How are prices set?**
Merit order. Buy and sell bids are matched, and the market-clearing price is where supply meets demand. There is a regulatory price cap (₹10/kWh on exchanges, verify the current cap).

**50. Why do prices spike in the evening?**
Solar disappears while demand peaks, so expensive generators set the price. That spread is the storage arbitrage opportunity.

**51. What is the difference between bilateral PPAs and exchange trading?**
PPAs are long-term contracts at agreed tariffs. Exchange trading is short-term, price-discovered and flexible but volatile.

**52. What is open access?**
The right of consumers and generators to use the transmission or distribution network for third-party power purchase, subject to charges (wheeling, cross-subsidy surcharge, additional surcharge).

**53. What is the Green Energy Open Access Rule 2022?**
It simplifies access to renewable energy for consumers with a lower threshold (100 kW), faster approvals and a green tariff option. Verify the details.

**54. What is GNA?**
General Network Access, CERC's framework for granting transmission access to users, replacing older long-term access forms.

---

## H. Regulation and law

**55. Who are the key institutions?**
CERC (central regulator), SERCs such as MPERC (state), CEA (planning and standards), MoP (policy), SECI, NLDC/RLDC/SLDC (system operators), CTUIL (central transmission planning), POSOCO/Grid-India.

**56. Section 62 vs Section 63 of the Electricity Act?**
Section 62: the regulator determines tariff. Section 63: tariff is discovered by transparent competitive bidding under government guidelines, and the regulator adopts it.

**57. What are ARR, true-up and MYT?**
ARR is the Annual Revenue Requirement of a utility. True-up adjusts past estimates to actual costs. MYT is a multi-year tariff framework with set trajectories.

**58. What is the cross-subsidy surcharge?**
A charge on open-access consumers that compensates the discom for losing high-tariff customers who subsidised others.

**59. What are wheeling charges?**
Charges for using the distribution network to carry power.

**60. What is a PPA and what are its key terms?**
Power Purchase Agreement: tariff, term (for example 12 years in MP BESS tenders), availability guarantees, payment security, change-in-law clauses, termination rules.

**61. What is change-in-law?**
A clause that compensates the developer when new laws or duties change project costs after bid submission.

---

## I. Policy and schemes

**62. What is VGF for BESS?**
Viability Gap Funding. A central subsidy reducing the upfront cost. The first scheme was 4,000 MWh. The 2025 scheme offers up to ₹18 lakh/MWh in tenders such as MP's.

**63. What is ACC PLI?**
A production-linked incentive (₹18,100 crore, about 50 GWh) to build advanced chemistry cell manufacturing in India and reduce import dependence.

**64. RPO vs ESO?**
RPO (now RCO, Renewable Consumption Obligation) requires a share of renewable energy consumption. ESO requires a share of energy to be backed by storage, rising from about 1% in 2023-24 toward 4% by 2029-30 (verify updates).

**65. What is RDSS?**
Revamped Distribution Sector Scheme: central support for reducing discom losses and installing smart meters.

**66. What is the National Electricity Plan / storage target?**
CEA's plan projects large storage needs by 2030 and 2032 (hundreds of GWh). Verify the latest numbers before quoting.

**67. What is the Energy Conservation (Amendment) Act 2022 role?**
It enables renewable and carbon-market obligations (RCO, carbon credit trading).

**68. What is CCTS?**
India's Carbon Credit Trading Scheme.

**69. What is Time-of-Day tariff and why does it matter for BTM storage?**
Higher prices at peak hours and lower at solar hours. Customers use batteries to shift consumption, so ToD creates the bill-saving case.

---

## J. Madhya Pradesh specifics

**70. Describe MP's BESS tenders.**
MPPMCL issued 750 MW / 1,500 MWh (Jan 2026) and 625 MW / 1,250 MWh (July 2026). Terms: at least 2 hours, two cycles a day, VGF up to ₹18 lakh/MWh, 12-year agreement, indigenous software, no refurbished cells, and developer-arranged land.

**71. MP's storage policies?**
Pumped Hydro Storage Policy (Feb 2025): 12,000 MW of 4-hour storage by 2034-35, 10-year duty/cess exemption. Renewable Energy Policy 2025: 10,000 MW RE parks, 50% wheeling waiver for 5 years, 10-year electricity duty exemption.

**72. Name MP's flagship projects.**
Morena solar plus storage (about 440 MW plus 880 MWh), Gandhi Sagar pumped storage (1,920 MW, Greenko), Neemuch solar park, Rewa solar park (750 MW). Reported tariff for Morena about ₹2.70/kWh. Sources disagree on scale, so verify.

**73. Who are MP's key power institutions?**
MPERC (regulator), MPPMCL (bulk buyer), MP Power Transmission Co, and three regional discoms (East, Central at Bhopal, West at Indore). Verify current names.

**74. Why is MP good for storage?**
Large solar capacity, good land, pumped hydro potential, and active state policy support.

**75. What would you check before advising a developer on an MP BESS bid?**
Tender terms (duration, cycles, availability), VGF eligibility, connectivity and land, payment security from the discom, cell supply and local-content rules, financing assumptions and degradation.

---

## K. Analytical and case questions

**76. How would you size a 100 MW BESS for an MP discom?**
1) Get the load profile and solar generation profile. 2) Find the evening peak and the shortfall energy. 3) Choose duration (2h or 4h) to cover the target window. 4) Account for efficiency and degradation. 5) Compare with alternatives (pumped hydro, gas peaker, demand response). 6) Check tariff vs the avoided cost of peak power purchases.

**77. How would you estimate the revenue of a 100 MW / 200 MWh arbitrage battery?**
Daily revenue = energy discharged x (peak price - charging price) x efficiency x cycles. Example: 200 MWh x 0.88 efficiency x ₹4/kWh spread = about ₹7 lakh/day per cycle (illustrative). Subtract charging losses, O&M, degradation and financing.

**78. Is a ₹2.70/kWh solar-plus-storage tariff reasonable?**
It signals strong competition and falling costs, but assess: share of storage, delivery hours, penalties, and what firm output the buyer actually gets. Compare against alternatives such as new coal or exchange evening prices.

**79. A discom has high AT&C losses. How do you improve its finances?**
Smart metering, feeder segregation, theft control, better billing and collection, ToD tariffs and timely subsidy payments. Link to why weak discom credit raises project risk.

**80. How would you forecast power prices?**
Combine demand forecasts, generation mix, fuel costs, weather, transmission constraints and regulatory caps, then run scenarios on a dispatch or merit order model.

**81. What data and tools would you use?**
Excel and Python, grid-india and CEA data, exchange price data, MPERC orders, and tools for load profiles and dispatch simulation.

**82. How would you present a recommendation to a client?**
Lead with the answer, support with 3 key numbers, show the main risks and options, and be clear on assumptions.

---

## L. Current affairs and trends

**83. What changes are you watching?**
Falling battery prices, hybrid and FDRE tenders, market coupling, ESO enforcement, pumped hydro pipeline, transmission constraints, green hydrogen, nuclear and SMR announcements, and carbon markets.

**84. What are the main challenges for storage in India?**
Import dependence for cells, connectivity and land, discom payment security, unclear revenue for merchant projects, and inconsistent state rules.

**85. Is coal still needed?**
Yes in the near term for baseload, with flexibilisation to complement renewables, while storage and renewables take a growing share.

---

## M. Questions you can ask them

1. What will the Bhopal team's first engagements look like (regulatory work, market studies, BESS advisory)?
2. Which clients or states will this office serve?
3. How is a new joiner trained and supervised?
4. What tools and models does the team use?
5. What does success look like in the first 6 months?

---

## N. Honest-answer rule

If you don't know a number, say: "I'm not sure of the exact figure, but my understanding is... and I would verify it against the latest CERC/MoP notification." Interviewers value honesty and structure over memorised trivia.

## O. Check before the interview
- Confirm the Bhopal role and location (I could not verify a Mercados Bhopal office).
- Verify: ESO percentages, VGF details, ISTS waiver dates, exchange price cap, market coupling status, peak demand record, and MPERC storage orders.
