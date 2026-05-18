# Kaspa UnderDAG — Live BlockDAG Consensus Visualization

Real-time generative art driven by the live Kaspa BlockDAG. Every shape is a real block, every thread a real connection. Watch consensus form as an atmospheric, cinematic experience — not a dashboard, but a living network observatory.

## Live Demo

**[weirdtualguy.github.io/UnderDAG](https://weirdtualguy.github.io/UnderDAG/)**

## How It Works

Fetches live block data from `api.kaspa.org` every 2 seconds, translating block metrics into a dynamic visual system:

- **Blocks** — Each shape is a real Kaspa block. Gold = chain block. Violet = DAG block. Glow brightness reflects validation strength. Larger size means more references.
- **Connections** — Wavy threads are real parent-child relationships from the API. Gold threads link chain blocks. Blue threads link DAG blocks. Each thread has a unique static fingerprint.
- **Pulses** — Expanding rings around blocks with strong consensus. Golden pulses = confirmed chain. Violet pulses = well-connected DAG.
- **Particles & Strands** — Tiny floating dots show transaction flow between connected blocks. Bottom strands represent transactions inside each block.
- **Warp Grid** — Background lines bend toward consensus clusters like gravity warping spacetime. Strong agreement reshapes the network's geometry.
- **Speed** — New blocks race upward. Old chain blocks slow down as they settle into consensus history.
- **Tap-to-Inspect** — Tap any block to see full on-chain data: hash, timestamp, DAA score, blue score, work, transaction count, KAS amount, parents, and children.

Built as a single HTML file with vanilla JavaScript and pure Canvas 2D. No frameworks, no dependencies.

## Made by

[@weirdtualguy](https://x.com/weirdtualguy)

## Support

If you enjoy this project, donations are appreciated.

`kaspa:qp4ljl85vxf6wfj5m46txm9rdnnxdrjwm53wzjhh2we83u2fs8xm5mk5rknv0`
