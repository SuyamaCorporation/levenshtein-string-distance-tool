# Levenshtein Edit Distance String Tool

An interactive visualization tool for the Levenshtein edit distance algorithm. Enter two strings (up to 20 characters each) and the app computes the minimum edit distance using dynamic programming, then renders the full DP matrix with the optimal edit path highlighted. Color coding distinguishes insertions (green), deletions (red), substitutions (yellow), and matches (purple) both in the matrix and in the edit sequence view.

## Features

- Computes Levenshtein edit distance for any two strings up to 20 characters
- Full DP matrix rendered as an HTML table with color-coded optimal path
- Traceback algorithm identifies the optimal sequence of edits
- Edit sequence displayed as labeled chips (insert, delete, substitute, match)
- Counts of each operation type (insertions, deletions, substitutions, matches)
- Normalized similarity score: (1 − distance / maxLength) × 100%
- Pre-filled example: "kitten" → "sitting" (classic Levenshtein demo)
- Enter key triggers calculation from either input field
- Accessible: all inputs labeled, table has aria-label, edit sequence uses aria-live
