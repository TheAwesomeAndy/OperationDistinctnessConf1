# IEEE BIBM 2026 — Doctoral Forum Cover Note

Dear Dr. Yi He and Dr. Xingquan Zhu,

I am pleased to submit "On the Non-Invariance of Robustness Metrics: Baseline-Floor and Imputation Effects in Perturbed EEG Representations" for the IEEE BIBM 2026 Doctoral Forum. The paper treats channel dropout and amplitude noise as perturbations of a representation and asks whether the resulting robustness rankings of affective-ERP representations are intrinsic or are artifacts of *how* robustness is measured. Auditing four representations under subject-grouped validation — spectral band-power, ERP-window amplitudes, a fixed training-free leaky integrate-and-fire reservoir, and a trained EEGNet — it isolates two evaluation confounds: an *accuracy-floor* confound (relative-retention metrics reward near-chance representations) and a *zero-imputation* confound (zeroing dropped channels injects out-of-distribution values that penalize non-centered features).

The contribution is that correcting these confounds *reverses* the naive conclusion. Under the standard protocol a near-chance fixed reservoir appears the most channel-robust; with an above-chance metric and train-mean imputation, ERP-window features become the most robust fixed encoder, and a trained EEGNet recovers nearly all of its apparent dropout fragility once standard augmentation is added — separating robustness contributed by the representation from robustness contributed by training. The fixed, training-free reservoir is used as an accuracy- and imputation-invariant reference whose zero-centered embedding is, by construction, invariant to the imputation choice; it is this property that exposes the artifact affecting the other encoders. We close with a short corrected reporting protocol for EEG robustness studies.

The work fits the Doctoral Forum: it engages the current EEG robustness-evaluation literature, uses conservative subject-grouped validation with confidence intervals and a permutation null, and reports negative and reversed results honestly. The first author is currently enrolled in the Ph.D. program in Electrical and Computer Engineering at Stony Brook University, is the primary contributor, and will present the work if accepted; a one-page CV of the first author is appended as required by the call.

Sincerely,

Andrew Lane
