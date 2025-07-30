# Pull Request Checklist

Please check to indicate:
(Keep all code up to standard where possible, not just new code)

- [ ] Files are appropriately named in `snake_case.py` format

- [ ] Included any new files you have created

- [ ] Run ALL scripts and tests which depend on this code

- [ ] Code adheres to style guidelines

- [ ] Code formatted correctly

- [ ] Extraneous comments removed

- [ ] Difficult parts of the code are commented as to WHY it is the way it is.
  
- [ ] Commented-out code is removed

- [ ] Hardcoded settings and variables (e.g. referencing your home directory) are removed

- [ ] Special cases only for testing are removed (factor code and make a proper test script)

- [ ] Unused code is removed

- [ ] Code checked over with typechecking (`pyright` or `pyrefly`)  enabled to check, use casts and/or pragmas to keep this clean where necessary 

- [ ] Code is sufficiently simple and not overly verbose (split any complex parts, each method will do exactly ONE thing and can fit well within a single screen)

- [ ] Tests have been written for algorithmically complex parts (including making code properly testable by factoring out such parts)

Be ruthless in removing dead code and unused settings; remember, we have git to go back and find old code. 
