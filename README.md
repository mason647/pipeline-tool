The Pipeline (Sales & Money)

    Kanban Board: A digital board with columns (Leads, Quoted, Review, Won, Lost) to move deals through.

    Drag-and-Drop: Click and slide a deal from one stage to the next.

    Quick-Add Form: A simple pop-up to create a deal with:

        Client Name

        Project Type (e.g., Pickleball, Basketball)

        City

        Dollar Amount

        Optional: Start Date & how many days it will take.

    The "At-a-Glance" Card: The front of the card must show the Name, $, City, and Type without needing to click it.

    The Scoreboard (Dashboard): A header that live-calculates:

        Total number of active deals.

        Total dollar value of everything in the pipeline.

        Total revenue from "Won" deals.

        Total money lost (from the "Lost" column).

        Average deal size.

        Actual Profit: Calculations based on "Won" deals.

        Projected Profit: Calculations based on what's still in the pipeline.

The Calendar (Operations & Scheduling)

    The "Year-at-a-Glance" View: A single, scrollable page showing all 12 months (no clicking "Next Month" repeatedly).

    "Won" Only Filter: The calendar should ignore everything except deals moved to the "Won" column.

    Gantt-Style Bars: Projects appear as horizontal bars stretching across their scheduled dates.

    Visual Separation: Each project bar needs to look distinct (different colors or clear borders) so they don't bleed together.

    Auto-Population: If a "Won" deal has a start date and duration, it automatically draws itself on the calendar.

Product Requirements Document: ICC Pipeline & Schedule
1. Problems We Are Solving
   
Financial Blind Spots: Business owners currently have to guess or manually calculate how the company is doing financially in terms of active pipeline, potential profit, and closed-won revenue.

Leads Slipping Through the Cracks: Without a visual, deal-by-deal tracking system, individual opportunities can easily be forgotten or stalled in the sales process.

Fragmented Scheduling: Traditional calendars require users to click through month by month to figure out what projects are coming up, making it difficult to get a high-level view of the company's yearly timeline.

2. Product Goals
   
Instant Financial Visibility: Provide a real-time, zero-effort dashboard that calculates key business metrics (including projected and actual profit) automatically.

Frictionless Pipeline Management: Create a visual Kanban board that makes adding and moving deals effortless while capturing scheduling data early.

Simplified Yearly Scheduling: Deliver a single-page, Gantt-style yearly overview specifically for scheduled, closed-won projects that is highly legible.

3. Epics
   
Epic 1: The Pipeline View
This epic covers the core sales tracking functionality, combining high-level financial and profit metrics (Dashboard) with granular, day-to-day deal management (Kanban Board).

Epic 2: The Calendar View
This epic focuses on operational visibility, translating closed-won sales into a manageable, visually distinct, year-at-a-glance project schedule.

4. User Stories
   
Epic 1: Pipeline View

Dashboard: As a business owner, I want to see an overall dashboard of active deals, pipeline value, lost value, and profit metrics, so that I do not have to guess how the company is doing financially.

Kanban Board: As a business owner, I want to easily submit a new deal and slide it between pipeline stages, so that I have a deal-by-deal view and ensure no individual deals slip through the cracks.

Deal Snapshots: As a business owner, I want every deal card to display core information (dollar value, project type, city), so that I can understand the context of a deal at a quick glance without opening it.

Epic 2: Calendar View

Yearly Snapshot: As a business owner, I want to see a visualized snapshot of the calendar for the entire year in one place, so that I do not have to toggle between months to see upcoming projects.

Won Project Filtering: As a business owner, I want the calendar to automatically only show projects from the "Won" stage, so that my schedule isn't cluttered with unconfirmed deals.

Visual Clarity: As a business owner, I want each project on the calendar to be visually distinct from the others, so that I am never confused about where one project ends and another begins.

5. Functional Requirements
   
5.1 Pipeline Dashboard
The system must display a real-time count of total Active Deals (deals in active stages like Quoted or Review).

The system must calculate and display the total Pipeline Value (sum of all active deals).

The system must calculate and display the Total Won revenue.

The system must calculate and display the Average Deal size based on the active pipeline.

The system must calculate and display the Closed Lost Amount (the total dollar value of all deals moved to the "Lost" column).

The system must calculate and display the Profit of Closed Won (the actual calculated profit of all deals in the "Won" column).

The system must calculate and display the Projected Profit of Pipeline (the estimated future profit of all active deals currently in the pipeline).

5.2 Kanban Pipeline Board

Stages: The board must have predefined columns representing the sales cycle (e.g., Leads, Quoted, Review, Won, Lost).

Deal Creation: Users must be able to add a new deal via a simple form requiring core information: Client Name, Amount, City, and Type.

Optional Scheduling Fields: The deal creation form must also allow users to input a Start Date and Projected Days to Complete right from the beginning, so scheduling data can be captured early.

Drag-and-Drop: Users must be able to drag a deal card from one column and drop it into another to change its stage.

Card Display: Each deal card must visually render the Client Name, Amount, City, and Type directly on the face of the card.

5.3 Calendar / Schedule View

Single-Page Layout: The calendar must render all 12 months of the year on a single, scrollable view.

Gantt Chart UI: Projects must be represented as horizontal bars spanning across the days they are active.

Visual Distinction: Deals on the Gantt chart must be visually distinct from one another (e.g., utilizing alternating colors, clear borders, or vertical spacing) to ensure there is absolutely no user confusion regarding where one project ends and another begins.

Data Source: The calendar must only populate using deals that reside in the "Won" column.

Scheduling Logic: To appear on the calendar, a "Won" deal must have a defined "Start Date" and "Days to Complete" (duration).
