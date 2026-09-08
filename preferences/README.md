# Private purchase preferences

Store product preferences outside Git at
`~/.config/amazon-plugin/preferences/`, or set `AMAZON_PREFERENCES_DIR` to an
explicit private local directory. Read only Markdown relevant to the current
request. If no preferences are configured, ground the choice in the user's
request and verified product information.

Preferences can record product constraints and known successful variants. They
do not authorize cart changes or purchase. When an exact item is unavailable,
present alternatives instead of silently substituting. Never commit order
history, delivery addresses, payment information, or health-related preferences.
