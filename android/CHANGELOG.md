# Change Log

<!--
Template:


## Version X.Y.Z (dd.mm.yyyy)

* New: `Foo` was added.
* Fix: Dont divide by zero.

-->

## Version 1.4.1 (08.08.2018)

* Fix: Correctly use `activityExitAnimation` from `ViewStoryConfiguration`

## Version 1.4.0 (01.08.2018)

* New: `Gobi.showStory(String, Activity, ViewStoryConfiguration)` method was added. The configuration object can set `useRewind`, as well as `activityEnterAnimation` and `activityExitAnimation`.

## Version 1.3.0 (26.07.2018)

* New: `Gobi.showStory(String, android.app.Activity, boolean)` and `Gobi.showStory(String, android.support.v4.app.FragmentManager, boolean)` were added. The last boolean is `useRewind`, to watch a story from the beginning.
* New: `no.gobiapp.gobi.sdk.data.StoryData` got a new method: `getTotalAvailableContentCount()`

## Version 1.2.0 (18.07.2018)

* New: `Gobi.showStory(String, android.app.Activity)` was added.

## Version 1.1.0 (16.07.2018)

* New: More detailed exception message when user generation fails.

## Version 1.0.0 (5.07.2018)

Initial release
