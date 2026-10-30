# QuoteFlow
## Customer requests into reviewed quotations

QuoteFlow is an AI-assisted quotation application developed for my consulting work. It connects request intake, item extraction, catalog matching and quote preparation while keeping a person in control of the final quotation.

**Context:** Individually developed consulting application in active use. Public case-study material must use fictional customer requests and sample catalog data.

## Who it is for and what it solves

Sales and operations teams need to turn incoming customer requests into clear, editable quotes. QuoteFlow addresses the handoffs between reading a request, identifying products and preparing a document for customer review.

## How it works

1. A customer email enters the quotation workflow through Gmail integration.
2. Claude helps extract structured request items from the message.
3. Matching logic supports catalog, customer and job identification.
4. A user reviews and edits the quotation draft before approval.
5. Approved information is used to generate a professional PDF quote.

## My contribution

I developed the application individually, connecting email intake, AI-assisted extraction, matching logic, editable drafts, approval handling and PDF output. The implementation combines language-model assistance with explicit review rather than treating generated content as final.

## Implementation and evidence

The reviewed source snapshot implements Gmail integration, Claude calls, Supabase-backed records and PDF quotation generation. The snapshot also includes tests and an approval check before quote creation.

## Access and boundaries

The application is used in my consulting work. Source code and customer records are not included in this showcase, and the current deployment is not an unrestricted recruiter demo. A public walkthrough should demonstrate the process using sample data without connecting to a live mailbox or sending a quotation.

This case study describes the reviewed source snapshot. A sanitized walkthrough is planned to make the workflow accessible without exposing business records.
