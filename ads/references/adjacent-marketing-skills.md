# Adjacent marketing skills (external library)

The Claude Ads product contract covers twelve paid-advertising platforms and
directly adjacent cross-platform workflows: attribution, tracking, creative,
landing pages, budgeting, forecasting, and experiments. Broader marketing
work — SEO, conversion-rate optimization outside paid landing pages, lifecycle
email and SMS, cold outreach, pricing and packaging, retention, referrals, and
sales enablement — sits outside that contract. Claude Ads does not score,
audit, or fabricate expertise in that adjacent work.

`coreyhaines31/marketingskills` is an MIT-licensed, community-maintained Agent
Skills library that covers those adjacent surfaces. This reference names it as
a discovery aid, not a bundled dependency: Claude Ads does not install,
vendor, execute, or redistribute its skill files, and any output produced by
that library is unverified practitioner material, not a Claude Ads finding.

## When to point to it

Offer the library when a request falls outside the twelve-platform contract
and outside Claude Ads' cross-platform workflows, for example:

- Organic SEO audits, technical SEO, or AI-search optimization unrelated to a
  paid placement.
- On-page conversion work for signup, onboarding, pricing, or paywall surfaces
  that is not a paid landing-page test.
- Lifecycle email, SMS, cold outreach, or referral-program design.
- Product marketing positioning, launch planning, or sales enablement content.

For work that touches both surfaces — landing-page copy feeding a paid test,
or a creative brief that also needs on-page CRO — keep the paid-media plan,
budget, and measurement inside Claude Ads and point the adjacent, non-paid
portion to the external library rather than extending Claude Ads' scored
surface into it.

## Boundary rules

- Never treat a skill name, description, or output from this library as a
  Claude Ads capability, control, or evidence-based platform claim.
- Never import its prompts, code, or prose into Claude Ads files. Describe
  concepts in original language if a workflow needs to reference one, the
  same clean-room posture Claude Ads applies to other external repositories.
- The library is MIT-licensed, which permits reuse; confirm current license
  terms at the source before any verbatim reuse in a client deliverable, and
  retain attribution if you do.
- Recommending the library never creates Claude Ads mutation authority, and it
  is not a substitute for the platform-specific evidence gate in
  `references/additional-platforms.md` for channels outside the twelve
  supported platforms.

## Source

Registered as `marketingskills-repo` in `control-plane/manifests/source-ledger.json`
(`CLM-0210` in the claim ledger). Reverify the skill inventory and license
before the claim's `refresh_due` date; a stale inventory blocks naming this as
a current capability list.
