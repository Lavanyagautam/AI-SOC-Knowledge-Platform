# Password Reset Investigation

## Objective

Validate whether a password reset was authorized and determine if it indicates account compromise.

## Investigation Steps

1. Review Entra ID audit logs.
2. Identify who initiated the password reset.
3. Verify whether the reset was expected.
4. Review recent sign-in activity.
5. Check MFA status and registration changes.
6. Look for suspicious authentication attempts.
7. Validate activity with the user if required.

## Potential Indicators of Compromise

- Unexpected password reset.
- Password reset followed by suspicious logins.
- MFA changes immediately after reset.
- Multiple failed sign-in attempts.

## Containment

- Revoke active sessions.
- Force password reset.
- Require MFA re-registration.
- Temporarily disable account if compromise is suspected.

## Remediation

- Review account activity.
- Investigate additional impacted accounts.
- Implement additional monitoring.

## Closure Criteria

- Password reset validated.
- No suspicious activity detected.
- Account secured and monitored.
