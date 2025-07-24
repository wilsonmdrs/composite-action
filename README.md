# 📚 Composite Actions Library

This document contains a collection of reusable **composite GitHub Actions** designed to standardize workflows across multiple projects.

You can use these actions from any other repository by referencing:

```yaml
- uses: wilsonmdrs/composite-actions/<framework>/<type>/<action>@main
  with:
    # custom inputs depending on the action