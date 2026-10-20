<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/hero-dark.png">
    <img src=".github/assets/hero.png" alt="about.me.at landing page" width="880">
  </picture>
</p>

<h1 align="center">about.me.at</h1>

<p align="center"><strong>About me: my background, skills, and the path so far as a full-stack software engineer.</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/status-live-171717?style=flat-square" alt="Status: live">
  <img src="https://img.shields.io/badge/license-source--available-404040?style=flat-square" alt="License: source-available">
  <img src="https://img.shields.io/badge/part%20of-me.at-737373?style=flat-square" alt="Part of me.at">
</p>

<p align="center">
  <a href="https://about.me.at">Website</a> ·
  <a href="#features">Features</a> ·
  <a href="#how-it-works">How it works</a> ·
  <a href="#built-with">Built with</a>
</p>

A resume flattens a career into dates and bullet points. I built about.me.at to hold the parts it leaves out: how I got into software, where the years went, the tools I reach for, and how to find me elsewhere. It is deliberately the smallest shape in my family of apps: one page, authored inline, prerendered to static HTML, with no content pipeline and no client-side fetching.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/overview-dark.svg">
    <img src=".github/assets/overview.svg" alt="about.me.at at a glance: one page prerendered, toolbox by job, identity you can verify, calm by default" width="880">
  </picture>
</p>

## Why about.me.at

- **What a resume leaves out**: the story, the work history and the toolbox, told in my own words on one page.
- **Small on purpose**: authored inline and prerendered, so a visit is plain static HTML with nothing to fetch.
- **Verifiable**: profile links are allowlisted and published as `rel="me"` and `sameAs`, so they can be checked from the other end.

## Features

- **One static page**: a hero, a toolbox band, a facts strip, then the story, work history, network, elsewhere, and colophon sections, prerendered to static HTML.
- **Toolbox by job**: tools grouped into labelled columns by what they are used for, with the primary stack emphasized.
- **Facts strip**: years of experience, career track, and location, kept in one place so they stay current.
- **Structured identity**: schema.org `AboutPage` JSON-LD and an IndieWeb h-card on the page.
- **Verified profiles**: outbound profile links are allowlisted and published as `rel="me"` and `sameAs`.
- **Calm motion**: CSS-only animation that stops under `prefers-reduced-motion`, in a grayscale palette with light and dark themes.

## How it works

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/flow-dark.svg">
    <img src=".github/assets/flow.svg" alt="How about.me.at works: author, prerender, describe, verify" width="880">
  </picture>
</p>

The copy is written inline in the page's own modules and prerendered once, so a visit is plain static HTML. The page describes me in schema.org `AboutPage` JSON-LD and an IndieWeb h-card, and every outbound profile link is allowlisted and published as `rel="me"` and `sameAs`, so a profile that links back confirms both ends.

## Built with

<p>
  <img src="https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 16">
  <img src="https://img.shields.io/badge/React-19-171717?style=flat-square&logo=react&logoColor=white" alt="React 19">
  <img src="https://img.shields.io/badge/TypeScript-5-262626?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-4-404040?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS 4">
</p>

- Next.js 16 (App Router), React 19, TypeScript
- Tailwind CSS 4
- next-intl for localized family chrome
- Shared `*.me.at` app shell (header, footer, theme, auth)

## Part of the me.at family

about.me.at is one of my [`*.me.at`](https://me.at) apps. They share one design system, account, and app shell. Development happens in a private monorepo; this repository is the project's public-facing home.

## License

Source-available. See [LICENSE](LICENSE).
