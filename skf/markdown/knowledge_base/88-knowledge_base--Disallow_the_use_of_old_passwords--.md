## Description:

This is a mitigation of the risk that a password can leak by any means towards a possible attacker.Changing the password to a new one minimizes the damage.

## Solution:

Keep the old entries of the password record of the user. If the user changes his password
you can match against the old entries to validate it is not an old one.
