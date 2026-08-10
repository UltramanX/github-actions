# github-actions
Repo for Github Actions

The core hierarchy of GitHub Actions perfectly:

Workflow: The top-level automated process defined in your .github/workflows/*.yml file, triggered by an event.

Job: A set of steps that run sequentially on the same runner environment. By default, jobs run in parallel unless you define dependencies between them (needs:).

Step: An individual task within a job—either a shell script (run:) or a pre-packaged action (uses:).

Runner: The underlying server (hosted by GitHub or self-hosted) that executes the job environment and runs the steps.
