# Exception Insights Report

Auto-generated insights derived from actual per-test stack traces.

---

## [C51100001] AssertionError — `video`

**📍 Failure Location:** `tests\ABC_app\conftest.py:527`

**🔍 What it indicates:** Test &#x27;C51100001&#x27; failed during the &#x27;check_and_navigate_to_video_page&#x27; setup fixture in the &#x27;video&#x27; module. The &#x27;Video Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Video Control card is still not visible after relaunching app"
- The test stopped at this assertion: `assert self.fd["devices_details_pc_mfe"].verify_video_card_show_up(), "Video Control card is still not visible after relaunching app"`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_video_control_page()`
- 'Video Control' was not rendered or not interactable when the fixture attempted to navigate to the 'video' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_video_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_video_control_page()' in the 'video' flow is directly responsible — trace why it could not confirm the 'Video Control' state. The 'Video Control' failed visibility check even after an app restart. Verify: (1) the 'video' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'video' page loads before the fixture times out.

---

## [C51100002] AssertionError — `video`

**📍 Failure Location:** `tests\ABC_app\conftest.py:522`

**🔍 What it indicates:** Test &#x27;C51100002&#x27; failed during the &#x27;check_and_navigate_to_video_page&#x27; setup fixture in the &#x27;video&#x27; module. The &#x27;Video Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Video Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without video page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_video_control_page()`
- 'Video Control' was not rendered or not interactable when the fixture attempted to navigate to the 'video' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_video_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_video_control_page()' in the 'video' flow is directly responsible — trace why it could not confirm the 'Video Control' state. The 'Video Control' failed visibility check even after an app restart. Verify: (1) the 'video' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'video' page loads before the fixture times out.

---

## [C51100003] AssertionError — `video`

**📍 Failure Location:** `tests\ABC_app\conftest.py:522`

**🔍 What it indicates:** Test &#x27;C51100003&#x27; failed during the &#x27;check_and_navigate_to_video_page&#x27; setup fixture in the &#x27;video' module. The &#x27;Video Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Video Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without video page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_video_control_page()`
- 'Video Control' was not rendered or not interactable when the fixture attempted to navigate to the 'video' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_video_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_video_control_page()' in the 'video' flow is directly responsible — trace why it could not confirm the 'Video Control' state. The 'Video Control' failed visibility check even after an app restart. Verify: (1) the 'video' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'video' page loads before the fixture times out.

---

## [C51100004] AssertionError — `video`

**📍 Failure Location:** `tests\ABC_app\conftest.py:522`

**🔍 What it indicates:** Test &#x27;C51100004&#x27; failed during the &#x27;check_and_navigate_to_video_page&#x27; setup fixture in the &#x27;video' module. The &#x27;Video Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Video Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without video page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_video_control_page()`
- 'Video Control' was not rendered or not interactable when the fixture attempted to navigate to the 'video' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_video_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_video_control_page()' in the 'video' flow is directly responsible — trace why it could not confirm the 'Video Control' state. The 'Video Control' failed visibility check even after an app restart. Verify: (1) the 'video' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'video' page loads before the fixture times out.

---

## [C51200001] AssertionError — `keyboard`

**📍 Failure Location:** `tests\ABC_app\conftest.py:540`

**🔍 What it indicates:** Test &#x27;C51200001&#x27; failed during the &#x27;check_and_navigate_to_keyboard_page&#x27; setup fixture in the &#x27;keyboard' module. The &#x27;Keyboard Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Keyboard Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without keyboard page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_keyboard_control_page()`
- 'Keyboard Control' was not rendered or not interactable when the fixture attempted to navigate to the 'keyboard' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_keyboard_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_keyboard_control_page()' in the 'keyboard' flow is directly responsible — trace why it could not confirm the 'Keyboard Control' state. The 'Keyboard Control' failed visibility check even after an app restart. Verify: (1) the 'keyboard' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'keyboard' page loads before the fixture times out.

---

## [C51200002] AssertionError — `keyboard`

**📍 Failure Location:** `tests\ABC_app\conftest.py:540`

