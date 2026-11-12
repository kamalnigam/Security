# Security

Principal Architect–level interview preparation for OAuth 2.0, OpenID Connect,
PKCE, and JSON Web Tokens. The material is designed to be spoken in an
interview, then defended through architecture trade-offs and follow-up
questions.

## Start here

| Question | Topic | Key outcome |
| --- | --- | --- |
| [Q1](interview-prep/q1-oauth2.md) | OAuth 2.0 | Explain delegated authorization and a scalable enterprise design. |
| [Q2](interview-prep/q2-grant-types.md) | Grant selection | Select the correct flow for user, service, and device clients. |
| [Q3](interview-prep/q3-pkce.md) | PKCE | Explain why an intercepted authorization code cannot be redeemed. |
| [Q4](interview-prep/q4-oidc.md) | OpenID Connect | Clearly separate authentication from authorization. |
| [Q5](interview-prep/q5-jwt-validation.md) | JWT validation | Validate tokens safely, rotate keys, and handle revocation trade-offs. |

The diagrams are local SVG assets under [`interview-prep/assets`](interview-prep/assets/), so they render on GitHub and do not depend on external image hosts.

## Suggested practice loop

1. Give the "interview-ready answer" aloud without reading.
2. Draw or describe the included diagram.
3. Discuss the listed trade-offs and the scenario.
4. Answer the follow-ups as if you were accountable for the production design.

## Standards referenced

- [OAuth 2.0 — RFC 6749](https://www.rfc-editor.org/rfc/rfc6749)
- [OAuth 2.0 Security Best Current Practice — RFC 9700](https://www.rfc-editor.org/rfc/rfc9700)
- [PKCE — RFC 7636](https://www.rfc-editor.org/rfc/rfc7636)
- [OpenID Connect Core 1.0](https://openid.net/specs/openid-connect-core-1_0.html)
- [JWT — RFC 7519](https://www.rfc-editor.org/rfc/rfc7519)
- [JWT Best Current Practices — RFC 8725](https://www.rfc-editor.org/rfc/rfc8725)
