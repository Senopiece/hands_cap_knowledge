#conclusion
#dimensionality_reduction

Dimensionality reduction is somewhat needed as stated in [[Why a dimensionality reduction after features extraction is needed]]

There are several approaches to do so:
- KFD
- LDA
- NLDA
- ULDA
- OLDA
- OFNDA
- LDA/QR
- AKDA/QR
- PCA
- BS

Despite LDA being the most preferrable choice ([[LDA is the common choice for dimensionality reduction]]), some applications are using KFD: [[KFD over LDA]], and PCA: [[englehart2001wavelet]]

Seems like `KFD > LDA > PCA` based on the section 4.3 of [[raurale2019emg]]

Also seems like `NLDA > PCA` based on the proposed approach of [[chu2006real]]

[[phinyomark2012application]] compared may dimensionality reducers-features combinations, as for the dimensionality reduction LDA, ULDA, OLDA, OFNDA was the best (that also counts into `LDA > PCA`).