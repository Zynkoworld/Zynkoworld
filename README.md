# Zynko — proven computation, shipped as re-runnable capsules

Zynko is a deterministic proving system: a claim only counts when independently-authored implementations re-derive it **byte-for-byte**. This account publishes the proof artifacts themselves — oracle capsules you can re-run on your own machine.

**What's here.** Oracle capsules: security detectors per CWE class and language, and CPU/GPU determinism maps. Each repo ships the actual ratified engine (vendored, not described), its probe set, and a self-check:

```
python3 verify.py
```

If the check fails, the capsule is invalid — you don't have to trust us, and you shouldn't.

**The method.** Three separately-authored implementations, derived from the same published spec — never from each other — must agree byte-for-byte before anything is ratified. Disagreement halts ratification instead of shipping. The only allowed states are *proven*, *honestly-not-yet-proven*, and *momentarily-unknown* — never a false green.

**Today / Horizon.** Today: the capsules in this account, re-runnable as-is. On the horizon: a proving network where verified results are reused instead of recomputed. We publish the boundary honestly — what is proven is re-runnable here; what isn't yet, we say so.

**Site:** https://zynko.dev · **Contact:** info@zynko.dev
