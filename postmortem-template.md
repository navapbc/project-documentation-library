# YYYY-MM-DD Postmortem title
Date:
Authors:
Status:
---

## Summary
*example:*
```
- Product - all products
Issue category -
- Mission Impact – Low: Brief intermittent outage for products
```
## Impact
*example:*
```
- Users were seeing 5xx errors for a few hours while the RDS DB was at 100% CPU utilization and could not handle more queries
```

## Root Causes

## Detection
*How was the incident detected?*

## Timeline
*example:*
```
2020-3-25 1:20pm
[Started] RDS CPU Utilization hits 100% and is unable to recover
RDS CPU Utilization

...
```
## Resolution
*example:*
```
Added new indices to speed up particularly slow DB queries, lowering average DB utilization
```

### Prevention

### Action Items
*What are some action items that came out of this incident?*

### Lessons Learned
- **What Went Well**
- **What Went Poorly**
- **Where We Got Lucky**

### Supporting Information
*relevant links and/or similar previous incidents*
