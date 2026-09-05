Fully Automated Daily Sales Reporting System (Excel)

An Excel-based sales reporting system that automates daily, monthly, and yearly sales tracking for a restaurant/retail-style business with Dine-in, Takeaway (TA), and Delivery channels — replacing manual daily calculations with a self-updating, formula-driven report.

📌 Overview
Manually preparing daily sales reports, tracking targets, and consolidating monthly/yearly numbers is time-consuming and error-prone. This system automates the entire process using Excel formulas — the user only enters raw daily sales and ticket counts, and every other metric (dates, holidays, APC/APT, totals, target achievement, growth) is calculated automatically.

✨ Features
Automated date generation — Month sheets auto-generate all dates from a single Start Date using DATEVALUE and chained IF formulas.
Automatic day & holiday tagging — Each date auto-fetches the weekday (TEXT) and matches against a master holiday calendar (VLOOKUP + IFERROR) maintained in Sheet1.
Channel-wise sales tracking — Separate Sales & Ticket inputs for Dine-in, Takeaway, and Delivery.
APC/APT (Average per Transaction) — Auto-calculated per channel and for total sales.
Target vs. Achievement analysis — Daily variance (Total Sales − Target) and achievement % (Total Sales / Target) calculated automatically.
Monthly summary dashboard — Highest/Lowest sale of the month, total days, Saturdays/Sundays count, average sales, channel-wise totals, last year's sales, and growth %.
Consolidated yearly report — All 12 months roll up into a single Consolidated sheet for year-level performance monitoring.
Zero manual calculation — Only raw sales & ticket figures need to be entered; everything else updates automatically.
🛠 Tech / Tools Used
Microsoft Excel
Formulas: VLOOKUP, IF, IFERROR, TEXT, DATEVALUE, arithmetic aggregation formulas
Structured multi-sheet linking across 14 sheets
📂 Workbook Structure
Sheet	Purpose
Sheet1	Master calendar — holiday list and month/year reference table used by all other sheets
Jan – Dec	One sheet per month, each with a Summary panel (month, year, date range, total days, Sat/Sun count, highest/lowest sale, target achieved, average sales, channel-wise totals, last year sales, growth %) and a Daily Sales Report table (date, day, holiday, channel-wise sales/tickets/APC, target, total sales, achievement %)
Consolidated	Year-level rollup combining all monthly totals for overall performance tracking
⚙️ How It Works
Set the Start Date once in a month's Summary panel — all dates for that month auto-populate.
The Day and Holiday columns auto-fill based on the date, cross-referencing the master calendar in Sheet1.
Enter daily Sales and Ticket count for each channel (Dine-in / TA / Delivery).
APC/APT, Total Sales, Total Tickets, Target Variance, and Achievement % are calculated instantly via formulas.
The Summary panel and Consolidated sheet update automatically as monthly data is entered — no manual rollups needed.
📈 Impact
Eliminated manual daily/monthly sales calculations
Improved reporting accuracy and consistency across months
Enabled faster, real-time business performance monitoring against targets
🚀 How to Use
Download/open Fully_Automatic_Daily_Sales_Report.xlsx
Set Start Date, Year, and Target Sales in each month's Summary panel
Enter daily Sales & Ticket figures for Dine-in, TA, and Delivery
View auto-updated metrics in the Summary panel and Consolidated sheet

👤 Author
Lalit Kumar, www.linkedin.com/in/lalit-kumar-463546328
