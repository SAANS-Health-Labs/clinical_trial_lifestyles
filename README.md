# clinical_trial_lifestyles
Many clinical trials want to exclude participants who have alcohol, drug, or nicotine dependence. Here we screen for such exclusions.

In the most common scenario, clinical trials that mention "alcohol" intend to exclude participants who drink too much alcohol. The same logic applies to smoking and recreational drugs. In these cases, we detect keywords, and label whether a clinical trial is excluding participants based on lifestyle factors.

In the less common scenarios, for example, a clinical trial may want to study cigarettes cesession. In this case, they actually want to recruit participants who smoke.

We need to separate clinical trials into two groups: substance cessation studies and everything else.

If a clinical trial is a substance cessation study, then we know that they DO want participants who drink, use drugs, or smoke.  For each clinical trials in our database, we will verify whether it is a substance related trial.
