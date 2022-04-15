# Feature Dogfooding Guidelines
*These guidelines should be used when setting up a session for the team to dogfood a new major feature.*

### Steps
*Either product managers or engineers can own the dogfooding process for a given feature. Please work that out within your team based on capacity.*
1. Copy the template below and fill in with specific instructions for your feature.
4. Schedule a dogfooding session (typically 1 hour meeting at least 1 sprint before launch).
6. **Before the dogfooding session**: check to make sure everyone participating has the proper permissions and access so that the session runs smoothly! Select the most appropriate environment(local, dev, and/or test) for your feature.
7. Facilitate the dogfooding session by going over the testing plan document with the team and giving them time to walk through the instructions manually on their machine. Explain how to report bugs and the specific labels. Ask for 1-2 volunteers to handle accessibility testing.
8. Product manager and engineer should meet after the session to triage and prioritize any issues that were reported from the session, deciding what is launch-blocking and including them in the sprint.
9. Once all launch-blocking issues are resolved, ship it! :rocket:

# TEMPLATE {Feature-Name} Testing Guidelines

## Setup
Instructions for how to set up for testing. This could mean setting up test accounts, setting certain permissions, etc.

```
EXAMPLE

- Check that you have access via the feature toggle {#feature toggle name here}
- Ensure you have access to UAT via these instructions.
```

## Report a Bug
Instructions for how to report bugs.

```
EXAMPLE

When you notice a defect or bug, create a Github issue with the bug report template and include the labels.
```

## Test Plan
Different scenarios/cases that need to be tested and instructions for the "happy path" (expected behavior). Make sure that accessibility testing instructions are also included at this point (keyboard and VoiceOver testing).

```
EXAMPLE

Schedule a virtual hearing
1. Login as X
2. Go to this feature
3. Click on “Schedule” and see that a virtual hearing is added to the schedule
4. Check that the virtual hearing is deleted the day after the hearing is held

Cancel a virtual hearing
1. Login as X
2. View currently scheduled hearings
3. Select a virtual hearing and click “Cancel”
...
