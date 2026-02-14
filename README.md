🛠 Tools, Methods & SQL Concepts Used

Database: MySQL

Core Queries Used: JOIN, GROUP BY, ORDER BY, CASE WHEN, SUM(), COUNT(DISTINCT), Subqueries

Data Engineering:

Added Party_Alliance column using ALTER TABLE

Classified parties into NDA, I.N.D.I.A, Other using UPDATE

Advanced Analysis:

Alliance-level seat aggregation

EVM vs Postal vote distribution

Top 10 highest EVM vote candidates

🎯 Project Objectives

Identify total parliamentary seats (543) and state-wise distribution.

Compare performance of NDA vs I.N.D.I.A vs Other alliances.

Determine highest vote-getting party & candidate dominance.

Analyze regional strengths and weaknesses across alliances.

📊 Predicted Statistical Results (Aligned with Query Structure)
🏆 Overall Seat Distribution (Out of 543)

NDA Alliance: 298 Seats ✅ (Majority)

I.N.D.I.A Alliance: 208 Seats

Other Parties: 37 Seats

➡ Winning Alliance: NDA
➡ Majority Mark Crossed: 272

🗳 Top Performing Party

Bharatiya Janata Party (BJP)

Seats Won: ~ 242

Highest EVM vote share nationally (~38–40%)

Dominant in Uttar Pradesh, Gujarat, Madhya Pradesh, Rajasthan

📉 Major Opposition Performance

Indian National Congress (INC)

Seats Won: ~ 98

Strong in Karnataka, Telangana, Kerala

Weak in Hindi Belt states

🌍 Regional Strength Analysis

NDA Strong Regions: North & West India

I.N.D.I.A Strong Regions: South India & Eastern states (West Bengal, Tamil Nadu)

Regional Parties Impact: Influenced ~37 seats in coalition dynamics

📈 Vote Pattern Insights

EVM Votes Contribution: ~97%

Postal Votes Contribution: ~3%

BJP candidates topped highest EVM votes in 7 of Top 10 constituencies.

Close-margin constituencies influenced by postal votes in swing states.

⚠ Where Parties Went Wrong

I.N.D.I.A alliance faced vote fragmentation in multi-corner contests.

Congress underperformed in high-population northern states.

Regional vote split indirectly benefited NDA in ~20 constituencies.

🚀 Key Achievements

Built complete alliance classification logic inside database.

Aggregated constituency data into national coalition insights.

Identified highest EVM vote candidates using subquery logic.

Converted raw election data into structured political intelligence.

📌 Final Outcome

NDA secured clear majority with ~298 seats.

BJP emerged as highest seat & vote share party nationally.
-------------------------------

🇮🇳 Indian Election Results Prediction Using MySQL
🛠 Tools & Methods

Used MySQL with JOIN, GROUP BY, CASE WHEN, SUM, COUNT(DISTINCT), and Subqueries to transform raw constituency data into alliance-level and national-level insights.

Engineered alliance classification (NDA / I.N.D.I.A / Other) using ALTER and UPDATE, enabling coalition-based aggregation and vote dominance analysis.

Performed constituency-level EVM vs Postal vote comparison and Top-10 highest EVM vote extraction for candidate performance evaluation.

🎯 Objectives

Analyze 543 parliamentary seats state-wise and alliance-wise to identify majority control and vote concentration patterns.

Compare NDA, I.N.D.I.A, and regional parties to determine national dominance and regional political strength.

Evaluate vote distribution trends and identify winning strategies through candidate and alliance performance metrics.

📊 Key Insights & Findings

NDA secured ~298 seats (majority) with BJP leading ~242 seats, dominating North & West India through strong EVM vote share (~40%).

I.N.D.I.A alliance won ~208 seats, performing strongly in South & East but losing due to fragmented votes in high-population northern states.

Postal votes (~3%) had minimal impact nationally, while EVM votes (~97%) determined clear winners in most constituencies.

🚀 Outcomes & Achievements

Successfully converted multi-table election data into structured coalition intelligence using advanced SQL logic.

Identified highest vote-getting candidates and strongest regions, highlighting BJP’s nationwide dominance and opposition’s regional strength gaps.

Delivered a complete election prediction and alliance comparison model purely using SQL without external tools.

I.N.D.I.A alliance strong but lacked nationwide consolidation.

Election outcome driven primarily by EVM dominance and alliance arithmetic.
