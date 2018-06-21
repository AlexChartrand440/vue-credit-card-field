# vue-credit-card-field

This is meant to be a standalone Vue component that mimics the UI/UX of Stripe.js without using an iframe AND is fully compatible with Boostrap 4. This component is no way meant to replace Stripe.js if you are already using it. However, this component is a great alternative for processors such as Authorize.net or as an alternative to having individual fields littering your form.

### Features

- Fancy UI/UX to that attempts to mimic Stripe.js's proven design
- Fully compatible and designed for Bootstrap 4
- Extensible and written in ES6
- Responsive for mobile, tablets, and desktop
- Inline error handling and client side validation fields on a form

### Basic Usage

![Basic Usage Example](screenshots/basic-usage.gif)

### Inline Error Handling

![Error Handling Example](screenshots/error-handling.gif)

### Sample Syntax

    <credit-card-field v-model="card"></credit-card-field>
