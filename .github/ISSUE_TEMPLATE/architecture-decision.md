---
name: Architecture Decision
about: Technical architecture, platform choices, technology decisions that set precedent
title: '[ARCH] '
labels: 'decision:architecture, impact:medium'
assignees: ''
---

## Decision Summary
<!-- One sentence: What technical decision needs to be made? -->

## Problem Statement
<!-- What problem are we solving? Why do we need to make this decision? -->

## Proposed Solution
<!-- What do you recommend? Be specific about technology, approach, implementation. -->

## Alternatives Considered
<!-- What other options did you evaluate? Why did you reject them? -->

### Option 1: [Name]
- **Pros:**
- **Cons:**
- **Why rejected:**

### Option 2: [Name]
- **Pros:**
- **Cons:**
- **Why rejected:**

## Tech Stack Alignment
<!-- Does this align with pre-approved tech stack (Charter Section: Architectural Standards)? -->
- [ ] Uses pre-approved technology (no escalation needed)
- [ ] Deviates from standards (requires Jeff approval)
- [ ] New technology not in standards (requires Jeff approval with rationale)

**If deviating:** Why can't we use standard stack?

## Impact Assessment

### Technical Impact
- Affects: [ ] Database [ ] Backend [ ] Frontend [ ] Infrastructure [ ] Security
- Cross-domain: [ ] Yes [ ] No
- Sets precedent: [ ] Yes [ ] No

### Team Impact
- Requires training: [ ] Yes [ ] No
- Changes operational processes: [ ] Yes [ ] No
- Estimated effort: [hours/days]

### Customer Impact
- Customer-facing: [ ] Yes [ ] No
- Performance impact: [ ] Positive [ ] Negative [ ] Neutral
- Uptime risk: [ ] High [ ] Medium [ ] Low [ ] None

## Security & Compliance
<!-- Has Mat (Security Lead) reviewed this? -->
- [ ] Security review not needed
- [ ] Security review needed - @mat
- [ ] SOC2 compliant
- [ ] SOC2 considerations documented

## Domain Lead Reviews

### Infrastructure Review (Brad)
- [ ] Approved - no concerns
- [ ] Concern raised (see comments)
- [ ] Blocker identified (see comments)
- [ ] Review not needed

### Product Review (Nick)
- [ ] Approved - no concerns
- [ ] Concern raised (see comments)
- [ ] Blocker identified (see comments)
- [ ] Review not needed

### Security Review (Mat)
- [ ] Approved - no concerns
- [ ] Concern raised (see comments)
- [ ] Blocker identified (see comments)
- [ ] Review not needed

## Budget
- Estimated cost: $
- Recurring cost: $ per [month/year]
- Requires CFO approval: [ ] Yes [ ] No

## Timeline
- Decision needed by: [DATE]
- Implementation timeline: [timeframe]
- Customer commitment: [ ] Yes [ ] No

## Decision Owner
<!-- Usually Jeff for architecture decisions -->
@jeff

## Related Issues/PRs
<!-- Link to related decisions, implementation PRs, etc. -->

---

**Decision Process:**
1. Domain leads review and comment (48 hours)
2. Jeff makes final decision after reviewing input
3. Decision documented in closing comment
4. Summary posted to #tech-team
5. Update charter if this changes standards
