# RideRent requirement traceability

| Requirement | Implemented in website |
|---|---|
| RF-01 Register | Register page with duplicate-email and validation checks |
| RF-02 Login | Login page, session state, protected routes, logout |
| RF-03 Search cars | Rent a car page with text/category/price filters |
| RF-04 Car details | Vehicle detail route with model/category/seats/price/availability |
| RF-05 Reserve car | Date validation + reservation creation + availability check |
| RF-06 Manage reservations | My reservations page + active/cancelled status + cancel action |
| RF-07 Create shared ride | Create shared ride workflow |
| RF-08 Search shared rides | Shared rides page with origin/destination/date filters |
| RF-09 Join shared ride | Join action, seat decrement, full-ride protection, activity persistence |
| RF-10 Admin vehicles | Protected `/admin` page for add/edit/deactivate vehicles |

## Non-functional requirements
- Responsive layouts for desktop/tablet/mobile.
- Semantic labels and keyboard-focusable controls.
- Clear success/error validation messages.
- Reusable React components for cards, buttons, forms, alerts and page titles.
- English-first interface, with copy structured so i18n can be added later.
- localStorage is used only as a prototype persistence layer; production authentication must use a backend with password hashing and secure sessions.
