# Azure virtual machines and scale sets

**Context:** MST400 academic lab.

## Objective
Explore Azure virtual machine deployment, virtual machine scale sets and scaling rules.

## Work documented
- The submission describes deploying virtual machines and configuring a virtual machine scale set.
- During the scaling exercise, CPU usage stayed too low for the original test condition to trigger.
- The report states that the test rule was adjusted to trigger another virtual machine when CPU usage was below 1%, allowing the scaling scenario to be observed.

## Takeaway
An autoscaling rule can appear inactive when its metric never reaches the test condition. For a controlled demonstration, changing a test condition can help exercise the configuration. The below-1% rule was a lab workaround, not a recommendation for production scaling.

## Evidence and limitations
The source describes the work and includes screenshots. The screenshots are not included here and have not been independently checked in this record.