**🔍 What it indicates:** Test &#x27;C51200002&#x27; failed during the &#x27;check_and_navigate_to_keyboard_page&#x27; setup fixture in the &#x27;keyboard' module. The &#x27;Keyboard Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Keyboard Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without keyboard page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_keyboard_control_page()`
- 'Keyboard Control' was not rendered or not interactable when the fixture attempted to navigate to the 'keyboard' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_keyboard_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_keyboard_control_page()' in the 'keyboard' flow is directly responsible — trace why it could not confirm the 'Keyboard Control' state. The 'Keyboard Control' failed visibility check even after an app restart. Verify: (1) the 'keyboard' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'keyboard' page loads before the fixture times out.

---

## [C51200003] AssertionError — `keyboard`

**📍 Failure Location:** `tests\ABC_app\conftest.py:540`

**🔍 What it indicates:** Test &#x27;C51200003&#x27; failed during the &#x27;check_and_navigate_to_keyboard_page&#x27; setup fixture in the &#x27;keyboard' module. The &#x27;Keyboard Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Keyboard Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without keyboard page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_keyboard_control_page()`
- 'Keyboard Control' was not rendered or not interactable when the fixture attempted to navigate to the 'keyboard' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_keyboard_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_keyboard_control_page()' in the 'keyboard' flow is directly responsible — trace why it could not confirm the 'Keyboard Control' state. The 'Keyboard Control' failed visibility check even after an app restart. Verify: (1) the 'keyboard' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'keyboard' page loads before the fixture times out.

---

## [C51300001] AssertionError — `battery`

**📍 Failure Location:** `tests\ABC_app\conftest.py:558`

**🔍 What it indicates:** Test &#x27;C51300001&#x27; failed during the &#x27;check_and_navigate_to_battery_page&#x27; setup fixture in the &#x27;battery' module. The &#x27;Battery Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Battery Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without battery page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_battery_control_page()`
- 'Battery Control' was not rendered or not interactable when the fixture attempted to navigate to the 'battery' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_battery_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_battery_control_page()' in the 'battery' flow is directly responsible — trace why it could not confirm the 'Battery Control' state. The 'Battery Control' failed visibility check even after an app restart. Verify: (1) the 'battery' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'battery' page loads before the fixture times out.

---

## [C51300002] AssertionError — `battery`

**📍 Failure Location:** `tests\ABC_app\conftest.py:558`

**🔍 What it indicates:** Test &#x27;C51300002&#x27; failed during the &#x27;check_and_navigate_to_battery_page&#x27; setup fixture in the &#x27;battery' module. The &#x27;Battery Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Battery Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without battery page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_battery_control_page()`
- 'Battery Control' was not rendered or not interactable when the fixture attempted to navigate to the 'battery' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_battery_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_battery_control_page()' in the 'battery' flow is directly responsible — trace why it could not confirm the 'Battery Control' state. The 'Battery Control' failed visibility check even after an app restart. Verify: (1) the 'battery' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'battery' page loads before the fixture times out.

---

## [C51300003] AssertionError — `battery`

**📍 Failure Location:** `tests\ABC_app\conftest.py:558`

**🔍 What it indicates:** Test &#x27;C51300003&#x27; failed during the &#x27;check_and_navigate_to_battery_page&#x27; setup fixture in the &#x27;battery' module. The &#x27;Battery Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Battery Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without battery page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_battery_control_page()`
- 'Battery Control' was not rendered or not interactable when the fixture attempted to navigate to the 'battery' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_battery_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_battery_control_page()' in the 'battery' flow is directly responsible — trace why it could not confirm the 'Battery Control' state. The 'Battery Control' failed visibility check even after an app restart. Verify: (1) the 'battery' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'battery' page loads before the fixture times out.

---

## [C51400001] AssertionError — `network`

**📍 Failure Location:** `tests\ABC_app\conftest.py:575`

