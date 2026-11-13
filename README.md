# CS781: all original model and task notebooks

This collection contains all ten uploaded production notebooks: Model A, B and C
Phase 1 notebooks, the later fast Model D pretraining notebook, and the complete
Phase 2–7 notebooks. The task notebooks retain every original experiment arm,
including alternatives to the selected best runs. They are not seven winner-only
workflows.

Long Markdown explanations and checklists have been reduced to section headings.
Code cells, saved outputs, execution counts, settings and experiment-selection
flags are unchanged. The source uploads have not been overwritten. Previously
saved errors and incomplete output logs are retained as part of the run record;
this cleanup does not imply that every configured experiment finished or that a
fresh run was performed.

## Notebook index

| Notebook | Original uploaded filename |
|---|---|
| [Phase1_ModelA_Causal_LM.ipynb](Phase1_ModelA_Causal_LM.ipynb) | `notebookc45d82fccb(1).ipynb` |
| [Phase1_ModelB_Encoder_Decoder.ipynb](Phase1_ModelB_Encoder_Decoder.ipynb) | `notebook87aa906066.ipynb` |
| [Phase1_ModelC_GQA_RoPE.ipynb](Phase1_ModelC_GQA_RoPE.ipynb) | `notebook3a9d824e6c.ipynb` |
| [ModelD_Fast_Pretraining.ipynb](ModelD_Fast_Pretraining.ipynb) | `notebooka23cae87f4.ipynb` |
| [Phase2_All_Experiments_NER.ipynb](Phase2_All_Experiments_NER.ipynb) | `phase2endtiend.ipynb` |
| [Phase3_All_Experiments_RR.ipynb](Phase3_All_Experiments_RR.ipynb) | `phase3end2end.ipynb` |
| [Phase4_All_Experiments_CJPE.ipynb](Phase4_All_Experiments_CJPE.ipynb) | `phase4end2end.ipynb` |
| [Phase5_All_Experiments_LSI.ipynb](Phase5_All_Experiments_LSI.ipynb) | `phase-5.ipynb` |
| [Phase6_All_Experiments_Summarization.ipynb](Phase6_All_Experiments_Summarization.ipynb) | `phase6.ipynb` |
| [Phase7_All_Experiments_Retrieval.ipynb](Phase7_All_Experiments_Retrieval.ipynb) | `notebooke4773fa26b.ipynb` |

## Execution

Open the relevant notebook in Kaggle and inspect its configuration cell before
running it. Retain the original GPU setup and data/checkpoint inputs for the run
you intend to reproduce. Private or gated Hugging Face inputs require a token
provided through Kaggle Secrets or the environment, never pasted into public code.
Preserved output paths describe the original sessions; files under
`/kaggle/working` must be restored in a new session.

The Model D fast-pretraining notebook is the later checkpoint-producing run for
downstream phases, not evidence of the original Phase 1 D leaderboard submission.
The multi-experiment notebooks retain their original run controls; keeping an arm
in the implementation does not automatically enable or retrain it.

This archive contains notebook code and saved cell outputs, not dataset files,
trained model weight files or original prediction ZIP files. Individual task
notebooks write their runtime modules when the setup cells are run.
