# WET ticketing handoff

## Agreed architecture

- Shopify remains the WET website, content and future merchandise platform.
- SimpleTix is the event inventory, ticket delivery and QR check-in system.
- WET's existing Square account processes online and onsite ticket payments.
- Square Registers remain in normal use. A compatible tablet and Square reader can be dedicated to SimpleTix door sales and scanning.
- Current SPLASH sales remain on Eventbrite until that event is complete.
- Regular Jam-Packed Sundays, Towelless Tuesdays and Naked Fridays remain walk-in unless specifically advertised as ticketed.

## Fee policy

- Customer pays the advertised ticket price.
- Customer pays the SimpleTix booking fee.
- WET absorbs Square payment-processing fees.
- Do not enable SimpleTix payment-processing fee recovery.
- Show the full total before payment and keep all public fee wording consistent with Australian pricing requirements.

## Theme activation

The Events template contains a `WET SimpleTix tickets` section. It outputs no storefront markup while disabled or while the embed code is blank.

After the merchant account is ready:

1. Connect SimpleTix to WET's correct Square account and Square location.
2. Configure SimpleTix to pass only its booking fee to the customer.
3. Create branded ticket email, QR ticket, capacity and ticket-type settings.
4. Copy the SimpleTix event-list or calendar embed code.
5. In the Shopify theme editor, open the Events page and select `WET SimpleTix tickets`.
6. Paste the embed code and enable `Show SimpleTix ticketing`.
7. Test a paid purchase, refund, ticket email, QR scan, duplicate scan, sold-out state and door sale before launch.

## Merchandise boundary

Ticket orders remain SimpleTix orders paid through Square. Future merchandise remains Shopify commerce. Do not create duplicate Shopify ticket products or sync ticket capacity through a Shopify-to-Square inventory connector.
