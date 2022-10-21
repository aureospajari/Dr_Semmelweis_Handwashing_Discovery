# Dr_Semmelweis_Handwashing_Discovery
The Tragic Discovery of Handwashing: t-Tests &amp; Distributions


In this lesson we learn:

<ul>
  <li>How to use histograms to visualise distributions</li>
  <li>How to superimpose histograms on top of each other even when the data series have different lengths</li>
  <li>How to use a to smooth out kinks in a histogram and visualise a distribution with a Kernel Density Estimate (KDE)</li>
  <li>How to improve a KDE by specifying boundaries on the estimates.</li>
  <li>How to use scipy and test for statistical significance by looking at p-values.</li>
  <li>How to highlight different parts of a time series chart in Matplotib.</li>
  <li>How to add and configure a Legend in Matplotlib.</li>
  <li>Use NumPy's .where() function to process elements depending on a condition.</li>
</ul>


# The Tragic Story of Dr Semmelweis

Gather round, gather round. Now I'll tell you how our story ends. Despite the incredible evidence in favour of Dr Semmelweis' theory - that childbed fever was caused by some "substance" (which today we know as bacteria) from autopsy room corpses - was rejected by the medical community at the time. But why?! 

Part of the reason is that Semmelweis was not very tactful. He made it look like doctors were giving childbed fever to women (which they in fact were). This is not something people wanted to hear.

However, he also published his data in the form of long tables **without** any data visualisations:

<img src="https://img-b.udemycdn.com/redactor/raw/2020-10-23_15-25-37-28877dab514343720243ddca867f7da4.png">

The long tables made it very hard to see what's actually going on! Also, at the time statistics and statistical arguments were quite uncommon in the field of medicine.

Eventually, Dr Semmelweis belligerent campaigning made him some powerful and influential enemies. He lost his job at the Vienna hospital, and doctors gave up washing their hands with chlorine. As Dr Semmelweis grew older he got even angrier and eventually quite "strange". This was either the immense frustration or possibly a result of another disease like Alzheimer's or syphilis. In 1865, at the age of 47, Dr Semmelweis was committed to a mental asylum. And at the asylum, he was probably beaten since he eventually died of sepsis, a complication of an infection in the bloodstream. The tragic irony is that sepsis is a similar kind of disease that he fought so hard to prevent in women who died from childbed fever. It wasn't until 20 years later with Louis Pasteur's work on germ theory that Dr Semmelweis' work gained acceptance. RIP Dr Semmelweis.
