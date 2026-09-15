# Likely Judge Questions

### Why is this AI?
The prototype uses an explainable recommendation engine. It combines weighted skill similarity, a related-skill map, interest overlap, experience fit, work-mode fit and text similarity. The matching layer can later be replaced or augmented with embeddings or a learned model.

### Why not a normal job portal?
A portal makes the student search repeatedly. SkillBridge turns the student's profile into a ranked shortlist and exposes the reasons behind each ranking.

### How is the score calculated?
50% exact skills, 15% related skills, 15% interests, 10% experience, 5% work mode, and 5% text similarity.

### How do you avoid misleading scores?
The score is a decision aid, not a hiring guarantee. The component breakdown and reasons make its basis inspectable.

### How could this scale?
Replace JSON with Postgres, add authentication and organization verification, and introduce embeddings/vector search without changing the core product workflow.

### How does it make money?
Students remain free. Future revenue can come from recruiter subscriptions, campus partnerships, placement analytics, and optional employer branding. These are proposed monetization paths, not current revenue claims.

### What is the SDG 8 connection?
The product reduces friction between demonstrated student capabilities and entry-level internship requirements, supporting access to decent work opportunities.