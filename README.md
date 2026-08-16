# Human review-cost evaluation

A measurement harness that tests how the *presentation* of AI-proposed document edits changes human review — decision time, inter-reviewer agreement and error rate against a pre-registered answer key — across four conditions: batch vs sequential presentation, crossed with section-diff vs whole-document-diff. Built on the SuperDocs API, with the corpus frozen from human-in-the-loop `pending_changes` so no edit is ever applied.

This is an N=1 pilot: it validates the harness and documents what the API does, but it does not rank the four conditions, and the report suppresses accuracy and Fleiss' κ rather than printing numbers a single rater cannot support.

**Full write-up, setup and results → [`use-cases/Ranjan2113/doctask-ranjan-jamnis-review-eval/README.md`](use-cases/Ranjan2113/doctask-ranjan-jamnis-review-eval/README.md)**

Submitted to SuperDocs as [superdocsapp/superdocs-builds#46](https://github.com/superdocsapp/superdocs-builds/pull/46). The folder path mirrors that pull request.
