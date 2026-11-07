# Guide publication checklist

Use this for every InterviewAlpha guide, not only the ATS article. The preview site stays noindex. Live search setup happens only on an approved page in the product, after Tom says it can go live.

Indexing and ranking are not guaranteed. Do not add third-party analytics or tags.

## Before writing

- [ ] Name the search intent in one sentence, and the reader who needs it.
- [ ] Check existing InterviewAlpha guides and do not publish a second page with the same job to do.
- [ ] Keep one clear topic. A related question can be a short section or a separate guide, not a stuffed aside.
- [ ] Prefer original, useful examples and one action the reader can take. Label fictional examples as illustrative. Do not invent statistics, name real private people, or imitate a product screen.
- [ ] Use official, academic, or government sources when a claim needs a citation. Name the organisation, and keep the country or study in a compact source note. Do not repeat "this is not true everywhere" through the article. State a local difference only when it changes what the reader should do, such as length, a photograph, or personal details.
- [ ] Design it as a practical editorial handbook: expressive serif headings, a readable body face, a measure near 60 to 68 characters, real whitespace, and a numbered chapter rhythm. Original artwork can open the piece. Do not ship a card grid, a dashboard, or labelled outline boxes and call it a redesign. Template packs are inspiration only. Do not copy or embed them.
- [ ] No creator, vendor, or video-pack references in the reader-facing article. Practical findings can stay without those names.

## Draft and preview

- [ ] Title states the topic in plain language. Meta description says what the reader will learn. No keyword stuffing and no promise of ranking.
- [ ] One H1. H2s follow the order of the article. In-page links use those headings.
- [ ] Essential advice is real HTML text. Artwork has a text alternative. Do not bake the only copy of the advice into a picture.
- [ ] The whole article has a magazine rhythm, including later chapters, the checklist, and the sources. Print should read as a handbook, not a shrunken desktop page.
- [ ] Self-host the fonts you use, with `font-display: swap`, a licence file, and explicit image dimensions. Prefer the live brand faces only when the licence allows it.
- [ ] Fictional examples are marked illustrative.
- [ ] The page is readable on a narrow phone and on a desktop. Checklist controls still copy and print. Print hides site chrome, not the checklist text.
- [ ] Related links point at real pages that have been opened and checked. Omit a link you have not checked.
- [ ] Preview banner, `noindex, nofollow, noarchive`, and no live canonical. Do not add Article or review markup that pretends the preview is the published URL.
- [ ] Reading time is counted from the draft, not copied from an older version.
- [ ] No em dashes or en dashes in reader-facing language.

## When Tom approves the live page

Do these on the live URL only. Leave review previews noindex.

- [ ] The live URL returns 200 and the article text is in the HTML, not only in an image or a script.
- [ ] Remove the preview banner and the preview `noindex` / `nofollow` / `noarchive` tags, and any `X-Robots-Tag` that blocks that URL. Do not remove noindex from other drafts.
- [ ] `robots.txt` allows the live guide URL.
- [ ] The live page has one canonical link to the live URL, not to a preview host.
- [ ] The URL is in the live sitemap, and the guides index links to it.
- [ ] Title, meta description, and H1 match the approved article.
- [ ] Add only structured data that is true: an Article (headline, live URL, dates you actually published or updated) and a breadcrumb for the real path. Do not invent an author, star rating, or review. Do not add FAQ markup just to chase a rich result.
- [ ] Social title, description, and image match the article. The image is one you have rights to use.
- [ ] Check a phone-width layout and a basic performance pass. Fix anything that hides the text or breaks the checklist.
- [ ] Show the real published date and the real updated date when the page changes.
- [ ] Where someone authorised for the property can do it, submit or refresh the sitemap in Search Console and inspect the live URL. Until that is done, say it has not been checked. Do not report the page as indexed unless the inspection says so.

A published page can still take time to be indexed, and a listing is not a promise of traffic.
