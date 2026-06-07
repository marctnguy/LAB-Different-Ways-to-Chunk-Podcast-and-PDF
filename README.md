# Different Ways to Chunk Podcast and PDF

This lab explores multiple chunking strategies for two content types: a Trustworthy AI PDF and a podcast transcript.

## Project Structure

- `chunking_strategies.ipynb` - main notebook with data loading, chunking experiments, visualizations, and recommendations
- `lab_summary.md` - short final summary of findings and recommendations
- `resources/` - input files used by the notebook
  - `trustworthy_ai.pdf`
  - `podcast.m4a` 
  - `podcast_small.m4a` (compressed transcription input)

## What This Lab Covers

- Fixed-size character chunking
- Recursive character chunking
- Token-based chunking
- Optional semantic chunking
- Comparison tables and chunk quality analysis
- Final recommendations for PDF and podcast transcript chunking

## How to Run

1. Open `chunking_strategies.ipynb` in Jupyter or VS Code.
2. Install the required packages when prompted by the notebook.
3. Place the source files in the `resources/` folder.
4. Run the notebook cells in order from Step 1 to Step 8.

## Notes

- The podcast transcript must be available as an audio file for transcription.
- If the audio file is larger than the transcription limit, compress it before transcribing.
- Step 5 semantic chunking is optional and may take longer to run.