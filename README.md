# Amazon

Amazon purchase-preparation workflow for the current user.

The plugin may ground an ordinary product request and make the reversible cart
change the user explicitly authorized. It never converts an unattended capture
into checkout or an order. Ambiguous products become options; prepared carts
remain in the current task or native scheduled thread for the user's approval.

Private purchasing constraints and known successful products stay outside Git.
See [`preferences/README.md`](preferences/README.md) for optional local
configuration. They help identify what to buy but never count as permission
to change the cart or place an order.
