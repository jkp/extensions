# Jira Changelog

## [Fix persisted values] - 2023-04-18

- Fix an issue where the filter dropdown or the active sprint dropdown wouldn't save the selected dropdown value.

## [Fix priority issue] - 2023-04-13

- Fix an issue where priorities could be unset, causing the loading of issues to fail.

## [Support tables] - 2023-04-12

- Support tables in Jira following Markdown additions in v1.49.3 release

## [Implement Search Suggestions for Filters and Projects] - 2023-04-03

- Add typeahead search for filter dropdowns
- Fix duplicated values in filter dropdowns
- Add typeahead search for project dropdowns

## [Various fixes and improvements] - 2023-03-09

- Make issue types and auto-complete URLs optional
- Add support for auto-completing in the Assignee field
- Add a default value for priorities
- Sort sprints to show active sprints first, then future ones, then closed ones.

## [Initial Version] - 2023-02-27