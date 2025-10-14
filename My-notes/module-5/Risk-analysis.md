#### 🎓 Professor Messer Study Notes

##  Risk Analysis - CompTIA Security+ SY0-701 - 5.2

[Link to video](https://youtu.be/Ykx7t54y-oo?si=fAfryLmwaw69upGw)

### Notes

Risk analysis has two main approaches. Qualitative and quantitative.

Qualitative analysis is a big-picture view. Instead of using numbers to represent levels, we use low, medium, and high.

For example, if we find a device not running antivirus. The impact is medium, the likelihood is high, and the cost of controls medium. That puts the overall risk at very high.

Qualitative analysis helps us to see where we need to focus our attention.

Quantitative analysis uses numbers and formulas to calculate risk in financial terms.

We start with the annualised rate of occurrence (ARO). This tells us how many times a risk might happen in a year.

Next we take the Asset Value (AV). This is the total worth to the business, not just the cost to replace then asset but also the total lost sales, fines, or other impacts.

Then we look at the Exposure Factor (EF). This is the percentage of the asset lost if the risk occurs. If we lose 25% of an asset, EF is 0.25. If the entire asset is gone, EF is 1.0.

Now we can calculate the Single Loss Expectancy (SLE). SLE = AV x EF

For example, if a laptop is stolen and the asset value is £1,000, and we lose the entire laptop. The EF is 1.0 so the SLE = £1,000 x 1.0 = £1,000

To calculate the Annualised Loss Expectancy (ALE) we do ALE = ARO x SLE

If we expect seven laptops to be stolen in a year the ARO is 7. The SLE is £1,000 and we get an ALE of £7,000.

Risk isn’t just about money. We must also factor in life and safety, property, and broader financial impact. People always come first, a laptop can be replaced.

Likelihood Versus Probability. Likelihood is more qualitative (rare, possible, almost certain). Probability is the hard number, often based on history or predictions.

Another key concept is risk appetite versus risk tolerance. Risk appetite is how much risk the organisation is willing to take. Risk tolerance is how much extra they’ll actually allow.

Many organisations use a risk register. This is a document listing every risk tied to a project. Each risk is described, assigned to an owner and given a threshold. The register makes sure everyone knows the risks, and what options exist to manage or avoid them. 
