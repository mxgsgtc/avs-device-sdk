add_subdirectory("Attachment")
set(INCLUDE_PATH
    "${AVSCommon_INCLUDE_DIRS}"
    "${AVSCommon_SOURCE_DIR}/AVS/test"
    "${MetricRecorder_INCLUDE_DIRS}")
discover_unit_tests("${INCLUDE_PATH}" "AVSCommon;AttachmentCommonTestLib;SDKInterfacesTests")
