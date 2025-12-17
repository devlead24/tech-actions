---
name: Budget Decision
about: Major spending (>$2K), vendor contracts, tool purchases, hiring
title: '[BUDGET] '
labels: 'decision:budget, impact:medium'
assignees: ''
---

## Purchase Summary
<!-- One sentence: What do we want to buy/spend on? -->

## Budget Request
- **One-time cost:** $
- **Recurring cost:** $ per [month/year]
- **Total first year:** $
- **Contract term:** [length]
- **Cancellation terms:** [notice period, fees]

## Business Justification
<!-- Why do we need this? What problem does it solve? -->

### Current Pain Point
<!-- What's broken or missing without this? -->

### Expected Benefit
- **Efficiency gain:** [quantify if possible]
- **Risk mitigation:** 
- **Revenue impact:** 
- **Customer impact:** 

### ROI Calculation (if applicable)
- **Cost:** $
- **Savings/Value:** $
- **Payback period:** [months]

## Alternatives Considered
<!-- What other options did you evaluate? Include "do nothing" option. -->

### Option 1: [Name]
- **Cost:** $
- **Pros:**
- **Cons:**
- **Why rejected:**

### Option 2: Do Nothing
- **Cost:** $0
- **Impact of not purchasing:**
- **Why not acceptable:**

## Category
- [ ] Software/SaaS tool
- [ ] Infrastructure/hosting
- [ ] Hardware
- [ ] Contractor/consulting
- [ ] Hiring (new employee)
- [ ] Training/education
- [ ] Other: ___________

## Domain Owner
<!-- Who in the team needs/requested this? -->
- **Requested by:** @
- **Will use:** 
- **Domain:** [ ] Product [ ] Infrastructure [ ] Security [ ] Data [ ] Tools

## Technical Evaluation

### Integration Requirements
- [ ] No integration needed
- [ ] Simple integration (API, webhook)
- [ ] Complex integration (custom development)
- [ ] Infrastructure changes required

**Integration effort:** [hours/days]

### Security Review (Mat)
- [ ] Security review not needed
- [ ] Security approved
- [ ] Security concerns (see comments)
- [ ] SOC2 compliant vendor: [ ] Yes [ ] No [ ] N/A

### Operational Impact
- [ ] No operational changes
- [ ] Requires team training
- [ ] Changes existing processes
- [ ] Requires ongoing maintenance

## Budget Authority
<!-- Per charter, thresholds TBD with CFO -->
- [ ] <$100 - Domain lead approved
- [ ] $100-$2K - CTO (Jeff) approved
- [ ] >$2K - CTO + CFO approval needed
- [ ] Hiring - CTO + COO approval needed

## Timeline
- Decision needed by: [DATE]
- Why this timeline: 
- Start date: [when would we start using/paying]

## Decision Owners
- **Requestor:** @
- **CTO (Jeff):** Approves technical fit
- **CFO:** Approves budget (>$2K)
- **COO (Tom):** Approves strategic/hiring

## Contract Details (if vendor)
- **Vendor:** 
- **Contract length:** 
- **Auto-renewal:** [ ] Yes [ ] No
- **Cancellation terms:** 
- **Payment terms:** 
- **Escalation clauses:** 

## Related Decisions
<!-- Link to related architecture/product decisions -->

---

**Decision Process:**
1. Requestor fills out justification and alternatives
2. Domain lead reviews and confirms need
3. Mat reviews security (if applicable)
4. Jeff approves technical fit and priority
5. CFO approves budget (if >$2K)
6. Tom approves if strategic/hiring
7. Decision documented in closing comment
8. Tracked for Tom's weekly budget export
