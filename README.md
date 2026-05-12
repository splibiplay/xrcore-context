# XRCore Context

[![Unity](https://img.shields.io/badge/Unity-2022%2B%20%7C%20Unity%206-black)](https://unity.com/)
[![Module](https://img.shields.io/badge/Module-Context%20Infrastructure-2563eb)](#)
[![Depends](https://img.shields.io/badge/Depends-XRCore%20SDK-7a3cff)](https://github.com/splibiplay/xrcore-sdk)
[![Contract](https://img.shields.io/badge/Contract-Events%20%2B%20State-0ea5e9)](#)

Neutral runtime context layer for XRCore ecosystems.

## Published foundation (Unity Asset Store)

Install the core SDK from Unity first, then add this module via Git URL:

- [XRCore – Event-Driven AI Framework for Unity XR](https://assetstore.unity.com/packages/tools/ai-ml-integration/xrcore-event-driven-ai-framework-for-unity-xr-366852)

## Value in 2 Minutes

1. Install XRCore SDK + Context.
2. Open the context demo scene.
3. Ingest sample events during Play Mode.
4. Inspect live context state and persistence snapshot.

## What It Adds

- canonical event/state contracts (`XRContextContract`)
- in-memory context store with bounded ring buffer
- runtime access point (`XRContextRuntime`)
- optional JSON persistence provider
- editor debugger for live context inspection

## Ecosystem Position

```text
XRCore SDK
   ↓
XRCore Context (infrastructure)
   ↓
Training / Voice / VisionPlus / LLBridge
   ↓
Analytics / Enterprise workflows
```

## Related XRCore Modules

- Hub: [splibiplay](https://github.com/splibiplay/splibiplay)
- SDK: [xrcore-sdk](https://github.com/splibiplay/xrcore-sdk)
- Training Toolkit: [xrcore-training-toolkit](https://github.com/splibiplay/xrcore-training-toolkit)
- Assessment: [xrcore-assessment](https://github.com/splibiplay/xrcore-assessment)
- Authoring: [xrcore-training-authoring](https://github.com/splibiplay/xrcore-training-authoring)
- Voice: [xrcore-voice](https://github.com/splibiplay/xrcore-voice)
- VisionPlus: [xrcore-visionplus](https://github.com/splibiplay/xrcore-visionplus)
- LLBridge: [xrcore-llbridge](https://github.com/splibiplay/xrcore-llbridge)
- Analytics: [xrcore-analytics](https://github.com/splibiplay/xrcore-analytics)

## Commercial Packaging

- Sold as standalone infrastructure module.
- Included in XRCore Complete Pack.
- Recommended whenever modules need shared runtime memory and state consistency.
