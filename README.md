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

[![Hub — splibiplay](https://img.shields.io/badge/Hub-splibiplay-24292f?style=flat-square)](https://github.com/splibiplay/splibiplay)
[![Unity Asset Store — XRCore](https://img.shields.io/badge/Unity%20Store-XRCore-f59e0b?style=flat-square)](https://assetstore.unity.com/packages/tools/ai-ml-integration/xrcore-event-driven-ai-framework-for-unity-xr-366852)

[![xrcore-sdk](https://img.shields.io/badge/GitHub-xrcore--sdk-2563eb?style=flat-square)](https://github.com/splibiplay/xrcore-sdk)
[![xrcore-context](https://img.shields.io/badge/GitHub-xrcore--context-0e7490?style=flat-square)](https://github.com/splibiplay/xrcore-context)
[![xrcore-training-toolkit](https://img.shields.io/badge/GitHub-training--toolkit-7c3aed?style=flat-square)](https://github.com/splibiplay/xrcore-training-toolkit)
[![xrcore-assessment](https://img.shields.io/badge/GitHub-assessment-db2777?style=flat-square)](https://github.com/splibiplay/xrcore-assessment)
[![xrcore-training-authoring](https://img.shields.io/badge/GitHub-authoring-c2410c?style=flat-square)](https://github.com/splibiplay/xrcore-training-authoring)
[![xrcore-voice](https://img.shields.io/badge/GitHub-voice-059669?style=flat-square)](https://github.com/splibiplay/xrcore-voice)

[![xrcore-visionplus](https://img.shields.io/badge/GitHub-vision--plus-0f766e?style=flat-square)](https://github.com/splibiplay/xrcore-visionplus)
[![xrcore-llbridge](https://img.shields.io/badge/GitHub-llbridge-4f46e5?style=flat-square)](https://github.com/splibiplay/xrcore-llbridge)
[![xrcore-analytics](https://img.shields.io/badge/GitHub-analytics-d97706?style=flat-square)](https://github.com/splibiplay/xrcore-analytics)
[![xrcore-ai](https://img.shields.io/badge/GitHub-xrcore--ai-9333ea?style=flat-square)](https://github.com/splibiplay/xrcore-ai)
[![xrcore-ai-mcp](https://img.shields.io/badge/GitHub-xrcore--ai--mcp-7c3aed?style=flat-square)](https://github.com/splibiplay/xrcore-ai-mcp)

*Click a badge to open the GitHub repository or the Unity Asset Store listing.*

## Commercial Packaging

- Sold as standalone infrastructure module.
- Included in XRCore Complete Pack.
- Recommended whenever modules need shared runtime memory and state consistency.
