# FTW Tutorial

Tutorial submission for the Machine Learning for Remote Sensing (ML4RS) workshop at ICLR 2026

## Development

```bash
# Clone the repo
git clone https://github.com/fieldsoftheworld/iclr2026-ml4rs-tutorial.git

# Install the dependencies
conda env create -f environment.yml
conda activate ftw-tutorial
pip install '.[dev]'

# Run formatting/linting
pre-commit run --all-files
```
