# Quadar ForbocAI Integration

Quadar is a game-facing integration surface for the ForbocAI TypeScript SDK. It
demonstrates how a browser game can supply runtime evidence to game-agnostic
NPC intelligence while retaining authority over its own rules and world.

- Play Quadar: <https://platform.forboc.ai>
- ForbocAI SDK documentation: <https://docs.forboc.ai/npm/welcome>
- Account and API keys: <https://account.forboc.ai>

## Integration Flow

Quadar's ForbocAI boundary follows one direction:

1. The game supplies an NPC identifier, structured persona, current
   observation, allowed actions, and relevant world context.
2. The TypeScript SDK transports the signed multi-round protocol and executes
   client-owned vector-memory or Soul operations requested by the API.
3. The ForbocAI API performs orchestration, inference, decision making,
   rationale, diagnosis, and validation.
4. The SDK returns normalized dialogue, action, and evidence data.
5. Quadar decides how validated results affect its world and presentation.

This keeps game mechanics in Quadar, intelligence policy in the API, and the
SDK as the reusable input/output and persistence boundary.

## ForbocAI Surfaces

Quadar's ForbocAI surface is designed for NPC interaction, context-sensitive
decisions, memory-aware responses, validated action proposals, and autonomous
playtest diagnostics. These capabilities consume
structured game evidence without placing Quadar names, maps, levels, rules, or
canon inside Servitor.

The hosted ForbocAI API is selected by the SDK without URL configuration. An API
key remains a runtime secret and must not be embedded in browser assets, source
control, logs, or saved game data.

## Related SDKs

- TypeScript SDK: <https://github.com/ForbocAI/sdk>
- Unreal Engine SDK: <https://github.com/ForbocAI/sdk-ue-5>

## License

All rights reserved. See [LICENSE](./LICENSE).
