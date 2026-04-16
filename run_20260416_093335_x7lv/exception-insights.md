# Exception Insights Report

Auto-generated insights derived from actual stack traces and RCA evidence.

---

## [C51100001] AssertionError — `video`

**📍 Failure Location:** `tests\ABC_app\conftest.py:522`

**🔍 What it indicates:** A &#x27;AssertionError&#x27; occurred in the &#x27;video&#x27; module during test execution.

**⚠️ Most likely causes:**
- Failed at assertion/statement: `assert self.fd["devices_details_pc_mfe"].verify_video_card_show_up(), "Video Control`
- Failure occurred inside: `def check_and_navigate_to_video_control_page(self):`

**🔧 Typical fix direction:** Review the exact assertion that failed in the 'video' module: 'Could not extract error message'. Trace back the condition that caused it and add appropriate wait strategies, error handling, or test precondition validation.

---

## [C51100002] AssertionError — `video`

**📍 Failure Location:** `tests\ABC_app\conftest.py:522`

**🔍 What it indicates:** In the &#x27;video&#x27; module, a &#x27;AssertionError&#x27; was raised because: Video Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Video Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_video_page(request):`

**🔧 Typical fix direction:** The UI element in the 'video' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51100003] AssertionError — `video`

**📍 Failure Location:** `tests\ABC_app\conftest.py:522`

**🔍 What it indicates:** In the &#x27;video&#x27; module, a &#x27;AssertionError&#x27; was raised because: Video Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Video Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_video_page(request):`

**🔧 Typical fix direction:** The UI element in the 'video' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51100004] AssertionError — `video`

**📍 Failure Location:** `tests\ABC_app\conftest.py:522`

**🔍 What it indicates:** In the &#x27;video&#x27; module, a &#x27;AssertionError&#x27; was raised because: Video Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Video Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_video_page(request):`

**🔧 Typical fix direction:** The UI element in the 'video' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51200001] AssertionError — `keyboard`

**📍 Failure Location:** `tests\ABC_app\conftest.py:540`

**🔍 What it indicates:** In the &#x27;keyboard&#x27; module, a &#x27;AssertionError&#x27; was raised because: Keyboard Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Keyboard Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_keyboard_page(request):`

**🔧 Typical fix direction:** The UI element in the 'keyboard' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51200002] AssertionError — `keyboard`

**📍 Failure Location:** `tests\ABC_app\conftest.py:540`

**🔍 What it indicates:** In the &#x27;keyboard&#x27; module, a &#x27;AssertionError&#x27; was raised because: Keyboard Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Keyboard Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_keyboard_page(request):`

**🔧 Typical fix direction:** The UI element in the 'keyboard' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51200003] AssertionError — `keyboard`

**📍 Failure Location:** `tests\ABC_app\conftest.py:540`

**🔍 What it indicates:** In the &#x27;keyboard&#x27; module, a &#x27;AssertionError&#x27; was raised because: Keyboard Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Keyboard Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_keyboard_page(request):`

**🔧 Typical fix direction:** The UI element in the 'keyboard' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51300001] AssertionError — `battery`

**📍 Failure Location:** `tests\ABC_app\conftest.py:558`

**🔍 What it indicates:** In the &#x27;battery&#x27; module, a &#x27;AssertionError&#x27; was raised because: Battery Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Battery Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_battery_page(request):`

**🔧 Typical fix direction:** The UI element in the 'battery' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51300002] AssertionError — `battery`

**📍 Failure Location:** `tests\ABC_app\conftest.py:558`

**🔍 What it indicates:** In the &#x27;battery&#x27; module, a &#x27;AssertionError&#x27; was raised because: Battery Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Battery Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_battery_page(request):`

**🔧 Typical fix direction:** The UI element in the 'battery' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51300003] AssertionError — `battery`

**📍 Failure Location:** `tests\ABC_app\conftest.py:558`

**🔍 What it indicates:** In the &#x27;battery&#x27; module, a &#x27;AssertionError&#x27; was raised because: Battery Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Battery Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_battery_page(request):`

**🔧 Typical fix direction:** The UI element in the 'battery' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51400001] AssertionError — `network`

**📍 Failure Location:** `tests\ABC_app\conftest.py:575`

**🔍 What it indicates:** In the &#x27;network&#x27; module, a &#x27;AssertionError&#x27; was raised because: Network Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Network Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_network_page(request):`

