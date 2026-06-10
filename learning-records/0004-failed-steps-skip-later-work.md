# Failed Steps Skip Later Work

The learner asked whether later steps are skipped when a stage fails. Future lessons should assume the beginner rule is now explicit: a failed `sh` step normally fails the current stage, skips remaining normal steps/stages, and produces a failed build unless the Jenkinsfile deliberately handles the failure with mechanisms such as `post`, `returnStatus`, or error-handling steps.
