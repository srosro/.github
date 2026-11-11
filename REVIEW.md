# Review instructions — .github

Repo-specific reviewer policy. The universal review policy is prepended by the
reviewer and is not restated here.

## What this repo is

Default community health files for srosro's repos: today the shared
`.github/PULL_REQUEST_TEMPLATE.md`. GitHub applies it to every srosro repo that
has none of its own. No code.

**Stage:** internal.

## Review bar

Report **Critical** and **Important** findings only. Nits and style go
unmentioned.

- **No security against coworkers.** Everyone with push access, and our own
  agents, are trusted. Don't propose guards against them.
- **Simplest code wins.** Shorter is better when it does the same thing.

## Where the real risks are

- **Wide blast radius.** The template appears on every srosro PR; flag a change
  that drops a section the review flow relies on (such as the LOC target).