**🔍 What it indicates:** Test &#x27;C51400001&#x27; failed during the &#x27;check_and_navigate_to_network_page&#x27; setup fixture in the &#x27;network' module. The &#x27;Network Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Network Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without network page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_network_control_page()`
- 'Network Control' was not rendered or not interactable when the fixture attempted to navigate to the 'network' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_network_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_network_control_page()' in the 'network' flow is directly responsible — trace why it could not confirm the 'Network Control' state. The 'Network Control' failed visibility check even after an app restart. Verify: (1) the 'network' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'network' page loads before the fixture times out.

---

## [C51400002] AssertionError — `network`

**📍 Failure Location:** `tests\ABC_app\conftest.py:575`

**🔍 What it indicates:** Test &#x27;C51400002&#x27; failed during the &#x27;check_and_navigate_to_network_page&#x27; setup fixture in the &#x27;network' module. The &#x27;Network Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Network Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without network page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_network_control_page()`
- 'Network Control' was not rendered or not interactable when the fixture attempted to navigate to the 'network' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_network_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_network_control_page()' in the 'network' flow is directly responsible — trace why it could not confirm the 'Network Control' state. The 'Network Control' failed visibility check even after an app restart. Verify: (1) the 'network' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'network' page loads before the fixture times out.

---

## [C51500001] AssertionError — `storage`

**📍 Failure Location:** `tests\ABC_app\conftest.py:592`

**🔍 What it indicates:** Test &#x27;C51500001&#x27; failed during the &#x27;check_and_navigate_to_storage_page&#x27; setup fixture in the &#x27;storage' module. The &#x27;Storage Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Storage Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without storage page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_storage_control_page()`
- 'Storage Control' was not rendered or not interactable when the fixture attempted to navigate to the 'storage' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_storage_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_storage_control_page()' in the 'storage' flow is directly responsible — trace why it could not confirm the 'Storage Control' state. The 'Storage Control' failed visibility check even after an app restart. Verify: (1) the 'storage' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'storage' page loads before the fixture times out.

---

## [C51500002] AssertionError — `storage`

**📍 Failure Location:** `tests\ABC_app\conftest.py:592`

**🔍 What it indicates:** Test &#x27;C51500002&#x27; failed during the &#x27;check_and_navigate_to_storage_page&#x27; setup fixture in the &#x27;storage' module. The &#x27;Storage Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Storage Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without storage page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_storage_control_page()`
- 'Storage Control' was not rendered or not interactable when the fixture attempted to navigate to the 'storage' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_storage_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_storage_control_page()' in the 'storage' flow is directly responsible — trace why it could not confirm the 'Storage Control' state. The 'Storage Control' failed visibility check even after an app restart. Verify: (1) the 'storage' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'storage' page loads before the fixture times out.

---

## [C51600001] AssertionError — `display`

**📍 Failure Location:** `tests\ABC_app\conftest.py:610`

**🔍 What it indicates:** Test &#x27;C51600001&#x27; failed during the &#x27;check_and_navigate_to_display_page&#x27; setup fixture in the &#x27;display' module. The &#x27;Display Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Display Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without display page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_display_control_page()`
- 'Display Control' was not rendered or not interactable when the fixture attempted to navigate to the 'display' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_display_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_display_control_page()' in the 'display' flow is directly responsible — trace why it could not confirm the 'Display Control' state. The 'Display Control' failed visibility check even after an app restart. Verify: (1) the 'display' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'display' page loads before the fixture times out.

---

## [C51600002] AssertionError — `display`

**📍 Failure Location:** `tests\ABC_app\conftest.py:610`

**🔍 What it indicates:** Test &#x27;C51600002&#x27; failed during the &#x27;check_and_navigate_to_display_page&#x27; setup fixture in the &#x27;display' module. The &#x27;Display Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Display Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without display page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_display_control_page()`
- 'Display Control' was not rendered or not interactable when the fixture attempted to navigate to the 'display' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_display_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_display_control_page()' in the 'display' flow is directly responsible — trace why it could not confirm the 'Display Control' state. The 'Display Control' failed visibility check even after an app restart. Verify: (1) the 'display' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'display' page loads before the fixture times out.

---

## [C51601001] Failed — `display`

**📍 Failure Location:** `libs\flows\windows\ABCx_rebranding\flow_container.py:465`

