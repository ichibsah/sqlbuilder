SqlBuilder 3.0.0 Release
========================
- SqlBuilder now requires a Java 8+ runtime. As part of this update, all dependencies have been updated to their latest versions
- The separate common-util dependency has been removed. The few classes which were utilized from that dependency are now included in this project directly
- Add convenience methods to convert Java 8 Temporal types into jdbc date/time escape syntax