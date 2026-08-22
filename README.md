SQLtoER — Schema → ER
Turn raw SQL DDL into an Entity-Relationship diagram, instantly, in your browser.

Live demo: koderop.github.io/SQLtoER

What it does?
Paste a SQL script — CREATE TABLE statements plus ALTER TABLE ... ADD FOREIGN KEY clauses — and SQLtoER parses it and renders a clean ER diagram, complete with relationship cardinality (1:1, 1:N, M:N) between entities. No backend, no sign-up, no install, runs completely on browser.

Features:
DDL parsing — reads standard CREATE TABLE definitions and ALTER TABLE ... ADD FOREIGN KEY statements to infer entities and relationships
Multi-dialect support — works with MySQL, PostgreSQL, and generic SQL syntax
Automatic cardinality detection — labels relationships as 1:1, 1:N, or M:N based on key constraints
Instant diagram generation — click Generate diagram and the ER diagram renders immediately
Mermaid-powered output — view and copy the underlying Mermaid source for the generated diagram
SVG export — download the diagram as a standalone SVG file

Usage:
Paste your own SQL script into the input box, or pick one of the sample schemas.
Click Generate diagram.
View the rendered ER diagram, and:
Click Copy Mermaid to grab the Mermaid source for use elsewhere (docs, wikis, Notion, etc.)
Click Export SVG to download the diagram as an image.

Issues and pull requests are welcome. If you find SQL syntax that doesn't parse correctly, please open an issue.
