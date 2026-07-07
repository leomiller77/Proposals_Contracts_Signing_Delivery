# Compliance and Payments

When building tools that involve money, compliance is critical. We made a very deliberate architectural choice: **Pactiamo never processes payments.**

## The Merchant of Record Problem
Many platforms attempt to handle payments on behalf of users, which involves complex KYC regulations, holding funds, and charging platform fees. We chose to completely bypass this.

## Bring Your Own Payment Link
Instead of processing the money, we simply display your existing payment methods. You can embed your Stripe checkout, your PayPal link, or even a simple bank transfer QR code. 

When your client signs the contract, they are immediately presented with your link. They pay you directly.

## Benefits for Freelancers
*   **Zero Fees**: We do not take a percentage of your hard earned money.
*   **Instant Payouts**: The money goes straight to your account, so there is no waiting for the platform to release funds.
*   **Maximum Flexibility**: Use whatever payment method works best in your region.
