# Systems Engineering Glossary: Zanzibar Consistent Authz Engine

### Zanzibar
Google's global authorization system using relation tuples (user, relation, object) to evaluate permissions.

### Relation Tuple
Fundamental unit of authorization state structured as `namespace:object#relation@user`.

### Zookie
Consistency token embedding a snapshot timestamp to guarantee permissions are evaluated without stale-cache anomalies.

### Expand API
Authorization endpoint unpacking transitive relationship trees to inspect group memberships.
