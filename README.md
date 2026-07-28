# What the World Looked Up

Static D3 visualisation of Wikipedia page views.

## Publish on GitHub Pages

1. Create a new GitHub repository and push this folder to its default branch.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select the default branch and the **/(root)** folder.
4. Save. GitHub will provide the public site URL; it opens through `index.html`.

## Required data

The chart reads `data/merged_2026.csv`. Add that file before publishing. It must include these columns:

```csv
Page,Month,Views,Tier
Example article,January,1000000,Sustained
```

`Month` values must be January through June, and `Tier` must be `Sustained`, `Recurring`, or `Spike`.
