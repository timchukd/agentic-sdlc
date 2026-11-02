# Glossary: Customer Portal

Ubiquitous language for the Customer Portal. Terms are business concepts only.

**User**
A person who can authenticate to the portal. Owns credentials (email, password) and a role. Exists independently of any business activity.

**Profile**
The personal data of a User (name, phone, locale, time zone). Exactly one Profile per User.

**Customer**
A role a User takes on when they place orders or open support requests. Reserved for the ordering and support contexts. The identity context does not use this term.

**Role**
A User's permission category. In v1 every User has the role `customer`. Staff roles are added later.

**Session**
A login period for a User, identified by a refresh token. Ending a Session revokes its refresh token.

**Email verification**
Proof that a User controls the email address they registered with. A User cannot log in until their email is verified.
