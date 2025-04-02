# Unsloth Development Guidelines

## Build & Development Commands
- Install: `pip install -e .`
- Run CLI: `python unsloth-cli.py`
- Environment Variables:
  - `UNSLOTH_COMPILE_DEBUG`: Enable debug mode
  - `UNSLOTH_COMPILE_MAXIMUM`: Enable maximum optimizations
  - `UNSLOTH_COMPILE_IGNORE_ERRORS`: Ignore compilation errors

## Code Style Guidelines
- Licensing: Apache 2.0 header at the top of each file
- Imports: Standard library → Third-party → Local (with blank lines between)
- Type Annotations: Use typing module (Optional, List, Tuple, Union, etc.)
- Naming: snake_case for functions, PascalCase for classes, UPPER_SNAKE_CASE for constants
- Indentation: 4 spaces
- Documentation: Comprehensive docstrings with parameter descriptions
- Error Handling: Specific exception catching with helpful error messages
- Organization: Group related functions, add pass statements with end comments
- Optimizations: Clearly mark patches and performance enhancements
- Version Compatibility: Check versions and provide fallbacks