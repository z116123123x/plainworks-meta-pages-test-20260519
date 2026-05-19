# Netlify Static Deploy Package: 本月小店可看的官方機會

## Status

```text
package_updated_for_public_surface_value_first_correction
```

## Package Contents

```text
index.html
```

This package contains the approved static HTML sample page for the 7-day channel
test.

## What This Package Is

This is a static deploy package for Netlify.

It is:

- one HTML file
- no build step
- no framework
- no backend
- no scripts
- no forms
- no Netlify feature dependency

It is not:

- a product
- a website platform
- a landing page system
- a lead-capture flow
- a tracking implementation
- a dashboard

## Deployment Authorization

Actual Netlify deployment is not authorized by this package.

```yaml
actual_deploy_authorized: false
```

Deployment requires separate founder authorization and a chosen Netlify surface.

## Netlify Deploy Steps

Allowed static-only deployment path:

1. Open Netlify.
2. Create a new static site or use a one-off static deploy flow.
3. Upload this directory:

```text
deploy/netlify-0017
```

4. Confirm the deployed entry file is:

```text
index.html
```

5. Copy the generated public URL.
6. Record the URL and start time in the measurement CSV.
7. Start the 7-day measurement cycle.

## Required Disabled Features

Do not enable:

- Netlify Forms
- Netlify Analytics
- Identity
- Functions
- Split Testing
- redirects for tracking
- custom tracking scripts
- custom analytics
- lead capture
- email capture
- LINE capture
- payment
- dashboard

## Do Not Change

Do not change:

- approved copy
- official source links
- checked date
- main-list item count
- excluded-list reasoning
- page structure
- visual style

The earlier pre-test freeze was superseded by the founder's 2026-05-18
instruction to update both the website and the Facebook post, then the
founder's clarification that public copy must communicate reader value rather
than lead with boundary language, before starting the formal 7-day cycle.

The current published version is now frozen for the restarted 7-day channel
test:

```yaml
cycle_start: 2026-05-18 17:14 CST
cycle_end: 2026-05-25 17:14 CST
static_page_changes_allowed: false
```

## Measurement Start Condition

The 7-day measurement cycle starts only after there is an external public URL.

Record the start event in:

```text
../../measurement/0017-channel-test-measurement.csv
```

Minimum record:

```csv
date,channel,page_views,unique_visitors,official_source_clicks_total,top_clicked_source,reposts_or_forwards,inbound_feedback_count,shop_category_feedback,repeat_request,consulting_request,note
```

Allowed measurement:

- manual CSV
- social platform native stats
- hosting-native stats only if passively available

Do not add measurement implementation to the page.

## Seven-Day Review Rule

After 7 days, review the channel test.

Continue to review only if there is at least one weak real signal:

- non-internal public visits
- outside repost or forward
- useful shop-category feedback
- repeat request for next month
- official source clicks if available without custom tracking

Kill or stop if:

- only internal views
- no reposts
- no useful feedback
- only consulting / eligibility / application-help requests
- the team wants to add tracking or product features to get better data
