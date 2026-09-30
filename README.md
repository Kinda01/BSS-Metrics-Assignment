# BSS-Metrics-Assignment
Metrics Assignment
Biometrics Systems Security
01 Metrics



Exercise 1
Compute d' for the content of /content/test.csv.
For /content/test.csv:
•	Impostor observations: 50
•	Genuine observations: 50
•	Impostor mean: 0.345342
•	Genuine mean: 0.731026
•	Impostor variance: 0.025400617636
•	Genuine variance: 0.039974415124
Using the supplied formula: d_prime = 2.13324462836214. So, approximately: d' = 2.13
 
Exercise 2: Threshold meaning
The threshold is the minimum similarity score required to accept a match:
•	score >= threshold: accept the match
•	score < threshold: reject the match
•	Increasing the threshold generally decreases FMR and increases FNMR.
Exercise 3: FMR and FNMR at EER
fnmr, fmr, eer_threshold = compute_sim_fmr_fnmr_eer(output)

print("FNMR:", fnmr)
print("FMR:", fmr)
print("EER threshold:", eer_threshold)
Result:
FNMR: 0.16
FMR: 0.16
EER threshold: 0.5374

Exercise 4: FMR versus TMR AUC
auc, fmrs, tmrs = compute_sim_fmr_tmr_auc(output)
print("AUC:", auc)
Result:
AUC: 0.9376
Exercise 5: Histogram
plot_hist(output)
This plots impostor scores in red and genuine scores in blue. The title should show approximately: Score distribution, d'=2.13
 
Exercise 6: ROC/AUC plot
plot_sim_fmr_tmr_auc(output)
The plot displays the FMR versus TMR curve with: AUC: 0.94







