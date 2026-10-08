# Zones website — rider-story design alternative

One self-contained, dark athletic/editorial design alternative. The original prototype is preserved separately; this version replaces its feature-led composition with a rider journey. Open `index.html` directly, or serve this directory on loopback:

```sh
python3 -m http.server 8767 --bind 127.0.0.1
```

Visit <http://127.0.0.1:8767/>. No build, dependencies, remote fonts, external assets, tracking or network services are required.

## The alternative

- A wide, unframed development capture anchors “Your effort changes. Ride with it.” rather than a small phone inside a hero card.
- A zone-green chapter connects choosing a workout to the beginning of a ride.
- A larger iPhone ride view brings the reader into the session before an open, two-track illustration explains drift, power response and lag.
- Completed-ride reflection closes the story. Hardware and availability follow; missing iPad/Mac captures are explicitly tracked in a compact native disclosure, not a placeholder gallery.
- Native anchor navigation and a keyboard-operable capture-status disclosure provide the interactions. Only the illustrative traces animate, once.

## Internal review only

This is a visual prototype, **not a production website or an approved public release**. Three owner-supplied development captures are used locally: landscape ride, iPhone workout detail and iPhone ride. Both ride views show **development simulation, not a launch feature**. These images are not release-approved or evidence of a hardware-live ride; candidate and data provenance remain unconfirmed. The iPad and two native Mac views remain explicitly pending in “About the captures”. The landscape capture's platform is unconfirmed and is never called iPad or Mac.

### Local-only images

`/local-assets/` is git-ignored and must not be committed, uploaded or published. To view the supplied captures locally, place the unmodified portrait PNGs at:

- `local-assets/iphone-ride.png`
- `local-assets/iphone-workout.png`
- `local-assets/ride-landscape.png`

Portrait originals are 920 × 2000; the landscape original is 2000 × 920. The page preserves their whole-image proportions, including development labels. Without these files, native `<object>` fallbacks show honest labeled capture placeholders, including with JavaScript disabled. With JavaScript enabled, native full-image inspection links appear only after the image loads successfully; without scripts, the complete embedded captures remain visible and can be inspected using browser zoom. No screenshot manipulation or public asset approval is implied.

Approved release captures for all five slots, appropriate data handling and public-use provenance remain required before publication. Do not publish the locally supplied development images as launch screenshots.

The chart uses illustrative values on separate heart-rate and power tracks. Its single 1.1-second entrance is progressively enhanced, viewport/visibility gated, and disabled or stopped for reduced motion. The complete final illustration, content and native anchor navigation work without JavaScript.

Support/privacy sections explicitly describe their unpublished status. No store destinations, support contact, legal policy, seller record or launch dates have been invented. Approved release facts, assets, compatibility evidence and publication details are still needed. Browser validation of this study does not validate the native app or certify accessibility/legal compliance.

## Review and promotion

Review this alternative against the preserved original, including desktop/mobile layout and normal/reduced-motion behavior, before production implementation. The user-authorized `dev` branch retains the original; `design/story-led-prototype` is the separate source alternative. The intended later promotion path is **dev → stage → prod**; stage/prod branches, deployment configuration and public hosting are not created by this prototype. Publication requires separate approval. No Pages activation or public asset publication is included.