# Afzal Siddiqui

**Lead Mobile Engineer — identity, payments and trust at consumer scale.** Dubai, UAE.

I build the client-side systems people trust with their money: account and onboarding flows, payment surfaces, and the shared iOS frameworks that let multiple product teams ship against one foundation. Seventeen years in production iOS, the last seven on UAE banking apps serving over a million users.

## What I work on

**Payments and Apple platform integration** — issuer-side Apple Pay provisioning (pushing cards to Wallet via PassKit), Apple Pay acceptance in consumer apps, tokenised card storage, and a payment gateway SDK embedded by third-party merchant apps.

**Identity and trust** — document capture and OCR with Vision, face match and liveness, NFC passport reads, biometric authentication, and the security frameworks that sit under them.

**Shared iOS foundations** — versioned Swift Packages consumed by more than one production app, with the migration paths and release discipline that come with owning an API other teams depend on.

**On-device intelligence** — Core ML in live transaction paths, Vision-based document understanding, and inference that stays on the handset.

## Open source

| Project | What it is |
| --- | --- |
| [flux-ios-foundation](https://github.com/AfzalSiddiqui/flux-ios-foundation) | 26 SwiftUI components in Atomic Design layers — atoms, molecules, organisms — each with its own ViewModel, all visuals driven from design tokens, no hard-coded values |
| [flux-ios-experience](https://github.com/AfzalSiddiqui/flux-ios-experience) | The showcase app — 29 interactive screens with live variant, state and theme switching |
| [Signal-iOS](https://github.com/AfzalSiddiqui/Signal-iOS) | Type-safe async/await networking — generic client, Codable models, typed errors, token refresh, LRU cache with TTL, retry with backoff |
| [MotionKit-iOS](https://github.com/AfzalSiddiqui/MotionKit-iOS) | Reusable SwiftUI animations behind a protocol-based effects architecture |

I also maintain React Native counterparts of the Flux, Signal and MotionKit libraries, and build AI-driven fintech prototypes in TypeScript and Python.

## How I think about mobile

Shared systems over duplicated logic. Tests that run on every pull request, not just before release. Architecture chosen for what it costs as well as what it gives — modularising a codebase buys parallel builds and pays for it in package boundaries and dependency wiring, and both halves belong in the decision.

## Stack

Swift 6 · SwiftUI · UIKit · Swift Concurrency · Core ML · Vision · PassKit · StoreKit 2 · Core Data · Swift Package Manager · XCTest / XCUITest · Fastlane · Jenkins · iOS 15–26

---

📍 Dubai, UAE · open to relocating · [LinkedIn](https://www.linkedin.com/in/afzalsiddiqui214/) · afzal.siddiqui214@gmail.com
