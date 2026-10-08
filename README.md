# Zones website — local design prototype

One self-contained, dark athletic/editorial design study. Open `index.html` directly, or serve this directory on loopback:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Visit <http://127.0.0.1:8765/>. No build, dependencies, remote fonts, external assets, tracking or network services are required.

## Internal review only

This is a visual prototype, **not a production website or an approved public release**. Two owner-supplied development captures are used locally: iPhone ride and planning. The ride shows **development simulation, not a launch feature**. These images are not release-approved or evidence of a hardware-live ride; candidate and data provenance remain unconfirmed. The iPad and two native Mac views remain explicit placeholders. No unconfirmed landscape capture is assigned to a platform.

### Local-only images

`/local-assets/` is git-ignored and must not be committed, uploaded or published. To view the supplied captures locally, place the unmodified portrait PNGs at:

- `local-assets/iphone-ride.png`
- `local-assets/iphone-plan.png`

Both supplied originals are 920 × 2000. The page preserves their whole-image proportions, including development labels. Without these files, native `<object>` fallbacks show honest labeled capture placeholders, including with JavaScript disabled. With JavaScript enabled, native full-image inspection links appear only after the image loads successfully; without scripts, the complete embedded captures remain visible and can be inspected using browser zoom. No screenshot manipulation or public asset approval is implied.

Approved release captures for all five slots, appropriate data handling and public-use provenance remain required before publication. Do not publish the locally supplied development images as launch screenshots.

The chart uses illustrative values on separate heart-rate and power tracks. Its single 1.1-second entrance is progressively enhanced, viewport/visibility gated, and disabled or stopped for reduced motion. The complete final illustration, content and native anchor navigation work without JavaScript.

Support/privacy sections explicitly describe their unpublished status. No store destinations, support contact, legal policy, seller record or launch dates have been invented. Approved release facts, assets, compatibility evidence and publication details are still needed. Browser validation of this study does not validate the native app or certify accessibility/legal compliance.

## Review and promotion

Review the desktop/mobile layout and both normal-motion and reduced-motion behavior before production implementation. The user-authorized `dev` branch exists for source development. The intended later promotion path is **dev → stage → prod**; stage/prod branches, deployment configuration and public hosting are not created by this prototype. Publication requires separate approval. No Pages activation or public asset publication is included.