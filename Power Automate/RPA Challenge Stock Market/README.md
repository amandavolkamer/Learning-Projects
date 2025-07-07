# 🧩 RPA Challenge - Stock Market: https://rpachallenge.com/
- **Tools Used:** Power Automate Desktop and Google Chrome
- **Challenge:** Extract each Stock's name, premarket value, and datetime stamp and store it within a data table.  
- **Solution:** Used an **UI element** for the dropdown and setup a **loop condition** for the dropdown to select the next option for each iteration.
I also used the **Extract data from Web Page** action as a single value and then did **text manipulation** to split and crop the text (like the Premarket Value and
 Datetime stamp) into their own text variables so that then can be stored in a tabular format in the data table.  This utilized logic in indices within a column.

---

This is a challenge I have completed before in my previous role as part of the Citizen Developer Program.  I wanted to tackle this challenge again as a side project to showcase my skills.
Part of this challenge is that the premarket value will update every 3 seconds or so, which means that as a developer, I have to ensure to 
pull the data accurately with the datetime stamp before it changes.

Some of the challenges this time around were limited access to some parts of the Microsoft suite since I was using just my personal account.
So instead of directly storing the data into Excel, I stored it in a data table.  This can easily be remedied to write the data table to excel or store the data direactly to Excel.
