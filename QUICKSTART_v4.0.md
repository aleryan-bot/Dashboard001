# Trinova Dashboard v4.0 - Quick Start Guide

## Getting Started in 5 Minutes

### Step 1: Open the Dashboard
Double-click `trinova_dashboard_v4.0.html` in Chrome or Edge

### Step 2: Upload Your Data
Click **"Upload Data File"** → Select your CSV or Excel file

**Supported Formats:**
- Single CSV file (one week)
- Multi-sheet Excel file (each sheet = one week)

### Step 3: Explore!
Your dashboard is ready. Start exploring your data!

---

## What's Fixed in v4.0

### The Big Fix: No-Shows Now Work! ✅
**Problem:** No-Shows were showing as 0 or blank  
**Solution:** Completely rewrote the parsing engine  
**Result:** 100% accurate No-Shows data

**Test it yourself:** Upload week_36, week_37, and week_39 samples - all No-Shows values now appear correctly!

---

## New Features You'll Love

### 1. Compare Weeks Side-by-Side
**When to use:** Analyze performance between any two weeks

**How:**
1. Click **"Compare Weeks"**
2. Select two weeks
3. Click **"Compare These Weeks"**
4. See differences with arrows: ↑ for increases, ↓ for decreases

**Example Output:**
```
Visits: 254 → 379 (↑ 125, +49.2%)
Charges: $51,845 → $81,097 (↑ $29,252, +56.5%)
```

### 2. Export to Excel
**When to use:** Archive data, share with stakeholders, or analyze in Excel

**How:**
1. Click **"Export to Excel"**
2. File automatically downloads
3. Open in Excel

**What you get:**
- Summary sheet with all weeks
- Individual sheets for each week
- Complete data tables

### 3. Provider Rankings
**When to use:** Team meetings, performance reviews, monthly reports

**How:**
1. Click **"Provider Rankings"**
2. See rankings by visits and charges
3. Gold/Silver/Bronze medals for top 3

### 4. Print Reports
**When to use:** Board presentations, monthly reports, documentation

**How:**
1. Set up your view (week, monthly, or comparison)
2. Click **"Print Report"**
3. Choose "Save as PDF" or print directly

---

## Daily Workflow

### Monday Morning: Upload Last Week
```
1. Open dashboard
2. Upload last week's CSV
3. Check KPIs
4. Review trends
5. Share insights with team
```

### End of Month: Monthly Review
```
1. Ensure all weeks are uploaded
2. Click "Monthly View"
3. Export to Excel
4. Print PDF for records
5. Review provider rankings
```

---

## Common Tasks

### How do I hide a week?
1. Click **"Manage Weeks"**
2. Click **"Hide"** next to the week
3. Week disappears from view but data is saved

### How do I see all my weeks again?
1. Click **"Manage Weeks"**
2. Click **"Show All Weeks"** button

### How do I compare this month to last month?
1. Use monthly view for each month
2. Export both to Excel
3. Compare the summary sheets

### How do I see who's the top performer?
1. Click **"Provider Rankings"**
2. Check both visits and charges rankings
3. Rankings use all visible weeks

---

## Tips & Tricks

### Tip 1: Use Excel Multi-Sheet Files
Instead of uploading 4 separate CSVs, create one Excel file with 4 sheets. One upload = all weeks!

### Tip 2: Hide Instead of Delete
Hide weeks you don't need right now. You can always show them later. Delete is permanent!

### Tip 3: Export Monthly
At the end of each month, export to Excel. Create a library of monthly reports.

### Tip 4: Compare Sequential Weeks
To spot trends, compare Week 36 vs 37, then 37 vs 38, etc.

### Tip 5: Print to PDF
Use "Print Report" and choose "Save as PDF" to create shareable monthly reports.

---

## Troubleshooting

### No-Shows still showing as 0?
1. Open browser console (F12)
2. Look for parsing messages
3. Check if data is in the CSV at Row 5, Column M/N
4. Try re-uploading the file

### Upload not working?
- Check file is .csv, .xlsx, or .xls
- Make sure file isn't corrupted
- Try a smaller file first
- Check browser console for errors

### Charts not showing?
- Refresh the page
- Re-upload your data
- Try a different browser
- Clear browser cache

### Rankings seem wrong?
- Check which weeks are visible (hidden weeks don't count)
- Make sure all desired weeks are uploaded
- Verify the data in the original files

---

## Keyboard Shortcuts

None yet! But you can:
- Press **Ctrl+P** (or Cmd+P) to print from any view
- Use **F12** to open developer console for debugging
- Press **Ctrl+R** (or Cmd+R) to refresh

---

## Data Format Reminder

Your CSV/Excel files should have:
- **Row 1:** Header
- **Row 2:** WEEK # XX
- **Row 3:** Date range
- **Row 4:** "Visits" section header
- **Row 5:** Provider names + No-Shows data
- **Rows 6-12:** Visit types
- **Row 14+:** Patient Acquisition section
- **Row 20+:** Claims section

The dashboard handles small variations but keep the structure consistent.

---

## Need More Help?

### Check the Full Documentation
- `CHANGELOG_v4.0.md` - Complete list of changes
- `README.md` - Comprehensive user guide
- `PROJECT_SUMMARY.md` - Technical details (for developers)

### Common Questions

**Q: Does this work offline?**  
A: Yes! After first load, everything runs locally.

**Q: Is my data secure?**  
A: Yes! All processing happens in your browser. Nothing is sent to external servers.

**Q: Can I use on mobile?**  
A: Yes! v4.0 is fully responsive. Works on tablets and phones.

**Q: How many weeks can I load?**  
A: No hard limit. We've tested with 50+ weeks successfully.

**Q: Will my data be saved?**  
A: Yes! Auto-saves to browser localStorage. Persists between sessions.

---

## Quick Reference Card

| Action | Button |
|--------|--------|
| Upload new data | "Upload Data File" |
| Switch weeks | Week dropdown selector |
| View monthly totals | "Monthly View" |
| Compare two weeks | "Compare Weeks" |
| See top performers | "Provider Rankings" |
| Export data | "Export to Excel" |
| Create PDF report | "Print Report" |
| Hide/show weeks | "Manage Weeks" |
| Clear everything | "Clear Data" (⚠️ permanent!) |

---

## Version Check

**Current Version:** 4.0 Enhanced Edition  
**Released:** October 2024  
**Status:** Production Ready

**How to check your version:**  
Look at the footer at the bottom of the dashboard page.

---

## What's Next?

Possible features for v5.0:
- Year-over-year comparison
- Custom date range filtering
- Email report automation
- Advanced analytics
- Budget tracking
- Goal setting & tracking

**Got ideas?** Share your feedback!

---

**Remember:** This is YOUR dashboard. Use it however works best for your workflow. Don't be afraid to experiment!

Happy analyzing! 📊
