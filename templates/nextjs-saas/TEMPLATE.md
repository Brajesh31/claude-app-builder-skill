# Next.js SaaS Template

Use when the product has tenant-aware accounts, subscription plans, and billing.

## Core domains
- Users and organizations/tenants
- Memberships and roles
- Plans, subscriptions, invoices, and entitlements
- Audit events and usage records

## Required safeguards
- Verify billing webhooks and make handlers idempotent.
- Derive entitlements from trusted server-side subscription state.
- Enforce tenant isolation in every query.
- Never trust client-submitted plan or role values.
- Define trial, cancellation, failed payment, and refund behavior.

## Delivery sequence
Start with account lifecycle and tenant authorization, then billing integration, webhook processing, entitlements, usage controls, and operational reporting.
