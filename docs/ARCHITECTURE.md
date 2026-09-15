# Architecture

```text
Student UI + Recruiter UI
          ↓
       REST API
          ↓
   Recommendation Engine
          ↓
     JSON Persistence
```

1. A student creates or updates a structured profile.
2. The API persists normalized fields.
3. The matcher scores every active opportunity.
4. Scores are sorted and returned with component breakdowns and reasons.
5. The UI renders a ranked recommendation dashboard.

Production evolution: JSON → Postgres, add authentication/authorization, organization verification, rate limiting, privacy controls, audit logs, richer skill ontology, embeddings and resume parsing.