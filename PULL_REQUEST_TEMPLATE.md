# Pull Request Checklist

Please check to indicate:
(Keep all code up to standard where possible, not just new code)

- [ ] Files are appropriately named in `snake_case.py` format
- [ ] Included any new files you have created (checkout fresh repository and make sure it runs)
##
- [ ] Run tests
- [ ] Run lint - (use # noqa on legacy code which can't be improved for now)
- [ ] Run typechecker (for python projects) - fix up any external code use with `typing.cast`  and/or `# type : ignore` where applicable
##
- [ ] Code adheres to style guidelines
- [ ] Complex parts of the code are commented
- [ ] Code is refactored to a high standard (DRY, SRP, KISS etc.)
##  
- [ ] Unused code, commented code and excessive comments are removed (document high level functions and those with high complexity only)
- [ ] Tests have been written for algorithmically complex parts (including making code properly testable by factoring out such parts)


Be ruthless in removing dead code and unused settings; remember, we have git to go back and find old code. 
