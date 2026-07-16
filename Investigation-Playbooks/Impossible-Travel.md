# Impossible Travel Investigation

## Objective

Determine whether a user account has been accessed from geographically distant locations within an impossible timeframe.

## Investigation Steps

1. Review Entra ID sign-in logs.
2. Verify geolocation information.
3. Check MFA status and authentication details.
4. Review user sign-in history.
5. Validate device compliance status.
6. Contact user if required.
7. Determine whether activity is legitimate.

## Containment

- Revoke active sessions.
- Reset user password.
- Force MFA re-registration.

## Closure Criteria

- User activity validated.
- No indicators of compromise identified.
- MFA successfully completed.
