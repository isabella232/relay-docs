# Using workflows

Relay uses YAML workflows to define the steps in an automation task.

Each step in a workflow runs in a separate container. The Relay service executes the steps
simultaneously unless you explicitly define a sequential order for the steps to run in. The workflow syntax is documented [in the Reference section](reference/relay-workflows.md). This section provides practical examples and implementation details for going deeper with workflows.

-   [Running a workflow](using-workflows/running-a-workflow.md)
-   [Adding connections](using-workflows/managing-connections.md)
-   [Adding secrets](using-workflows/managing-secrets.md)
-   [Using triggers](using-workflows/using-triggers.md)
-   [Passing data into workflow steps](using-workflows/passing-data-into-workflow-steps.md)
-   [Conditional step execution](using-workflows/conditionals.md)
-   [Using Approvals in workflows](using-workflows/adding-an-approval-step.md)