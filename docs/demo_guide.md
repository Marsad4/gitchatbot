Real Estate Company — Knowledge Base
About Acme Realty (example)

Acme Realty is a full-service real estate firm operating in the Greater Metro area. We provide residential and commercial brokerage, property management, leasing, investment advisory, and construction consulting. Our mission is to simplify property decisions by combining local market expertise, transparent processes, and modern technology.

Contact

Headquarters: 123 Market Street, Metro City

Phone: +1 (555) 123-4567

Email: info@acmerealty.example

Website: https://acmerealty.example

Table of contents

Company Overview

Services Offered

Current Listings (sample data)

Neighborhood Guides

Buying Process (step-by-step)

Selling Process (step-by-step)

Renting & Leasing

Mortgage & Finance (guides & calculators)

Property Management

Legal, Compliance & Disclosures

Agent Directory (sample)

Data / Feed / Update policy (how content is updated)

FAQ (company-specific)

Glossary (real-estate terms)

Example questions for the chatbot

1. Company Overview

Acme Realty was founded in 2008 and now manages over 3,000 residential units and 150 commercial properties. We help buyers, sellers, landlords, and tenants with transaction advisory, valuation, and post-closing services. Core values: integrity, local expertise, and client-first service.

Key differentiators:

Local agents with average 8+ years experience

Proprietary market analytics dashboard updated weekly

24/7 property maintenance hotline for managed properties

2. Services Offered

Residential Sales

Home valuations, listing, open houses, negotiation, closing support.

Commercial Sales & Leasing

Office, retail, industrial brokerage, lease audits, tenant representation.

Property Management

Tenant screening, rent collection, maintenance coordination, accounting & monthly reporting.

Investment Advisory

Portfolio analysis, cap-rate modeling, acquisition and disposition support.

Construction & Renovation Consulting

Budgeting, contractor vetting, project timeline management, quality inspections.

Corporate Relocation

Home search for relocating employees, temporary leasing, orientation tours.

3. Current Listings (sample)

Note: In production, listings are stored in data/listings/ (CSV or JSON) and refreshed nightly via the feed.

Listing: 101 Park Ave, Apt 12B

Type: Residential — Condominium

Price: $525,000

Beds: 2 | Baths: 2 | Size: 1,100 sq ft

Neighborhood: Downtown Core

Listing ID: ACME-RES-101-12B

Agent: Sara Khan (sara.khan@acmerealty.example
)

Key Features: City views, hardwood floors, renovated kitchen, in-building gym

URL: /listings/ACME-RES-101-12B

Listing: 500 Commerce St — Warehouse Unit 8

Type: Commercial — Industrial

Price: $1,250,000

Size: 12,500 sq ft

Zoning: Light industrial (M1)

Listing ID: ACME-COM-500-08

(Add more entries or a feed; ingestion supports text/JSON/CSV files — see Data section.)

4. Neighborhood Guides

Downtown Core

Average sale price (last 12 months): $550k

Popular amenities: transit hub, restaurants, coworking spaces

Typical buyer profile: young professionals, investors

Westbrook Suburbs

Typical lot size: 0.15–0.25 acres

School district: Westbrook Unified (ratings and links)

Commute: 25–40 minutes to Downtown by car or express bus

(Each neighborhood file should include: boundaries, transit, schools, prices, rental demand, typical inventory.)

5. Buying Process (step-by-step)

Pre-qualification: Meet lender to get pre-approved for a mortgage.

Search: Define must-haves, use agent & MLS to shortlist homes.

Offer: Submit offer with deposit; negotiate terms.

Inspection & Due Diligence: Hire inspector; review disclosures.

Financing & Appraisal: Lender orders appraisal; finalize mortgage docs.

Closing: Sign documents, transfer funds, get keys.

Documents buyers should prepare:

Photo ID, proof of income, pre-approval letter, tax returns (if requested).

6. Selling Process (step-by-step)

Valuation & Strategy: Comparative Market Analysis (CMA) and pricing strategy.

Prep & Staging: Repairs and staging plan.

Marketing: Photos, floor plans, virtual tours, listing syndication.

Showings & Offers: Receive offers and negotiate.

Contract to Close: Inspections, repairs, escrow, closing table.

Seller disclosures and local forms are stored in docs/forms/.

7. Renting & Leasing

Landlord workflow

Create listing → screen tenants (credit + background) → sign lease → move-in inspection → maintenance & rent collection.

Tenant workflow

Apply → pay deposit → sign lease → move-in.

Standard lease lengths: 6, 12, 24 months. Security deposit rules: follow state/local regulation (see docs/legal/landlord_tenant_law.md).

8. Mortgage & Finance

Mortgage basics

Down payment, interest rate, term, APR, PMI, property taxes, HOA dues.

Quick calculator examples (static formulas)

Monthly payment formula: M = P * r * (1+r)^n / ((1+r)^n - 1) (P = principal, r = monthly rate, n = number of payments)

Loan products explained

Fixed-rate mortgage, adjustable-rate mortgage (ARM), interest-only loans, FHA/VA programs.

Affordability checklist

Debt-to-income ratio, reserves, closing costs estimate, pre-approval letter.

9. Property Management

Services included

Rent collection, bookkeeping, vendor management, legal eviction support, preventive maintenance.

Reporting

Monthly statements, occupancy/turnover reports, expense breakdowns.

Maintenance SLAs

Emergency: 24 hours; Routine: 3–7 business days depending on issue severity.

10. Legal, Compliance & Disclosures

Agency disclosure, lead-based paint disclosure (if applicable), local landlord-tenant law summary, fair housing policy, privacy policy.

All contract templates live in docs/forms/ and should be date-stamped when updated.

11. Agent Directory (sample)

Sara Khan — Senior Sales Agent

Email: sara.khan@acmerealty.example

Phone: +1 (555) 222-3333

Markets: Downtown Core, Westbrook Suburbs

Bio: 10+ years closing residential transactions.

David Lee — Commercial Broker

Email: david.lee@acmerealty.example

(Keep a CSV data/agents.csv or data/agents.json for structured ingestion: fields: id, name, email, phone, markets, bio.)

12. Data & Feed / Update Policy

Sources of truth

Listings: nightly feed (data/listings/*.json or feeds/listings.csv) updated by the ops team.

Neighborhood stats: weekly update from analytics (data/market_stats/YYYY-MM-DD.json).

Documents & forms: versioned in docs/forms/.

Ingestion guidelines

Filename conventions: listings-YYYYMMDD.json, neighborhood-downtown.md, agents.csv.

Preferred formats: Markdown / plain text for docs; JSON/CSV for structured data.

Large files: break long docs into topic files (e.g., buying/step1_prequalification.md) to help chunking.

13. FAQ (company-specific)

Q: How do I schedule a viewing?
A: Contact the listing agent shown on the listing page or use the scheduling widget on the listing URL.

Q: What are your management fees?
A: Residential management: 8% of monthly rent + fixed onboarding fee. Commercial: negotiated per contract.

Q: How long to sell my home?
A: Varies by market; average days on market in Downtown Core: 35 days (last 6 months).

14. Glossary (short)

MLS: Multiple Listing Service

CMA: Comparative Market Analysis

NOI: Net Operating Income

Cap Rate: Annual Net Operating Income / Purchase Price

15. Example questions for the chatbot

"What is the price of 101 Park Ave, Apt 12B?"

"Who is the agent for ACME-RES-101-12B?"

"How do I apply for a rental in Westbrook?"

"What services does Acme Realty provide for landlords?"

"What is the selling process?"

"List the neighborhoods you serve and their commute times."

"When was the last update to the listings feed?"