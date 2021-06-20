# Largest Contentful Paint (LCP) meaning

Tiny example showing how LCP is broken, and how to 'fix' it.

There are 5 stages, use `git checkout <tag-name>` to explore
each step.

# Setup First clone the repo then checkout the first tag:

```
git checkout 1-initial-score-100-everything-no-images
```
Don't know how to run it? Just open in your browser, or run with python:

# Run & perform lighthouse chec

```
python3 -m http.server
```
Then visit http://127.0.0.1:8000

Then do a Chrome lighthouse speed check.

# Checkout the next stages to see what changes
```
git checkout 1-initial-score-100-everything-no-images
# Run lighthouse...look at code
git checkout 2-img-tag-score-drop-98-77-93-92
# Run lighthouse...look at code difference
git checkout 3-fix-img-attributes-score-100-100-100-100
# Run lighthouse...look at code difference
git checkout 4-lower-score-lcp-elemt-delay-98-100-100-100
# Run lighthouse...look at code difference
git checkout 5-fix-LCP-element-score-100-100-100-100
```

# Learn
All the metrics are explained here also:
https://web.dev/vitals/
