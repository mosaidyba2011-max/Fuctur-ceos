# Future CEOs — starter app

A responsive React/Vite starter for a small-business storefront and management dashboard.

## Run it
1. Install Node.js (18+).
2. Extract this folder.
3. In this folder run `npm install`.
4. Run `npm run dev`.
5. Open the local address Vite prints.

To create a production web build, run `npm run build`; the output is in `dist/`.

## Included
- Business profile creation screen and demo sign-out
- Dashboard statistics and recent orders
- Product create, edit, delete, search, price and stock management
- Customer-facing store view
- Customer order creation and seller order-status updates
- Phone dialler link (`tel:`) and WhatsApp chat link (`wa.me`)
- Responsive layout for Android-sized screens
- Local browser persistence using localStorage

## Important production limitations
This is a working front-end starter, not a production-ready multi-user commerce service. Data is stored only in the current browser on the current device. The sign-up password is not sent to a server or securely authenticated. There is no cloud database, real image upload, payment processing, email/SMS notification, or separate public store URL yet. Do not use real customer data or rely on this for live trading until a backend is added.

For a public launch, connect a backend such as Supabase or Firebase for secure authentication, database rules, image storage, per-business data isolation, and order APIs. Add server-side validation, backups, privacy/terms pages, and payment-provider integration where supported. The image field currently accepts an image URL rather than uploading a file.

## Notes
- Enter WhatsApp numbers in international format, digits with country code (for example `220...`); the link strips punctuation.
- Prices are displayed in Gambian dalasi (GMD).
- Orders created in the demo are sample workflow records; they do not send a notification to the seller.
