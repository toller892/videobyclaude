# Beeswax CTV Explainer

A 60-second animated explainer video covering three core metrics of a Beeswax
(Freewheel Buyer Cloud) CTV campaign: **eCPM**, **fill rate**, and **daily spend**.

- Rendered programmatically with [Remotion](https://www.remotion.dev/) (React + headless Chrome)
- Stylized presenter avatar with synced narration and animated dashboard panels
- Narration audio generated with Google TTS
- Duration: ~53.5s · 1920x1080 · 30fps

All figures shown (eCPM, fill rate, spend) are illustrative placeholder values, not real campaign data.

## beeswax-waterfall.mp4

A 62-second motion-graphics explainer visualizing how a Beeswax-style CTV bidding
waterfall works: bid request → multiple DSP bidders → highest bid wins → ad placement.

- Rendered with [Remotion](https://www.remotion.dev/), narration via Google TTS
- DSP names ("DSP 1/2/3") are generic placeholders, not real company names
- Duration: ~62s · 1920x1080 · 30fps

## beeswax-waterfall-v2.mp4

A 60-second Chinese-subtitled motion graphic (no narration) of the CTV bidding
waterfall: 什么是 Beeswax → 竞价请求 → 竞价瀑布 → 结果. Rebuilt from scratch in Remotion
with Inter + Noto Sans CJK SC. DSP names and all figures are placeholders.

- Duration: 60.0s · 1920x1080 · 30fps

## beeswax-avatar-zh.mp4

A 60-second Chinese explainer hosted by an illustrated presenter avatar in front of a
mock CTV dashboard, covering eCPM, 填充率 and 日消耗. Metric panels slide in and glow as
each is introduced.

- Narration: Microsoft Edge TTS, `zh-CN-YunyangNeural` (male, news style)
- Mouth movement is driven per frame by the narration's loudness; the avatar is a
  stylized illustration, not a photorealistic lip-synced presenter
- All dashboard figures are placeholders
- Duration: 60.0s · 1920x1080 · 30fps

## beeswax-hive-avatar.mp4

"HIVE" — a creative re-imagining of the avatar explainer (same Chinese script and
narration as `beeswax-avatar-zh.mp4`). A holographic presenter is scanned into existence
above a honeycomb projector and walks the viewer through three floating holo-panels:

- **eCPM:** bid comets converge on a CTV audience; the price climbs as demand heats up
- **填充率:** 100 honeycomb cells (one per bid request) fill with honey to 87%, then
  drain as bidders leave, and a diagnostic scan flags targeting / deal issues
- **日消耗:** too-slow vs. burn-out vs. on-pace spend curves racing along a flight timeline
- Synthesized ambient bed + SFX (whooshes, honey ticks, burn-out rumble, chimes)
- Narration: Microsoft Edge TTS `zh-CN-YunyangNeural`; stylized avatar, mouth driven by loudness
- All figures and DSP names are placeholders
- Duration: 60.0s · 1920x1080 · 30fps

## beeswax-hive3d.mp4

The full-3D cut: a real-time WebGL film (Remotion + three.js, rendered in headless Chrome).

- **Presenter:** a procedurally modelled LIDAR-scan bust — ~70,000 glowing points on 154
  contour rings, generated from a signed-distance-field head (brow, eye sockets, nose, lips,
  jaw, ears). Irises glow, eyes blink, and the jaw opens with the narration's loudness.
  It explodes into particles on every cut and re-forms at its next mark.
- **Cold open:** fly-through of a hexagonal light tunnel into a particle burst that
  assembles the head.
- **eCPM:** ~8,000 bid particles spiral into a floating CTV screen; a demand ring fills
  and the price climbs as demand surges.
- **填充率:** a 3D honeycomb of 100 hex prisms (one per bid request) fills with honey to
  87%, drains to 64% as DSP beams withdraw, and a red scan wall flags the causes.
- **日消耗:** light-comets race along a flight-timeline runway; the overspend comet
  shatters on the budget ceiling while a giant ghost of the presenter looks on.
- **Score:** synthesized trailer-style sound design — heartbeat riser, sub-drop impacts on
  every cut, braams, honey plucks, burn-out shatter — ducked under the narration.
- Narration: Microsoft Edge TTS `zh-CN-YunyangNeural`. All figures and DSP names are placeholders.
- Duration: 60.0s · 1920x1080 · 30fps · stereo 48 kHz
