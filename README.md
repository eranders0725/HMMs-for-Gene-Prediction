This code implements a Hidden Markov Model (HMM) class and a way to construct them from scratch. It finds an HMM from a multiple sequence alignment

**v1: November 2nd, 2025**

Currently able to find an HMM for a protein sequence, and generate "new" samples using the model

**v2: November 3rd, 2025**

Updated the code to:
  - Work for either a protein or nucleotide sequence
  - Included non-zero base-rate probabilities to combat overfitting
  - Better model deletions by including a deletion hidden state.

**v3: November 8th, 2025**

Added:
  - Consensus sequences for an HMM
  - Viterbi Algorithm to analyze an observation

**v4: November 9th, 2025**

Added extra options for extra model flexibility:
   - Base Probabilities in myLog Function
   - Option to consider larger than observed insertions/deletions when scoring
  
