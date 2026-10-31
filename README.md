# AI Neuron 3D

An interactive 3D neuron rendered as a single self-contained web page.

The scene shows a translucent neuron — dendrites, a soma with a glowing
nucleus, a myelinated axon, and a vesicle-packed synaptic bouton over a
cleft with postsynaptic receptors — inside a sci-fi HUD with a live
membrane-potential waveform, ion-channel levels, and synapse statistics.

Firing runs an explicit nine-state simulation: RESTING → DEPOLARIZATION →
CALCIUM ENTRY → VESICLE DOCKING → FUSION → RELEASE → DIFFUSION → RECEPTOR
BINDING → RECOVERY. Membrane voltage, the waveform, the axon pulse,
calcium levels, vesicle docking and fusion, and neurotransmitter release
all derive from that state.

## Controls

- FIRE SPIKE — sends an action potential down the axon and releases
  glutamate across the cleft
- Camera views: Overview, Soma, Synapse, Macro Synapse
- Toggles: X-Ray, Labels, Glow, Spin
- Auto-fire and signal-speed controls
- Orbit, zoom, and pan by mouse or touch

## Running it

Open `index.html` in a browser, or serve the directory with any static
file server. The page is one file with no build step and no external
assets. On GitHub Pages it serves from the repository root.

Owners: Nova Parr, Ahmad Ali Parr, and Team HoloTwinKitty.
License: see `LICENSE`.
