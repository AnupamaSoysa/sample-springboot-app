## Project rules
- Use Java 17.
- Always run: mvn -B test before finishing.
- Keep changes minimal and well explained.

## Cross-repo rule
This repo depends on ../deps/sample-common-lib.
If a change requires updates to the dependency library:
1) Make changes in deps/sample-common-lib
2) Create a branch in that repo: claude/issue-<num>-common-lib
3) Commit + push and open a PR in sample-common-lib
4) Then update this repo if needed and open a PR here too.
