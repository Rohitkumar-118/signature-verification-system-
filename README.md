# Signature-Matching
Application to detect the similarity of two signatures.

My project develops a signature verification system using pixel and stroke analysis. Since every person has a unique signature, it is widely used as an important method of identity verification. Traditional offline verification methods are less accurate compared to online verification systems. To improve accuracy, we use pixel-based techniques along with Harris and SURF algorithms to analyze and verify signatures. The system compares important features such as index points, corner points, and stroke thickness at different areas of the signature. This approach is more reliable than human analysis and effectively helps in detecting forged signatures.

## Prerequisites
1. Python >=3.6
2. OpenCV
3. Scipy
4. Scikit-image

## Run
1. `pip install requirements.txt`
2. `python main.py`