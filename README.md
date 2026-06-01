# Open SaaS

A launch‑ready, open‑source SaaS boilerplate built on top of the Open SaaS ecosystem and the Wasp full‑stack framework.

It keeps the strengths of the upstream project — React, Node.js, Prisma, authentication, payments, email, file uploads, background jobs, and an admin‑ready foundation — while aiming for a more polished product presentation, cleaner onboarding, and stronger release discipline.

## Demo & docs

- Live demo: _coming soon_
- Documentation: _coming soon_ (will cover setup, deployment, and customization flows)

> If you are evaluating this repository today, start from the README and the upstream Open SaaS and Wasp docs to understand the full development workflow.

## Why this repository exists

This repository is positioned as a production‑minded fork for teams that want the speed of Open SaaS with a more intentional launch posture: clearer messaging, stronger defaults, better documentation, and a tighter path from clone to deploy.

The upstream Open SaaS project already provides a broad, batteries‑included foundation, which makes it a strong base for building and shipping modern SaaS products without paying for a proprietary starter kit.

This fork focuses on turning that technical foundation into something that feels closer to a release‑quality starter product rather than a generic template.

## What is included

Open SaaS ships with the features most teams need to get from idea to first release faster:

- Authentication with multiple providers.
- Payments support for modern SaaS billing flows.
- Email workflows and background jobs for operational tasks.
- File uploads and production‑oriented infrastructure patterns.
- An admin/dashboard foundation suitable for internal tooling and customer‑facing workflows.
- Deployment paths documented through the Open SaaS ecosystem and Wasp tooling.

On top of that, this repository aims to provide a clearer story around launch, evaluation, and ongoing releases.

## Technology stack

The project is built around Wasp, with:

- React on the client side.
- Node.js on the server side.
- Prisma for the data layer.

This stack is a strong fit for founders, indie hackers, consultants, and product teams that want a full‑stack JavaScript workflow with sensible conventions and integrated deployment guidance.

If you are already comfortable with React and Node, Wasp provides structure, batteries‑included features, and a smoother path to production.

## Product direction

This fork is intended to feel less like a generic template and more like a release‑quality starter product.

Key goals:

- Stronger first impression on GitHub.
- Cleaner README and setup flow.
- Better demo presentation and launch assets.
- Higher confidence for new adopters evaluating the repository.
- A clearer path to public releases, changelogs, and production deployment.

Rather than adding highly opinionated, niche functionality, the focus is on polishing the core SaaS experience and making the project feel trustworthy as a starting point.

## Launch principles

To keep the project useful as a general‑purpose SaaS starter, the focus is on operational excellence rather than narrow customization.

That means prioritizing:

- Clear setup and deployment guidance.
- High‑quality default UX.
- Reliable production checks.
- Better repository hygiene.
- Public release readiness.

In practice, this shows up through improved docs, better defaults, and a stronger emphasis on tagged releases and changelogs.

## Quickstart

If you want to get a local copy running quickly:

```bash
git clone https://github.com/Nashwan-Dev/open-saas.git
cd open-saas
npm install
# copy .env.example -> .env and fill required values
npm run dev
```

For detailed instructions and integration‑specific setup (auth, payments, email, storage), refer to the upstream Open SaaS and Wasp documentation.

## Getting started

Recommended onboarding flow:

1. Clone this repository into your own GitHub account.
2. Review the Open SaaS and Wasp documentation to confirm the expected local development workflow and required credentials.
3. Configure the integrations you actually need first, especially authentication, payments, email, and storage.
4. Run locally, validate the main user flows (sign‑up, sign‑in, billing, basic CRUD), then deploy a preview build early.
5. Publish a first release only after the README, demo, and setup instructions are aligned.

Treat this repository as a starting point for your own product, not as an immutable template. Fork it, customize the UX, branding, and flows to match your use case.

## Screenshots

![Landing page](./docs/screenshots/landing.png)
![Dashboard](./docs/screenshots/dashboard.png)
![Billing & subscriptions](./docs/screenshots/billing.png)

Keeping these screenshots up to date with the latest tagged release helps new users quickly understand what they are getting.

## Deployment

For this repository, deployment quality should be treated as part of the product itself.

A production‑ready release should include:

- A working hosted demo.
- A documented environment configuration process.
- Clear guidance for auth, payment, email, and storage providers.
- A changelog tied to tagged releases.
- Screenshots or short demos that reflect the current UI.

You can follow the upstream Open SaaS and Wasp deployment guidance and adapt it to your own hosting provider (e.g., one‑command deployment flows where possible).

## What makes this fork different

The goal is not to replace the upstream project.  
The goal is to package it with a more polished launch experience, stronger repository presentation, and a clearer adoption path for developers who judge a project first by its documentation and release quality.

Planned areas of improvement include:

- Refined branding and repository presentation.
- Better quick‑start guidance.
- Demo‑focused UX polish.
- More visible release management.
- A stronger contributor experience.

As the project evolves, these improvements will be captured through tagged releases and documented in the changelog.

## Roadmap

### Near‑term priorities

- Rewrite and maintain a release‑grade README.
- Add screenshots, demo links, and feature walkthroughs.
- Publish the first tagged release.
- Improve setup clarity for production integrations.
- Add issue templates, contribution guidance, and release notes.

### Longer‑term priorities

- Demo data and onboarding improvements.
- Better starter flows for first‑time users.
- Stronger testing and launch validation.
- More opinionated production defaults.

Roadmap items are intentionally high‑level to keep this repository broadly applicable across different SaaS ideas.

## Contributing

Useful ways to contribute:

- Improve setup clarity.
- Refine the default product UX.
- Strengthen deployment reliability.
- Improve docs, screenshots, and launch assets.
- Report gaps between the README and real project behavior.

If you open a pull request, try to keep it tightly scoped and include a brief explanation of the impact on new adopters and on existing users.

## Who this is for

This repository is a good fit for:

- Founders validating a SaaS idea quickly.
- Developers who want a strong open‑source alternative to paid starter kits.
- Agencies and consultants who need a repeatable SaaS starting point.
- Product teams that want to start from a modern full‑stack baseline instead of assembling common SaaS features from scratch.

If you care about launch quality, documentation, and production readiness as much as code, this fork is designed with you in mind.

## Credits

This work stands on top of the Open SaaS project and the broader Wasp ecosystem.

The upstream project is the technical foundation, and this repository aims to build on that foundation with a more polished public‑facing launch posture.
