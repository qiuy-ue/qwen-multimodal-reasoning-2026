# Experiment Table

## Submission history

| Artifact | Evaluation stage | Score | Interpretation |
| --- | --- | ---: | --- |
| V4 | Preliminary | **41.8** | Best preliminary SFT model |
| V4 baseline | Final-round protocol | 18.2 | Compliant starting point for RL |
| RLX30 | Final | **20.2** | V4 plus 30 GRPO steps |

## RL dose and pool ablations

| Variant | Change | Score |
| --- | --- | ---: |
| RLX10 | 10 GRPO steps | 19.2 |
| RLX20 | 20 GRPO steps | 15.2 |
| RLX30 | 30 GRPO steps | **19.6–20.2** |
| RLX50 | 50 GRPO steps | 17.8 |
| RLX60 | 60 GRPO steps | 16.8 |
| PH1 | Physics-focused pool | 18.8 |
| H7 | Counting-focused pool | 16.4 |
| H9K16 | Group size 16 | 16.6 |

The final score recorded for RLX30 was 20.2. Repeated reads of the same artifact varied because the platform evaluation was noisy.
