# Major Incident Checklist

This checklist can be used during a high-impact production incident to ensure quick triage, clear ownership, structured communication, and proper follow-up.

## 1. Incident Identification

- Confirm the incident source:
  - Monitoring alert
  - User report
  - Service desk ticket
  - Business escalation
  - Vendor notification

- Capture initial details:
  - Date and time detected
  - Reported by
  - Affected application or service
  - Business function impacted
  - Number or type of users impacted
  - Severity level
  - Initial symptoms

## 2. Initial Impact Assessment

Ask:

- Is the service fully down or partially degraded?
- Is this impacting external customers, internal users, or business operations?
- Is there a workaround available?
- Is the issue affecting one region or multiple regions?
- Is the issue time-sensitive, business-critical, or compliance-sensitive?

## 3. Incident Bridge / War Room

- Start an incident bridge or collaboration channel.
- Invite required teams:
  - Application support
  - Infrastructure / cloud / network team
  - Database team
  - Vendor team
  - Business owner
  - Service delivery manager
  - Incident manager
- Assign clear roles:
  - Incident lead
  - Technical investigation owner
  - Business communication owner
  - Timeline / notes owner

## 4. Triage and Investigation

- Review recent changes, deployments, releases, or configuration updates.
- Check monitoring dashboards and logs.
- Validate whether issue is reproducible.
- Compare affected vs unaffected users, regions, or transactions.
- Identify possible root cause area:
  - Application
  - Database
  - Integration/API
  - Network
  - Access/permission
  - External vendor/system
  - Batch/job failure

## 5. Communication

Send regular updates to stakeholders using a consistent format:

- Current status
- Business impact
- Actions in progress
- Teams engaged
- Workaround, if any
- Next update time

Recommended update frequency:
- P1 / Critical: Every 30 minutes or as agreed
- P2 / High: Every 60 minutes or as agreed

## 6. Resolution and Recovery

- Confirm technical fix or workaround.
- Validate with technical team.
- Validate with business users.
- Monitor service after recovery.
- Confirm no additional downstream impact.
- Communicate resolution to stakeholders.

## 7. Post-Incident Actions

- Create RCA / post-incident review.
- Document timeline of events.
- Identify root cause and contributing factors.
- Capture what went well and what can improve.
- Define preventive actions.
- Assign owners and due dates.
- Update runbooks, monitoring, SOPs, or training material if needed.
