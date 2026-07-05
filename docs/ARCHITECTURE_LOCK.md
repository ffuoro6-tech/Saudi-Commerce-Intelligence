# Saudi Commerce Intelligence - Architecture Lock

## Business Model
The system sells access to lead records, not monthly subscriptions.

## Core Rules

1. One central database only.
2. Customers do not own the database.
3. Each customer sees only the number of stores they purchased.
4. No device lock is required.
5. Access is controlled by customer lead limit.
6. Permanent Lead Allocation is required.
7. When a customer buys more leads, the system must assign only new stores not previously visible to that customer.
8. Store records are never duplicated for the same customer.
9. Each store has one permanent global Store ID.
10. If store data changes, the same Store ID is updated.
11. If a store becomes inactive, it is marked inactive and not deleted.
12. Data is collected only from public sources.
13. Every customer action must be logged.
14. Admin can increase or decrease customer lead limits.
15. Customers can export only the leads allocated to their account.

## First Version Sources

- Social Media
- Shopify
- Salla
- Zid
- Maroof
- Official Websites
- Public Search Results

## First Version Priority

1. Database schema
2. Customer access system
3. Store allocation system
4. Social collector
5. Export system
6. Admin dashboard
7. Client dashboard
