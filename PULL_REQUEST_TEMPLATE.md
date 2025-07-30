# Pull Request Checklist

Please check to indicate:
(Keep all code up to standard where possible, not just new code)

- [ ] Files are appropriately named in `snake_case.py` format

- [ ] Included any new files you have created

- [ ] Run ALL scripts and tests which depend on this code

- [ ] Code adheres to style guidelines

- [ ] Code formatted correctly - extraneous comments and commented out code are removed - difficult parts of the code are commented as to WHY it is the way it is.

- [ ] Code checked over with typechecking (`pyright` or `pyrefly`)  enabled to check, use casts and/or pragmas to keep this clean where necessary 

- [ ] Code is sufficiently simple and not overly verbose (split any complex parts, each method will do exactly ONE thing and can fit well within a single screen)

- [ ] Tests have been written for algorithmically complex parts (including making code properly testable by factoring out such parts)
