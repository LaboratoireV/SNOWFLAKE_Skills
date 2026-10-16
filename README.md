# Snowflake Skills | Snowflake for Beginners and Data Analytics

A practical, end-to-end guide to Snowflake for data analysts, from the first warehouse to analytical workflows. It covers Snowflake's three-layer architecture, a safe practice lab, analytical SQL, window functions, semi-structured JSON, Time Travel and zero-copy cloning, secure data sharing, and performance, security and cost, and ends with a capstone that builds a small analytics product.

## Live site

Visit the [Snowflake Learning Hub](https://the-v-lab.github.io/SNOWFLAKE_Skills/) to start in your browser, or go straight to the [guide](https://the-v-lab.github.io/SNOWFLAKE_Skills/snowflake_guide_en.html).

## What the guide covers

1. **Fundamentals:** what Snowflake is, storage, virtual warehouses and cloud services, object hierarchy and session context.
2. **A safe learning environment:** Snowsight and Workspaces, a lab database and warehouse, a small retail dataset and an optional analyst role.
3. **Data analytics:** data quality, business metrics, time series, window functions, CTEs and views, JSON with `VARIANT` and `FLATTEN`, Time Travel, cloning, data sharing, BI and Python integration, and incremental refresh.
4. **Performance, security and cost:** pruning and caching, warehouse sizing, role hierarchies, masking policies and cost controls.
5. **Capstone:** a business question, acceptance criteria, one implementation and a validation checklist.

It closes with a best-practice checklist, a quick SQL reference, a glossary and links to the official documentation.

## Files

| File | Purpose |
|---|---|
| `index.html` | Learning hub home page: learning path, guide card, routes and key concepts |
| `hub.css` | Styles for the learning hub, shared with the other The V Lab learning sites |
| `og.png` | Social preview image for the learning hub |
| `snowflake_guide_en.html` | The complete guide, a self-contained HTML page |
| `snowflake_styles.css` | Styles used when the guide is rendered |
| `includes/vlab-brand.html` | The V Lab brand component at the top of the guide; it links back to the hub |
| `.nojekyll` | Lets GitHub Pages publish the static files as they are |

The guide's R Markdown source is kept in local working copies and is not published.

## Notes

The SQL examples use a small, made-up retail dataset created in the guide. Running them needs access to a Snowflake account. Snowflake features and pricing change over time, so check the official documentation before relying on any detail.

This is an independent educational resource from [The V Lab](https://vthelab.com/), not an official Snowflake publication.
