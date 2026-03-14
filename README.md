# ICC Pipeline & Schedule - 

### prodreqdoc.md - Product Requirements Document - Status: WIP
### README.md - Project brainstorm and organization - Status - WIP

## Brainstorm - Feature List

### The Pipeline (Sales & Money)
* **Kanban Board:** A digital board with columns (Leads, Quoted, Review, Won, Lost) to move deals through.
* **Drag-and-Drop:** Click and slide a deal from one stage to the next.
* **Quick-Add Form:** A simple pop-up to create a deal with:
    * Client Name
    * Project Type (e.g., Pickleball, Basketball)
    * City
    * Dollar Amount
    * *Optional:* Start Date & how many days it will take.
* **The "At-a-Glance" Card:** The front of the card must show the Name, $, City, and Type without needing to click it.
* **The Scoreboard (Dashboard):** A header that live-calculates:
    * Total number of active deals.
    * Total dollar value of everything in the pipeline.
    * Total revenue from "Won" deals.
    * Total money lost (from the "Lost" column).
    * Average deal size.
    * **Actual Profit:** Calculations based on "Won" deals.
    * **Projected Profit:** Calculations based on what's still in the pipeline.

### The Calendar (Operations & Scheduling)
* **The "Year-at-a-Glance" View:** A single, scrollable page showing all 12 months (no clicking "Next Month" repeatedly).
* **"Won" Only Filter:** The calendar should ignore everything except deals moved to the "Won" column.
* **Gantt-Style Bars:** Projects appear as horizontal bars stretching across their scheduled dates.
* **Visual Separation:** Each project bar needs to look distinct (different colors or clear borders) so they don't bleed together.
* **Auto-Population:** If a "Won" deal has a start date and duration, it automatically draws itself on the calendar.

### Scheduling Logic
* To appear on the calendar, a "Won" deal must have a defined "Start Date" and "Days to Complete" (duration)
