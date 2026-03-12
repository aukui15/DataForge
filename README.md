# DataForge

A Python library for automated data pipeline construction and ETL workflows.

## Features
- Pipeline construction DSL
- Automatic data validation
- Built-in connectors for popular databases
- Parallel processing support

## Installation
```bash
pip install dataforge
```

## Quick Start
```python
from dataforge import Pipeline

pipeline = Pipeline()
pipeline.add_step("extract", extract_function)
pipeline.add_step("transform", transform_function)
pipeline.add_step("load", load_function)
pipeline.run()
```

## License
MIT License