Kritvi and Iker meeting 24/02 notes

Conclusions from pre processing:

- RGB means and intensities are similar across the board --> Can convert to grayscale
- Increase contrast --> image processing
- Line detection needs to be explored
- Edge detection cant be used by itself (too much noise)
    - Could be implemented in combination with line detection

Next steps:
- Explore different models:
    1. Line + edge detection 
    2. CNN
    3. Anomaly detection (CNN trained on cracked data)
    4. Using already available models for cracked detection

To be done by friday:
- Explore grayscale conversion and contrast (Kritvi)
- Outlier detection (Iker)