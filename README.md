# Formatting-a-transcript


Problem Statement
-----------------
You are given an unstructured, raw text transcript of a 3-hour meeting
involving up to 30 different speakers. The task is to develop an automated
tool that processes the transcript and formats it with speaker separation,
maintaining the original order and structure.

Objective
---------
Develop a Python function that:
- Parses raw, inline transcripts
- Detects speaker transitions
- Outputs text with clearly separated speaker sections
- Supports up to 30 unique speakers
- Maintains correct speaker order and preserves statements

Approach
--------
1. Tokenize the transcript by replacing ": " with line breaks.
2. Detect speaker tokens that start with "SPEAKER" and end with a colon.
3. Accumulate each speaker’s statement until a new speaker appears.
4. Output the transcript in the following format with this exact indentation:

SPEAKER1:
Statement.

SPEAKER2:
Statement.

Technologies Used
-----------------
- Python (no external libraries)
- Simple string manipulation and token-based parsing



