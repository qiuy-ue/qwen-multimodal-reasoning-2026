# Reproduction Notes

The public archive records the model family, training stages, public hyperparameters, reward definition, ablation results, and release boundaries.

The following remain private or competition-controlled: trained weights, original images, hidden questions, raw server logs, and submission archives.

## Safe reproduction checklist

1. Prepare a compatible Qwen multimodal checkpoint and accelerator environment.
2. Replace every internal path with a local argument.
3. Use legally shareable data with the same conversation and answer format.
4. Recreate the V4 SFT configuration from `configs/v4-sft.example.yaml`.
5. Start RL from the resulting SFT checkpoint and apply the RLX30 configuration.
6. Validate answer extraction locally before comparing results.

The published scores are competition observations and are not a guarantee for a different dataset, checkpoint, or hardware stack.
