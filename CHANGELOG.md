# Changelog

## [1.188.0] - 2019-06-16
### Added
- src/expandableCalendar/AgendaList.js - invoking used SectionList's events.
### Removed
- example/src/screens/ExpandableCalendar.js - removing unnecessary 'data' prop sent to AgendaList.


## [1.189.0] - 2019-06-24
### Bug Fix
- CalendarProvider - fix for 'date' prop update.

## [1.190.0] - 2019-06-24
### Added
- CalendarContext - 'disabledOpacity' prop to control the opacity of the today button when it is disabled (default is now undefined, meaning no opacity).
- src/style.js - adding support for today button's font size, weight, family.
### Bug Fix
- CalendarContext - fix for today button's width to allow button to take content's width.

## [1.191.0] - 2019-06-24
### Bug Fix
- ExpandableCalendar - limit calendar min height to closed height.

## [1.192.0] - 2019-06-25
### Fix
- CalendarProvider - Fix for warning on Image 'source' type.
- ExpandableCalendar - Fix shadow/elevation style.

## [1.193.0] - 2019-06-26
### Bug Fix
- ExpandableCalendar - fix for week paddings. Changing knob container height and weekDays style.
- CalendarList/item - limit headerStyle to horizontal only.

## [1.194.0] - 2019-06-30
### Added
- CalendarProvider - 'onMonthChange' event returning date object and updateSource.

## [1.195.0] - 2019-07-04
### Change
- Components' props comment format.

## [1.196.0] - 2019-07-04
### Added
- CalendarList - passing 'testID' to static CalendarHeader.

## [1.197.0] - 2019-07-14
### Added
- asCalendarConsumer - hoist non-react statics.

## [1.198.0] - 2019-07-14
### Fix
- ExpandableCalendar - fix example screen.

## [1.199.0] - 2019-07-18
### Changed
- CalendarHeader - editing 'testID' for static CalendarHeader.

## [1.200.0] - 2019-07-18
### Added
- ExpandableCalendar - adding testID for knob.

## [1.201.0] - 2019-07-25
### Change
- eslint - updating to version 6.1.0.
- lodash - importing library instead of sub-libraries.

## [1.202.0] - 2019-07-25
### Added
- CalendarHeader - adding 'firstDay' (PR #826), 'monthFormat' (PR #787) and 'weekNumbers' to shouldComponentUpdate.
- Agenda - adding support for weekdays name's 'fontSize', 'fontFamily' and 'fontWeight' (PR #711).
- ReservationList - adding support for Day number's 'fontFamily', and to Day text's 'fontFamily' and 'fontWeight' (PR #711).
