# BruteForce-Success (LINUX)

Work the incidents being generated within Azure Sentinel, in accordance with the
NIST 800-61 Incident Management Lifecycle. Make use of the provided Pl

Step 1: Preparation
(We initiated this already by ingesting all of the logs into Log Analytics Workspace and Sentinel and configuring alert rules)

Step 2: Detection & Analysis (You may have different alerts/incidents)
Set Severity, Status, Owner
View Full Details (New Experience)
Observe the Activity Log (for history of incident)
Observe Entities and Incident Timelines (are they doing anything else?)
“Investigate” the incident and continue trying to determine the scope
Inspect the entities and see if there are any related events
Determine legitimacy of the incident (True Positive, False Positive, etc.)
If True Positive, continue, if False positive, close it out

Step 3: Containment, Eradication, and Recovery
Use the simple Incident Response PlayBook

Step 4: Document Findings/Info and Clouse out the Incident in Sentinel
