# Contribution Guidelines

Please note that this project is released with a [Contributor Code of Conduct](code-of-conduct.md). By participating in this project you agree to abide by its terms.

Thank you for your interest in contributing to the Awesome Japanese List! We're excited to collaborate with you. This list thrives on the valuable contributions from contributors like you. Here’s how you can help make the Awesome List even more awesome.

## How to Contribute

### Suggesting New Resources

1. **Check for duplicates**: Before adding a new resource, please ensure it is not already listed or suggested.
2. **Create a new issue**: Use the issue template to suggest your resource. Please include the name, link, and a brief description of why it's a valuable addition.
3. **Pull request**: Once your suggestion has been acknowledged, you can submit a pull request. Please see the section below on how to do this properly.

### Nominating Your Own App or Resource

Self-nominations are welcome — if you built an app, site, or resource that fits the list, you're encouraged to submit it. We only ask that you're up front about it: in your pull request, tick **"I'm affiliated with this item"** under *Your Role* so we can note the affiliation for transparency. Submissions are judged on the same quality bar as any other, regardless of who submits them.

#### Eligibility for Self-Nominated Items

Awesome Japanese is a curated list of genuinely useful Japanese-language content and tools. It is **not** a place for marketing or self-promotion, and a listing is not a launch announcement. To keep self-nominations to resources with a proven track record, an item you nominate yourself must meet **both** of the following:

1. **At least 6 months old.** The item must have been publicly available for at least six months before the pull request is opened. Betas and soft launches count from the date the public could actually use it.
2. **At least 100 users, if it's paid.** If the item has paid plans, in-app purchases, or freemium tiers (i.e. it carries the `:moneybag:` emoji), it must have at least 100 users (registered accounts, active subscribers, or paying customers — any honest measure is fine).

**Proof is required.** Tick the boxes under *Self-Nomination Eligibility* in the pull request template and attach evidence. Either kind is accepted:

- **Public records** — for example a dated launch post, changelog, blog announcement, App Store or Google Play listing showing the release date, Wayback Machine snapshot, public download or review counts, or a press mention.
- **Private records** — for example a screenshot of your analytics, store console, or billing dashboard. Don't post private records on the public pull request; instead say in the PR that you'll provide proof privately, and a maintainer will reach out to arrange it. Private records are used only to verify eligibility and are never published.

Self-nominated pull requests that don't meet these requirements, or that lack proof, will be closed. You're welcome to resubmit once the item qualifies. These requirements apply only to self-nominations — a resource nominated by an unaffiliated third party is not subject to them.

### Improving Existing Resources

- If you notice a resource that could be improved or updated, please open an issue detailing your proposed changes.

### Documentation and Miscellaneous

- Suggestions for improving the documentation or any other non-code aspects of the project are welcome. Please open an issue to discuss your ideas.

## Submitting a Pull Request

1. Fork the repository.
2. Create a new branch for your contribution (`git checkout -b new-resource`).
3. Add your resource or make your changes in the relevant section.
4. Commit your changes with a clear and descriptive message (`git commit -m "Added [Resource Name]"`).
5. Push the branch to your fork (`git push origin new-resource`).
6. Open a pull request from your fork to the original repository.

## Entry Format

Add each item as a single list line in the form:

```markdown
- [Name](https://example.com) - Short description ending with a period.
```

- Use the linked **Name** for the resource, followed by ` - ` and a description.
- Capitalize the description and end it with a period.
- Prefer `https://` links, and confirm the link works before submitting.
- **Pricing:** don't use the word "free" in a description — items without the `:moneybag:` emoji are already treated as free, so it's redundant. If the item has freemium tiers, in-app purchases, or paid plans, add `:moneybag:` instead. See the emoji legend at the top of the [readme](readme.md).
- **Pricing changes after merge:** if an item starts charging money later (paid plans, in-app purchases, or freemium tiers), please open a pull request to revise its description and add the `:moneybag:` emoji. Entries that begin charging without being updated may be removed without warning.
- **Generative AI:** add the `:robot:` emoji if either applies — the item **uses** generative AI in the product itself (e.g. an AI tutor, AI-graded practice, or AI-generated example sentences), *or* the item was **mostly built with** generative AI, meaning AI did most of the work (the *"Mostly AI (>50%)"* answer in the pull request's AI Assistance survey). Light AI assistance during development is now common and does **not** qualify on its own — the bar is >50%. This is a neutral tag for transparency, not a judgment of quality. See the emoji legend at the top of the [readme](readme.md).

## Guidelines

- Ensure your contribution is in line with the project's theme and quality standards.
- Keep the **description to one concise sentence, under 100 characters** — count only the visible description text (the name, link URLs, and any emoji don't count toward the limit). This is checked automatically when you open a pull request, so an over-length description will fail the Markdown lint check.
- Provide a clear and concise description for each contribution.
- Check your spelling and grammar.
- Please disclose any affiliation if you own or are connected to the resource, so we can note it for transparency (see *Nominating Your Own App or Resource* above).
- Self-nominated items must be at least 6 months old and, if paid, have at least 100 users, with proof (see *Eligibility for Self-Nominated Items* above).
- Read **Editorial Independence** below before submitting an item you're connected to.

## Editorial Independence

Inclusion on this list is editorial. Items are chosen on merit alone, and being listed is never conditional on anything given in return:

- **No link exchange.** You don't need to link back to this list, and offering to won't help your submission.
- **No paid placement.** Listings are not for sale. Nobody has paid to appear here.
- **No affiliate or referral links.** Don't add tracking or referral parameters to a resource you're submitting.

Please don't offer, request, or arrange a reciprocal link, payment, or other consideration in exchange for a listing. Pull requests that do will be closed.

### The "Featured on Awesome Japanese" Badge

If your resource is already listed, you're welcome to display this badge on your own site or README:

[![Featured on Awesome Japanese](https://awesome-japanese.japantv.app/assets/badge.svg)](https://awesome-japanese.japantv.app/?utm_source=badge)

Copy-paste Markdown and HTML snippets are in the [readme](readme.md#featured-on-this-list). The badge is entirely optional. Displaying it earns no preferential treatment, and taking it down will never get an item removed.

## Questions?

If you have any questions or need further clarification on how to contribute, please don't hesitate to open an issue or contact the maintainers directly.

Thank you for your contributions, and let's make this Awesome List even better together!
