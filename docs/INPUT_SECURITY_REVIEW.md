# Input Security Review

For each externally supplied value, review:

- validation of type, length, and allowed values,
- safe output encoding,
- authorization before data access,
- safe error responses,
- protection of secrets and personal data,
- boundary and malformed-input tests.

Record the actual controls present in the application and list gaps separately. A checklist is not a substitute for an implementation review.