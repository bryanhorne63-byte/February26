# RISE 360 block – Free text question (14 UK allergens)

A self-contained HTML widget that reproduces this free-text question for use in
**Articulate Rise 360**:

> **Name FOUR of the 14 major allergens recognised in UK law.**
> Free text – learner types their own answer, then reveals the model answer and feedback.

## File

- [`allergens-free-text.html`](allergens-free-text.html) – the complete block (HTML + CSS + JS, no dependencies).

## How to add it to Rise 360

Rise 360 has no native free-text-with-feedback block, so use an **Embed** block:

1. **Host the file** somewhere reachable by a URL (e.g. GitHub Pages, your LMS,
   or any web host). Note the public URL of `allergens-free-text.html`.
2. In your Rise 360 lesson, add a block → **Multimedia → Embed**.
3. Choose **Embed code** and paste an iframe pointing at the hosted file:

   ```html
   <iframe src="https://YOUR-HOST/allergens-free-text.html"
           width="100%" height="520" frameborder="0"
           title="Free text question – 14 UK allergens"></iframe>
   ```

   (Or choose **Website link** and paste the URL directly.)
4. Adjust the iframe `height` if needed once the model answer is revealed.

### Quick preview

Open `allergens-free-text.html` directly in any browser to test it before embedding.

## The 14 major allergens (UK law)

Celery · cereals containing gluten · crustaceans · eggs · fish · lupin · milk ·
molluscs · mustard · nuts · peanuts · sesame · soybeans · sulphur dioxide/sulphites.
