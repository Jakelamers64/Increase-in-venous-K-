---
output: pdf_document
bibliography: bibliography.bib
csl: american-chemical-society.csl
---

<!---pandoc --bibliography=test.bib --citeproc -o test.pdf test.md--->

Increase in venous [K+] During Hyperbaric Exposure Independent of Changes in pH or O2 Concentration

Increase in venous [K+] During Hyperbaric Exposure

# Abstract
Plasma potassium regulation is important for function of numerous cells in the body. Changes in potassium levels during exposure to an increased O2 concentration is thought to be the result of the changes in pH and increasing reactive oxygen species. However, the effects of hyperbaria on plasma potassium concentration are not well understood.

Eight subjects were exposed to 1.3 atmospheres absolute (ATA) of hyperbaric air for 90 minutes, 10-times (M-F) over 12-days. Another eight subjects were exposed to 100% oxygen at 1 ATA over the same interval. Four venous blood draws were taken. On day 1 the first draw was taken immediately preceding treatment and the second was taken immediately following treatment. The third draw was taken prior to the 10th treatment and the 4th draw was taken 72 hours post final treatment. We analyzed samples on a blood gas analyzer and performed statistical analysis using a paired Wilcoxon signed-rank test.

The concentration group saw strong trend towards an increase in the potassium concentration from 4.09 ± 0.12 (mmol/L) to 4.28 ± 0.28 (mmol/L) (p = 0.065). In the hyperbaric group we see a significant increase in potassium concentration from 4.19 ± 0.26 (mmol/L) to 4.55 ± 0.27 (mmol/L) (p = 0.0068). In the concentration group we also see a significant increase in pH concentration from 7.37 ± 0.03 to 7.39 ± 0.01 (p= 0.021). A similar significant increase is not seen in the hyperbaric group.

These finding suggest that changes in potassium concentration in response to hyperbaria are not the result of oxygen concentration nor pH. Possible explanations include increased nitrogen levels due to hyperbaric air, increased CO2 concentration in hyperbaric chamber or changes in the activity of Na+,K+ ATPase pumps at the cellular level which may be a homeostatic response to combat pulmonary edema

Keywords: Potassium, Hyperbarics, Hyperoxia

# Introduction

Modulation of inspired $O_2$ concentration has been used as an effectives treatment for many conditions. The two main methods to administer this concentration increase are by directly varying concentration of inspired gases or by varying the ambient pressure. By combining these to aspects of concentration, three of the main modes of $O_2$ administration are obtained. These are hyperbaric $O_2$, concentrated $O_2$ and hyperbaric treatment. According the UHMS hyperbaric oxygen therapy ($HBO_2$) is defined as exposure to near 100% $O_2$ while inside a pressurized chamber at greater than sea level pressure.[@moon_hyperbaric_2019] As of July 2021 the FDA has cleared $HBO_2$ for 13 different conditions.[@noauthor_hyperbaric_2021] In contrast hyperbaric treatment is exposure to an increase in pressure without an increase in administered gas $O_2$ concentration. Finally concentrated oxygen is the exposure to $O_2$ gas with a higher concentration of $O_2$ than normal air.


Effects of hyperoxia on blood metabolites


Effects of hyperbaria on blood metabolites


One metabolite of interest in this study was potassium. Plasma potassium levels are dependent on a multitude of factors and result from the interplay of intracellular and extracellular changes and intake and execration rates.[@aronson_effects_2011; @adrogue_changes_1981] Regulation of these levels within normal ranges is of extreme importance to the function of various cells in the body.[@youn_recent_2009] Effects of increased inspired $O_2$ on plasma potassium remain ambiguous.[@adrogue_changes_1981] A few studies have demonstrated an increase in plasma potassium while others have found no similar increase.[@adrogue_changes_1981; @fraley_isohydric_1976] However the fact hypoxia has been shown to cause an increase in arterial potassium levels and cause changes in expression of Voltage gated K+ channel in pulmonary arterial myocytes through $HIF1-\alpha$ indicates some pathway through which potassium levels are modulated via changes in $O_2$ concentration.[@barlow_effect_1994; @whitman_endothelin-1_2008; @dong_hypoxia_2012; @semenza_regulation_2009] In contrast the effects of hyperbaria on plasma potassium levels are much less understood.

# Methods

Healthy adult subjects were recruited via REDCap using university of Wisconsin's email list. A questionnaire was administered to determine characteristics of individuals such as pre-existing conditions and age. Individuals who responded to the survey were selected at random contacted via phone. Participants in the study were separated into two groups. The first group received hyperbaric treatment in altitude sickness bags (n=14) while the second group received concentrated oxygen at room pressure (n=12).

Although treatment varied between groups, treatment schedule remained consistent and was the following. Subjects arrived Monday and height and weight were determined. Blood collected via venipuncture before treatment was used for a baseline metabolic panel and analyzed on arterial blood gas (ABG) machine. Following blood draws subjects underwent 1.5 hours of their respective treatments. After treatment blood was collected to determine acute response in blood metabolites. Following this, treatment was given Tuesday through Friday of the following week, taking a break for weekends where no treatment was administered. A blood draw and ABG analysis was preformed before the tenth and final treatment. After a weekend of no treatment following the final treatment a blood draw occurred and subsequent analysis was preformed.

A total of 36 metabolic indicators were reported by the ABG machine. Indicators were compared pairwise between the four draws. Statistical analysis and data visualization was performed using R (The R Foundation) and paired Wilcoxon tests.

# Results

# Discussion

Possible Explanations
-

Limitations
- dietary restrictions for potassium not used
- single draw for each patient
- difference in subjects between groups

# References



![Comparison of plasma potassium concentration before and after treatment in the hyperbaric group](C:\Users\jakel\github\Increase-in-venous-K-\Figures\hyper_K+.jpeg)

![Comparison of plasma potassium concentration before and after treatment in the concentrated oxygen group](C:\Users\jakel\github\Increase-in-venous-K-\Figures\conc_K+.jpeg)

![Comparison of plasma sodium, chloride and bicarbonate concentrations and pH levels before and after treatment in the hyperbaric group](C:\Users\jakel\github\Increase-in-venous-K-\Figures\hyper_ions.jpg)

![Comparison of plasma sodium, chloride and bicarbonate concentrations and pH levels before and after treatment in the concentrated oxygen group](C:\Users\jakel\github\Increase-in-venous-K-\Figures\conc_ions.jpg)
