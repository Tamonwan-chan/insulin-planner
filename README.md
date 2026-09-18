# Insulin Supply Planner

Repo: https://github.com/Tamonwan-chan/insulin-planner

A simple calculator for figuring out how many insulin vials to dispense to a patient between today and their next appointment.

Enter the per-dose units for breakfast, lunch, dinner, and bedtime, plus today's date and the appointment date. The calculator accounts for two limits on each vial:

- **Volume**: one vial holds 1,000 units.
- **Shelf life**: an opened vial must be discarded 28 days after opening, even if units remain.

It reports the total number of vials needed, days covered, total units required, any units wasted to expiry, a visual timeline, and a day-by-day breakdown of when each vial is opened and why it's retired.

Open [insulin-planner.html](insulin-planner.html) in a browser to use it.
