## Ablation Versions

### 1. TLearn_SimSplit<br>
   This version replaces XGBoost with TLearn, and separates data without changing the underlying values. Essentially just does a naieve split of the data, giving no real change to the "treatment" group.

### 2. TLearn<br>
   This version replaces XGBoost with TLearn and separates data but also changes the underlying values. This version gives real effects to the "treatment" group.

### 3. Causal (Main Version I Tested With)<br>
   This version replaces XGBoost with Causal and separates data but also changes the underlying values. This version gives real effects to the "treatment" group.

## Run Results (All Ran On Causal.ipynb)

### 1. high<br>
   Encoder: 0.7
   Decoder: 0.4

### 2. mid <br>
   Encoder: 0.7
   Decoder: 0.2

### 3. low <br>
   Encoder: 0.5
   Decoder: 0

## comparison file
   This one is just a helper to create the aggregated results graphs from the multiple runs
