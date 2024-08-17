# Doozer E2E tests for bugtracker2 project

## Test Cases

The tests are located in `src/test/java/dev/softtest/bugtracker/doozer/scripts/`.

## Command to run

```sh
mvn test -Ddoozer.directory=src/test/java/dev/softtest/bugtracker/doozer/scripts/
```

## Test Plan

- [x] smokeTest
- [x] login
- [x] bugReportListLoading
- [x] bugReportView
- [ ] bugReportEdit
- [x] bugReportCreate
- [ ] bugReportListActions
- [ ] bugReportEditActions
- [x] bugReportViewActions
- [x] bugReportDelete
- [ ] bugReportListSearch
- [ ] bugReportSearch
- [ ] userEdit
- [ ] userList
- [x] userView