**🔍 What it indicates:** Test &#x27;C51601001&#x27; raised a &#x27;Failed&#x27; in the &#x27;display' module. Error: myABC app did not launch successfully.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "myABC app did not launch successfully"
- The test stopped at this assertion: `pytest.fail("myABC app did not launch successfully")`
- 'myABC app' was not rendered or not interactable when the fixture attempted to navigate to the 'display' control page.

**🔧 Fix direction:** The application itself failed to launch before the 'display' tests could run. Check: (1) the app install/registration in the test environment, (2) the shell command used to start the app, (3) whether the device name and device card verification pass after launch.

---

## [C51601002] Failed — `display`

**📍 Failure Location:** ``

**🔍 What it indicates:** Test &#x27;C51601002&#x27; raised a &#x27;Failed&#x27; in the &#x27;display' module. Error: myABC app did not launch successfully.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "myABC app did not launch successfully"
- The test stopped at this assertion: `raise exc.with_traceback(exc_tb)`
- 'myABC app' was not rendered or not interactable when the fixture attempted to navigate to the 'display' control page.

**🔧 Fix direction:** The application itself failed to launch before the 'display' tests could run. Check: (1) the app install/registration in the test environment, (2) the shell command used to start the app, (3) whether the device name and device card verification pass after launch.

---

## [C51700001] AssertionError — `camera`

**📍 Failure Location:** `tests\ABC_app\conftest.py:628`

**🔍 What it indicates:** Test &#x27;C51700001&#x27; failed during the &#x27;check_and_navigate_to_camera_page&#x27; setup fixture in the &#x27;camera' module. The &#x27;Camera Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Camera Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without camera page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_camera_control_page()`
- 'Camera Control' was not rendered or not interactable when the fixture attempted to navigate to the 'camera' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_camera_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_camera_control_page()' in the 'camera' flow is directly responsible — trace why it could not confirm the 'Camera Control' state. The 'Camera Control' failed visibility check even after an app restart. Verify: (1) the 'camera' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'camera' page loads before the fixture times out.

---

## [C51700002] AssertionError — `camera`

**📍 Failure Location:** `tests\ABC_app\conftest.py:628`

**🔍 What it indicates:** Test &#x27;C51700002&#x27; failed during the &#x27;check_and_navigate_to_camera_page&#x27; setup fixture in the &#x27;camera' module. The &#x27;Camera Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Camera Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without camera page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_camera_control_page()`
- 'Camera Control' was not rendered or not interactable when the fixture attempted to navigate to the 'camera' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_camera_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_camera_control_page()' in the 'camera' flow is directly responsible — trace why it could not confirm the 'Camera Control' state. The 'Camera Control' failed visibility check even after an app restart. Verify: (1) the 'camera' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'camera' page loads before the fixture times out.

---

## [C51700003] AssertionError — `camera`

**📍 Failure Location:** `tests\ABC_app\conftest.py:628`

**🔍 What it indicates:** Test &#x27;C51700003&#x27; failed during the &#x27;check_and_navigate_to_camera_page&#x27; setup fixture in the &#x27;camera' module. The &#x27;Camera Control&#x27; could not be confirmed as visible or accessible before the test body executed.

**⚠️ Most likely causes:**
- Exact failure reason from stack trace: "Camera Control card is still not visible after relaunching app"
- The test stopped at this assertion: `pytest.fail(f"Cannot proceed without camera page access: {e}")`
- The internal flow method that triggered the failure: `fc.check_and_navigate_to_camera_control_page()`
- 'Camera Control' was not rendered or not interactable when the fixture attempted to navigate to the 'camera' control page.

**🔧 Fix direction:** Start by investigating the 'check_and_navigate_to_camera_page' fixture which is the entry point where this 'AssertionError' was raised. The method 'fc.check_and_navigate_to_camera_control_page()' in the 'camera' flow is directly responsible — trace why it could not confirm the 'Camera Control' state. The 'Camera Control' failed visibility check even after an app restart. Verify: (1) the 'camera' feature card is enabled in this test environment, (2) the app restarts cleanly and the 'camera' page loads before the fixture times out.

---
