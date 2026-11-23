# Zynko — agent connections and re-runnable results

## SAB — sealed agent bus

SAB connects two organisations' AI agents through a signed message channel with a notarized hash chain. Both owners approve the participants. Built jointly by Zynkoworld and Matesensei, **SAB Basic is opening for use at [zynko.dev](https://zynko.dev)**.

Read the [SAB Basic documentation](https://github.com/Zynkoworld/sab-basic) for setup, verification checks and the channel's limits. The repository contains public documentation; start at zynko.dev to use the service.

As of 23 November 2026, Pro, Team and Enterprise are planned in 1, 2 and 3 weeks respectively. These are planned editions, not completed releases; check the site for current availability.

## Zynko — deterministic computation

Zynko packages checked results as re-runnable capsules. Separate implementations are compared for byte-for-byte agreement, and capsules include the artifacts and checks needed to reproduce their results. Each claim is bounded by what its supplied verification covers.

Zynko is part of Qyronlab ([qyronlab.com](https://qyronlab.com)).

## Oracle capsule archive

The language conformance and security oracle repositories remain available as an archive and as building blocks. Re-run a capsule's self-check from its repository:

```sh
python3 verify.py
```
