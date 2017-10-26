# gwt-2.5.1-patches

Forked version of GWT 2.5.1.
One of projects I work on is locked on 2.5.1 version. I've decided to selectively fix some bugs introduced by newer browsers.

1. Ensure int values for pixels (newer browsers return floating point coordinates, sizes)
2. https://github.com/gwtproject/gwt/issues/9542 (GWT getAbsoluteLeft/Top incorrect in Chrome 61 )

Changes are merget info 2.5.1-patches branch.

