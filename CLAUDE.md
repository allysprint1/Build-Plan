# Build-Plan — conventions

## UK_Restock_Plan.xlsx

- **Always include UK shipping (transit) days, not just weeks**, on the "UK Restock Plan" tab.
  Sea Transit to UK and Air Transit to UK must each show both a Weeks column (looked up from
  Reference Data) and a Days column (`=Weeks * 7`), so shipping windows can be planned at
  day-level precision. This was an explicit, standing request from the user — keep both columns
  on any future regeneration of this tab, even as other columns are added/reordered around them.
