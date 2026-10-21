# Fab Order Progress

Supervisor app for ORO Design & Manufacturing. Track up to 8 trucks by Sales Order # and BM #, and tick off Welding and Cut & Fab stations to see each truck's completion %.

- Works in any browser on a computer, tablet or phone.
- Can be installed like an app (Add to Home Screen / Install app) and opens without internet.
- Each supervisor's trucks are saved only on their own device. Nothing is sent to GitHub or anywhere else.
- Use **Export backup** regularly, and **Import backup** to move trucks to another device.

## Changing stations or percentages
Open `index.html`, find `const DEPTS=[` near the top of the script, and edit the station names (`n`) and weights (`w`). Weights in each department should add up to 100.
