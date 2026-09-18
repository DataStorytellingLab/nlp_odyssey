# Text Processing with Python: Analyzing *The Odyssey*

## Abstract

This 90-minute workshop introduces text processing and linguistic
analysis with Python and spaCy. Using three translations of Homer's
*The Odyssey*, by Emily Wilson (2017), Robert Fagles (1996), and
Alexander Pope (1725), we learn how to work with spaCy's `Doc` and
`Token` objects, identify named entities and parts of speech, and use
conditional statements to filter text. We will then apply these
techniques to explore characterization in the text.

## Learning Outcomes

By the end of the workshop, students will be able to:

* Load and lightly clean a plain-text dataset using Python.
* Use spaCy to create and explore a `Doc` object.
* Identify and filter tokens using linguistic attributes such as part of speech.
* Extract named entities and examine words associated with particular characters.

## Requirements

The workshop can be completed in Google Colab or another Python
environment with spaCy installed. You will need the three plain-text
files from this workshop repository:

* `wilson.txt`
* `fagles.txt`
* `pope.txt`

### Workflow

1. Download the zip of this folder, via the dropdown on the green
   "Code" button above.
2. Uplaod the `DSL_odyssey.ipynb` to Google Colab.
3. Upload the three `.txt` files to your working environment, via the
   file tab on the left side.
4. Load spaCy by running (press the play button) the first code cell
   on jupyter colab.
5. Run the remaining cells as written.

The notebook is designed to be exploratory. Students are encouraged to
consult the spaCy documentation, experiment with token attributes, and
modify the filters to ask their own questions about the text.

## Further Resources

* spaCy Documentation: https://spacy.io/
* spaCy 101 — Processing Pipelines: https://spacy.io/usage/spacy-101#pipelines
* spaCy `Doc` API: https://spacy.io/api/doc
* spaCy `Token` API and attributes: https://spacy.io/api/token/#attributes