**🔧 Typical fix direction:** The UI element in the 'network' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51400002] AssertionError — `network`

**📍 Failure Location:** `tests\ABC_app\conftest.py:575`

**🔍 What it indicates:** In the &#x27;network&#x27; module, a &#x27;AssertionError&#x27; was raised because: Network Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Network Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_network_page(request):`

**🔧 Typical fix direction:** The UI element in the 'network' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51500001] AssertionError — `storage`

**📍 Failure Location:** `tests\ABC_app\conftest.py:592`

**🔍 What it indicates:** In the &#x27;storage&#x27; module, a &#x27;AssertionError&#x27; was raised because: Storage Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Storage Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_storage_page(request):`

**🔧 Typical fix direction:** The UI element in the 'storage' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51500002] AssertionError — `storage`

**📍 Failure Location:** `tests\ABC_app\conftest.py:592`

**🔍 What it indicates:** In the &#x27;storage&#x27; module, a &#x27;AssertionError&#x27; was raised because: Storage Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Storage Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_storage_page(request):`

**🔧 Typical fix direction:** The UI element in the 'storage' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51600001] AssertionError — `display`

**📍 Failure Location:** `tests\ABC_app\conftest.py:610`

**🔍 What it indicates:** In the &#x27;display&#x27; module, a &#x27;AssertionError&#x27; was raised because: Display Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Display Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_display_page(request):`

**🔧 Typical fix direction:** The UI element in the 'display' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51600002] AssertionError — `display`

**📍 Failure Location:** `tests\ABC_app\conftest.py:610`

**🔍 What it indicates:** In the &#x27;display&#x27; module, a &#x27;AssertionError&#x27; was raised because: Display Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Display Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_display_page(request):`

**🔧 Typical fix direction:** The UI element in the 'display' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51601001] Failed — `display`

**📍 Failure Location:** `Unknown`

**🔍 What it indicates:** A &#x27;Failed&#x27; occurred in the &#x27;display&#x27; module during test execution.

**⚠️ Most likely causes:**
- Failure occurred inside: `def launch_myABC(self):`

**🔧 Typical fix direction:** Review the exact assertion that failed in the 'display' module: 'Could not extract error message'. Trace back the condition that caused it and add appropriate wait strategies, error handling, or test precondition validation.

---

## [C51601002] Failed — `display`

**📍 Failure Location:** `Unknown`

**🔍 What it indicates:** In the &#x27;display&#x27; module, a &#x27;Failed&#x27; was raised because: myABC app did not launch successfully

**⚠️ Most likely causes:**
- Direct failure reason: myABC app did not launch successfully
- Failed at assertion/statement: `raise exc.with_traceback(exc_tb)`

**🔧 Typical fix direction:** Review the exact assertion that failed in the 'display' module: 'myABC app did not launch successfully'. Trace back the condition that caused it and add appropriate wait strategies, error handling, or test precondition validation.

---

## [C51700001] AssertionError — `camera`

**📍 Failure Location:** `tests\ABC_app\conftest.py:628`

**🔍 What it indicates:** In the &#x27;camera&#x27; module, a &#x27;AssertionError&#x27; was raised because: Camera Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Camera Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_camera_page(request):`

**🔧 Typical fix direction:** The UI element in the 'camera' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51700002] AssertionError — `camera`

**📍 Failure Location:** `tests\ABC_app\conftest.py:628`

**🔍 What it indicates:** In the &#x27;camera&#x27; module, a &#x27;AssertionError&#x27; was raised because: Camera Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Camera Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_camera_page(request):`

**🔧 Typical fix direction:** The UI element in the 'camera' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---

## [C51700003] AssertionError — `camera`

**📍 Failure Location:** `tests\ABC_app\conftest.py:628`

**🔍 What it indicates:** In the &#x27;camera&#x27; module, a &#x27;AssertionError&#x27; was raised because: Camera Control card is still not visible after relaunching app

**⚠️ Most likely causes:**
- Direct failure reason: Camera Control card is still not visible after relaunching app
- Failure occurred inside: `def check_and_navigate_to_camera_page(request):`

**🔧 Typical fix direction:** The UI element in the 'camera' module failed to appear or become interactable. Check: (1) element load timing / add explicit waits, (2) app navigation flow before the element is accessed, (3) whether the feature flag / card is enabled for this test environment.

---
