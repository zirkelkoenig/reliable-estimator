# reliable-estimator
A time tracking and estimation tool for programmers, implementing the Evidence-Based Scheduling by Joel Spolsky as described [here](https://www.joelonsoftware.com/2007/10/26/evidence-based-scheduling/ "Evidence Based Scheduling").

## Problem Definition
The user creates a task, split into subtasks with estimated time requirements. The software then calculates a confidence distribution, showing the probability for possible completion dates of the overall task. To achieve this, the software takes into account the estimated vs. actual time requirements of past tasks. A time-tracking feature should also be integrated directly.
