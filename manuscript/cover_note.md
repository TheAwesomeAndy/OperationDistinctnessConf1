# BIBM 2026 submission note

Dear BIBM 2026 Doctoral Forum Co-Chairs,

The attached manuscript, "Binned Spiking Reservoir Encoding for Perturbation-Characterized Affective EEG Signal Analysis," evaluates a fixed leaky integrate-and-fire (LIF) reservoir with a six-bin spike-count (BSC6) code as a nonlinear temporal encoding operator for affective EEG/ERP observations. Using subject-grouped validation against a classical bandpower/ERP baseline, the study reports balanced accuracy, macro-F1, and macro one-vs-rest AUC, and characterizes the encoding under additive amplitude noise, temporal jitter, and channel dropout, separating representation-level corruption from full raw-signal recomputation.

The result is deliberately bounded. The reservoir embedding is not a uniformly stronger static classifier than classical ERP-derived features, but it exhibits a distinct perturbation-response profile: it retains balanced accuracy more strongly under representation-level amplitude noise and channel dropout, while remaining sensitive to temporal misalignment and severe channel loss when the representation is recomputed from corrupted signals. Characterizing what temporal information a spiking representation preserves, transforms, or suppresses—rather than reporting a single clean-accuracy number—gives a reproducible operating-regime account that can inform preprocessing alignment and electrode-availability decisions for biomedical ERP analysis.

The work fits the IEEE BIBM scope in biomedical signal analysis and the Doctoral Forum route. The first author is the student applicant, primary contributor, and intended presenter; eligibility status (Ph.D. candidate/recently defended doctoral researcher in Electrical and Computer Engineering at Stony Brook University) will be stated accurately at submission, and a one-page CV is appended as requested in the call. This work forms one component of a broader doctoral framework for neuromorphic signal processing of affective neural data, where reservoir, descriptor, graph, and coupling observables are evaluated as distinct biomedical signal representations; the present submission is intentionally focused on the reservoir temporal-encoding component and does not duplicate the broader journal manuscript under preparation.

Sincerely,

Andrew A. Lane
