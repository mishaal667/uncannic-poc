# uncannic — live proof of capability

This repository is the target of a live demonstration of **uncannic**, the governed action layer for web
applications without an API.

What happens here, on the real github.com:

1. A person, signed in to GitHub in their own browser, comments on the demo ticket (issue #1) as they normally would.
2. uncannic learns that action from the demonstration: the structure of GitHub's own request, never a value or a password.
3. After an approval, uncannic posts a status comment **through GitHub's own page code, inside that person's
   session** — no API token, no stored password, no screen automation.
4. uncannic reads the issue back to confirm the comment is on the record, and every step is written to its
   tamper-evident audit log.

Every comment that uncannic posts says so in its text. The ticket is a demonstration ticket, not a real customer record.

Contact: Meshal Al Masud · meshal.almasud@gmail.com
