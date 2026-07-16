# MFA Manipulation Investigation

## Objective

Determine whether MFA settings were modified maliciously.

## Investigation Steps

1. Review audit logs.
2. Identify modified MFA methods.
3. Review initiator details.
4. Validate changes with user.
5. Review associated sign-ins.

## Containment

- Remove unauthorized MFA methods.
- Require MFA re-registration.
- Revoke sessions.

## Closure Criteria

- MFA secured.
- User validated.
- No compromise identified.
