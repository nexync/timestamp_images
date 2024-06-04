### Dated Data Review

These files show the ablation results where the number of documents in each month bucket are reduced. To be specific, rather than considering the 5000 most edited topics, we repeat the setup described in the paper instead with the $x$ most edited topics. We plot those averages for LLaMA, RedPajamas, and OLMo. Note that when $x=5000$, this is the same result as in the paper (Figure 4).

We find that for $x > 50$, the effective cutoffs of the three models is consistent with the full results. $x=50$ is the threshold where the trends and effective cutoffs are no longer consistent with the original results due to the more apparent variability when taking few samples. Ulitmately, we find that these extra results are a useful addition to the paper and confirm our main hypotheses for reasonable number of document bucket sizes.

### Results

Original Results
![alt text](https://github.com/nexync/timestamp_images/blob/main/c4_5000.pdf)

Extra Ablations
![alt text](https://github.com/nexync/timestamp_images/blob/main/c4_2500.pdf)

![alt text](https://github.com/nexync/timestamp_images/blob/main/c4_1000.pdf)

![alt text](https://github.com/nexync/timestamp_images/blob/main/c4_500.pdf)

![alt text](https://github.com/nexync/timestamp_images/blob/main/c4_100.pdf)

![alt text](https://github.com/nexync/timestamp_images/blob/main/c4_500.pdf)
