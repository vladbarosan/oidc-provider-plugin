# Optional claim template UI evidence

Screenshots for https://github.com/vladbarosan/oidc-provider-plugin/pull/1.

- `claim-template-before.jpg`: upstream master `ff6ac31471ff0a250ffd7b0dfe3c64fd55abdda9`, Jenkins 2.568.1.
- `claim-template-after.jpg`: optional-claim implementation `c4a027d87fe43d2a4e3ebcb7957dbde5624753b4`, Jenkins 2.568.1, after saving and reopening the configuration.

Both screenshots come from isolated local Jenkins development instances using the same `change_id = ${CHANGE_ID}` string claim. The updated form was exercised by clearing and selecting Optional, saving each state, and reopening the page to confirm persistence.
