# Pre-Register-Application-Power platform
# Employee Pre-Register Application (Power Apps)

This Power Apps canvas app lets an admin **pre-register employees** for on-site visits/inspections. The admin can search employees, see upcoming visits, and mark a visit as **checked-out** — checked-out visits are hidden from the list so the admin only sees what’s still pending.

## 🧩 What it does
- Admin selects an employee (from Dataverse / SharePoint list `workSiteVisits`)
- Admin assigns a **location** and a **date** for the visit
- Visits are shown in a list view, sorted by registration date (newest first)
- Admin can **search by name or visit number**
- Admin can **check** a visit → the app hides that record from the gallery using a collection (`COLHiddenVisits`)
- Admin can view more info with **“See Details”** button

## 🖥️ Screens
1. **Welcome / Front Page**
   - Intro text telling admin to start pre-registering
   - Button: “Click Here to Start”

2. **List View**
   - Search box: “Search By Name”
   - Gallery of visits (Name, Location, Visit Date)
   - Checkbox: **“checked-out”** → when checked, that visit is added to `COLHiddenVisits` and disappears from the list
   - “See Details” button for each row
   - Back button to go to the register form




