# Document Combiner

## Description
This program combines two documents, one in Devanagari script and the other in Roman script, into a single document. It identifies verses in the documents using regular expressions and merges corresponding verses. The combined document alternates between the Devanagari and Roman scripts, with the Roman script text set in italic. Each merged set of verses is separated by a page break.

## Usage
To use this program, ensure you have two documents:
1. A document in Devanagari script.
2. A document in Roman script.

The documents should have corresponding content, structured such that verses or paragraphs end with a specific pattern that can be recognized by a regular expression.

### Steps
1. Install the required Python package `python-docx` by running `pip install python-docx`.
2. Place the script `gita-doc-combine.py` in the same directory as your documents.
3. Modify the `devanagari_path`, `roman_path`, and `output_path` variables in the script to point to your respective input and output documents.
4. Run the script using the command:
   ```
   python gita-doc-combine.py
   ```

## Requirements
- Python 3.x
- `python-docx` library

## License
This project is licensed under the MIT License.

## Author
Suresh Srinivas with OpenAI ChatGPT Assistance
