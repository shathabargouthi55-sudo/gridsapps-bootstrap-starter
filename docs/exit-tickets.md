# Exit Tickets

## Day 06 — Bootstrap Setup, Grid & Utilities

**1. What did I build today?**

A responsive Bootstrap page with a hero section, a services card grid, a pricing section (B01), and a dashboard summary with KPI cards and a table (B03). I also added a custom stylesheet with hover effects for the cards.

**2. What bug/difficulty did I solve?**

The "Learn More" button did not scroll to the services section because the `id="services"` was on an empty div inside the hero. I moved the `id` to the real services section and the button worked. I also made the table scroll inside its own container on small screens so the page has no horizontal scroll.

**3. What concept can I explain clearly?**

The Bootstrap grid: `container`, `row`, and `col-*` classes divide the page into 12 columns, and breakpoints like `col-md-6` and `col-lg-4` change the number of columns by screen size. I also used utility classes for spacing (`py-4`, `mb-4`), flex (`d-flex`, `justify-content-center`, `gap-2`), and text (`text-center`, `fw-bold`).

**4. What remains incomplete?**

The dashboard numbers and table are sample data written directly in the HTML. In a real project they would come from a database.