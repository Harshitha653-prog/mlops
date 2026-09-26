# Model Registry

The current model is version v2, a linear regression trained on x3 and x4, with an R² of 0.5300. This improves significantly on the previous version, v1, which used only x4 and achieved an R² of 0.2750; the added x3 feature captures more of the target variance and produces a materially better fit. The current model remains the active version in the registry, while the earlier single-feature model is still preserved for comparison and rollback.
