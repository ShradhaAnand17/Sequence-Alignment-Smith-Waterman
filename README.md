# Smith–Waterman Algorithm for Local Sequence Alignment

This repository contains a **Python implementation of the Smith–Waterman algorithm**, a classical dynamic programming method for **local sequence alignment**.  
It is widely used in bioinformatics to identify regions of similarity between DNA, RNA, or protein sequences.

## 🧾 Overview
- Implements **Smith–Waterman algorithm** for local sequence alignment  
- Constructs scoring matrices based on match, mismatch, and gap penalties  
- Performs **traceback** to identify the best local alignment(s)  
- Outputs aligned sequences and alignment score  

## ⚙️ Algorithm Steps
1. **Initialization** – Build a scoring matrix with zeros in the first row and column.  
2. **Matrix Filling** – Score cells based on match/mismatch and gap penalties.  
3. **Traceback** – Start from the highest-scoring cell and trace back until score is zero.  
4. **Output** – Extract aligned subsequences and report alignment score.  


