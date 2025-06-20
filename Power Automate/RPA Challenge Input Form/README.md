# 🧩 RPA Challenge - Input Form: https://rpachallenge.com/
- **Tools Used:** Power Automate Desktop, Google Chrome, Excel
- **Challenge:** Complete 10 rounds of dynamic form submissions from an Excel file where form field order changes after each submission.
- **Solution:** Used **UI Selectors** and targeted unique **IDs** within elements to match fields regardless of their visual order.

---

This is a challenge I have completed before in my previous role as part of the Citizen Developer Program.  I wanted to tackle this challenge again as a side project to showcase my skills.
Some of the challenges this time around were limited access to some parts of the Microsoft suite since I was using just my personal account.
So instead of directly using Excel which the challenge data is downloaded as, I put that data into a datatable within the workflow to complete this challenge.

Another challenge I encountered was there is a difference between how to call on a data point from a variable when Power Fx is enabled in the workflow.
You'll see there is a comment within the workflow calling that out so that I can reference that later if needed for other builds.

When Power Fx is **NOT** enabled in the workflow, the correct formatting to call on a data point within a variable is %Variable['Column Name']%

But when Power FX is enabled within the workflow, the formatting needs to be =Variable.'Column Name'
