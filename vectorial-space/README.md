# Vectorial space demo

A [Streamlit](https://streamlit.io/) demo of the embedding tech behind vector databases: phrases are encoded with `sentence-transformers`, projected to 2D with PCA and compared by cosine similarity — add your own phrases and query the space interactively.

## Running

```bash
pip install -r requirements.txt
streamlit run vectorial_space_demo.py
```
