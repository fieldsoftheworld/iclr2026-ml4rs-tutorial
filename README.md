# FTW Tutorial

Tutorial submission for the Machine Learning for Remote Sensing (ML4RS) workshop at ICLR 2026

## Development

```bash
# Clone the repo
git clone https://github.com/fieldsoftheworld/iclr2026-ml4rs-tutorial.git

# Install the dependencies
conda env create -f env.yml
conda activate ftw-tutorial
pip install -e '.[dev]'

# Run formatting/linting
pre-commit run --all-files
```
