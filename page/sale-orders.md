Orders are created when a customer completes the checkout process, and they are visible to users with Admin and Shop Manager roles only. Each order is given a unique Order ID.

**Order statuses** let you know how far along the order is, starting with “**Pending payment**” and ending with “**Completed**.” The following order statuses are used:

- **Draft** — Order received, no payment initiated. Awaiting payment (unpaid).
- **Failed** — Payment failed or was declined (unpaid) or requires authentication (SCA). Note that this status may not show immediately and instead show as Pending until verified (e.g., PayPal).
- **Processing** — Payment received (paid) and the stock has been reduced; order is awaiting fulfilment.
- **Completed** — Order fulfilled and complete – requires no further action.
- **On hold** — Awaiting payment – stock is reduced, but you need to confirm payment.
- **Cancelled** — Canceled by an admin or the customer – stock is increased, no further action required.
 
Admin can create an Order on the **Dashboard &gt; SALES &gt; Orders &gt; Create Orders** or edit the existing Orders:

![](/assets/images/sale-orders/0c41d5bef48534cb3e3a28a80e964843.png)

Only the admin role can edit an Order and update its Booking status

![](/assets/images/sale-orders/77471119cd112214b22f6c15fe8268b5.png)