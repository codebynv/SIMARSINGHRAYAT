# Dependency Review Checklist

Before adding or upgrading a dependency:

- Confirm the feature cannot reasonably use existing project code.
- Check maintenance status and supported versions.
- Review license and security advisories.
- Consider package size and transitive dependencies.
- Update lockfiles consistently.
- Run relevant checks after the change.

Record the reason for the dependency and any migration implications. Do not claim a security audit was completed unless one was performed.