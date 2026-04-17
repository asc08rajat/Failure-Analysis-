# Exception Insights Report

Auto-generated insights derived from actual stack traces and RCA evidence.

---

## [C51250219] AssertionError — `battery`

**Failure Location:** `packages\_pytest\capture.py:900`

**What it indicates:** A `AssertionError` occurred in the 'battery' module during test execution.

**Most likely causes:**
- Failed at: `lambda: runtest_hook(item=item, **kwds), when=when, reraise=reraise`
- Occurred inside: `def _multicall(`

**Typical fix direction:** An assertion failed in 'battery'. Reason: Could not extract error message. Review the expected vs actual values, confirm test preconditions, and check whether recent code changes altered the behavior under test.

<details>
<summary>Stack trace excerpt</summary>

```
                        res = hook_impl.function(*args)
                        if res is not None:
                            results.append(res)
                            if firstresult:  # halt further impl calls
                                break
            except BaseException as exc:
                exception = exc
        finally:
            if firstresult:  # first result hooks return a single value
                result = results[0] if results else None
            else:
                result = results
            for teardown in reversed teardowns):
                try:
                    if excep...<truncated>
```

</details>

---

## [C51250220] AttributeError — `battery`

**Failure Location:** `packages\_pytest\capture.py:900`

**What it indicates:** A `AttributeError` occurred in the 'battery' module during test execution.

**Most likely causes:**
- Failed at: `lambda: runtest_hook(item=item, **kwds), when=when, reraise=reraise`
- Occurred inside: `def _multicall(`

**Typical fix direction:** An object in 'battery' does not have the attribute 'the referenced attribute'. This typically means an API/interface change, a None return where an object was expected, or a wrong import. Verify object types and the API contract.

<details>
<summary>Stack trace excerpt</summary>

```
                        if res is not None:
                            results.append(res)
                            if firstresult:  # halt further impl calls
                                break
            except BaseException as exc:
                exception = exc
        finally:
            if firstresult:  # first result hooks return a single value
                result = results[0] if results else None
            else:
                result = results
            for teardown in reversed teardowns):
                try:
                    if exception is not None:
                      ...<truncated>
```

</details>

---

## [C51250227] FixtureLookupError — `battery`

**Failure Location:** `packages\pluggy\_callers.py:121`

**What it indicates:** A `FixtureLookupError` occurred in the 'battery' module during test execution.

**Most likely causes:**
- Failed at: `lambda: runtest_hook(item=item, **kwds), when=when, reraise=reraise`
- Occurred inside: `def pytest_runtest_setup(item: Item) -> None:`
- A required pytest fixture is not registered in the current scope. Check conftest.py and plugin dependencies.

**Typical fix direction:** The test in 'battery' requires 'the referenced fixture' which is not registered. Check that the fixture is defined in the correct conftest.py scope, the plugin providing it is installed, and it is spelled correctly.

<details>
<summary>Stack trace excerpt</summary>

```
                            function_gen = cast(Generator[None, object, object], res)
                            next(function_gen)  # first yield
                            teardowns.append(function_gen)
                        except StopIteration:
                            _raise_wrapfail(function_gen, "did not yield")
                    else:
>                       res = hook_impl.function(*args)
                              ^^^^^^^^^^^^^^^^^^^^^^^^^
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\pluggy\_callers.py:121: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
item = <Function test_03_schedule_battery_charging_default_threshold_value>
    def pytest_runtest_setup(item: Item) -> None:
        _update_current_test_var(item, "setup")
>       item.session._setupstate.setup(item)
C:...<truncated>
```

</details>

---

## [C51250228] FixtureLookupError — `battery`

**Failure Location:** `packages\pluggy\_callers.py:121`

**What it indicates:** A `FixtureLookupError` occurred in the 'battery' module during test execution.

**Most likely causes:**
- Failed at: `lambda: runtest_hook(item=item, **kwds), when=when, reraise=reraise`
- Occurred inside: `def pytest_runtest_setup(item: Item) -> None:`
- A required pytest fixture is not registered in the current scope. Check conftest.py and plugin dependencies.

**Typical fix direction:** The test in 'battery' requires 'the referenced fixture' which is not registered. Check that the fixture is defined in the correct conftest.py scope, the plugin providing it is installed, and it is spelled correctly.

<details>
<summary>Stack trace excerpt</summary>

```
                            function_gen = cast(Generator[None, object, object], res)
                            next(function_gen)  # first yield
                            teardowns.append(function_gen)
                        except StopIteration:
                            _raise_wrapfail(function_gen, "did not yield")
                    else:
>                       res = hook_impl.function(*args)
                              ^^^^^^^^^^^^^^^^^^^^^^^^^
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\pluggy\_callers.py:121: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
item = <Function test_04_schedule_battery_charging_reset_schedule_button>
    def pytest_runtest_setup(item: Item) -> None:
        _update_current_test_var(item, "setup")
>       item.session._setupstate.setup(item)
C:\Users\exec\AppDat...<truncated>
```

</details>

---

## [C51250230] FixtureLookupError — `battery`

**Failure Location:** `packages\_pytest\runner.py:164`

**What it indicates:** A `FixtureLookupError` occurred in the 'battery' module during test execution.

**Most likely causes:**
- Failed at: `lambda: runtest_hook(item=item, **kwds), when=when, reraise=reraise`
- Occurred inside: `def pytest_runtest_setup(item: Item) -> None:`
- A required pytest fixture is not registered in the current scope. Check conftest.py and plugin dependencies.

**Typical fix direction:** The test in 'battery' requires 'the referenced fixture' which is not registered. Check that the fixture is defined in the correct conftest.py scope, the plugin providing it is installed, and it is spelled correctly.

<details>
<summary>Stack trace excerpt</summary>

```
                            next(function_gen)  # first yield
                            teardowns.append(function_gen)
                        except StopIteration:
                            _raise_wrapfail(function_gen, "did not yield")
                    else:
>                       res = hook_impl.function(*args)
                              ^^^^^^^^^^^^^^^^^^^^^^^^^
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\pluggy\_callers.py:121: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
item = <Function test_05_schedule_battery_charging_renavigate>
    def pytest_runtest_setup(item: Item) -> None:
        _update_current_test_var(item, "setup")
>       item.session._setupstate.setup(item)
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\_pytest\runner.py:164: 
_ _ _ _ _ _ _ _ _ _ _ _...<truncated>
```

</details>

---

## [C51250224] FixtureLookupError — `battery`

**Failure Location:** `packages\_pytest\runner.py:164`

**What it indicates:** A `FixtureLookupError` occurred in the 'battery' module during test execution.

**Most likely causes:**
- Failed at: `lambda: runtest_hook(item=item, **kwds), when=when, reraise=reraise`
- Occurred inside: `def pytest_runtest_setup(item: Item) -> None:`
- A required pytest fixture is not registered in the current scope. Check conftest.py and plugin dependencies.

**Typical fix direction:** The test in 'battery' requires 'the referenced fixture' which is not registered. Check that the fixture is defined in the correct conftest.py scope, the plugin providing it is installed, and it is spelled correctly.

<details>
<summary>Stack trace excerpt</summary>

```
                            next(function_gen)  # first yield
                            teardowns.append(function_gen)
                        except StopIteration:
                            _raise_wrapfail(function_gen, "did not yield")
                    else:
>                       res = hook_impl.function(*args)
                              ^^^^^^^^^^^^^^^^^^^^^^^^^
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\pluggy\_callers.py:121: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
item = <Function test_06_charging_options_in_battery_manager>
    def pytest_runtest_setup(item: Item) -> None:
        _update_current_test_var(item, "setup")
>       item.session._setupstate.setup(item)
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\_pytest\runner.py:164: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ ...<truncated>
```

</details>

---

## [C43080275] FixtureLookupError — `battery`

**Failure Location:** `packages\_pytest\runner.py:164`

**What it indicates:** A `FixtureLookupError` occurred in the 'battery' module during test execution.

**Most likely causes:**
- Failed at: `lambda: runtest_hook(item=item, **kwds), when=when, reraise=reraise`
- Occurred inside: `def pytest_runtest_setup(item: Item) -> None:`
- A required pytest fixture is not registered in the current scope. Check conftest.py and plugin dependencies.

**Typical fix direction:** The test in 'battery' requires 'the referenced fixture' which is not registered. Check that the fixture is defined in the correct conftest.py scope, the plugin providing it is installed, and it is spelled correctly.

<details>
<summary>Stack trace excerpt</summary>

```
                        except StopIteration:
                            _raise_wrapfail(function_gen, "did not yield")
                    else:
>                       res = hook_impl.function(*args)
                              ^^^^^^^^^^^^^^^^^^^^^^^^^
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\pluggy\_callers.py:121: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
item = <Function test_07_battery_manager_ui>
    def pytest_runtest_setup(item: Item) -> None:
        _update_current_test_var(item, "setup")
>       item.session._setupstate.setup(item)
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\_pytest\runner.py:164: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
self = <_pytest.runner.SetupState object at 0x000002727E5C61B0>
item = <Function test_07_batt...<truncated>
```

</details>

---

## [C51250225] FixtureLookupError — `battery`

**Failure Location:** `packages\_pytest\runner.py:164`

**What it indicates:** A `FixtureLookupError` occurred in the 'battery' module during test execution.

**Most likely causes:**
- Failed at: `lambda: runtest_hook(item=item, **kwds), when=when, reraise=reraise`
- Occurred inside: `def pytest_runtest_setup(item: Item) -> None:`
- A required pytest fixture is not registered in the current scope. Check conftest.py and plugin dependencies.

**Typical fix direction:** The test in 'battery' requires 'the referenced fixture' which is not registered. Check that the fixture is defined in the correct conftest.py scope, the plugin providing it is installed, and it is spelled correctly.

<details>
<summary>Stack trace excerpt</summary>

```
                            teardowns.append(function_gen)
                        except StopIteration:
                            _raise_wrapfail(function_gen, "did not yield")
                    else:
>                       res = hook_impl.function(*args)
                              ^^^^^^^^^^^^^^^^^^^^^^^^^
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\pluggy\_callers.py:121: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
item = <Function test_08_schedule_battery_charging>
    def pytest_runtest_setup(item: Item) -> None:
        _update_current_test_var(item, "setup")
>       item.session._setupstate.setup(item)
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\_pytest\runner.py:164: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
self = <_pytest.runner.SetupState obje...<truncated>
```

</details>

---

## [C51250223] FixtureLookupError — `battery`

**Failure Location:** `packages\_pytest\runner.py:164`

**What it indicates:** A `FixtureLookupError` occurred in the 'battery' module during test execution.

**Most likely causes:**
- Failed at: `lambda: runtest_hook(item=item, **kwds), when=when, reraise=reraise`
- Occurred inside: `def pytest_runtest_setup(item: Item) -> None:`
- A required pytest fixture is not registered in the current scope. Check conftest.py and plugin dependencies.

**Typical fix direction:** The test in 'battery' requires 'the referenced fixture' which is not registered. Check that the fixture is defined in the correct conftest.py scope, the plugin providing it is installed, and it is spelled correctly.

<details>
<summary>Stack trace excerpt</summary>

```
                            next(function_gen)  # first yield
                            teardowns.append(function_gen)
                        except StopIteration:
                            _raise_wrapfail(function_gen, "did not yield")
                    else:
>                       res = hook_impl.function(*args)
                              ^^^^^^^^^^^^^^^^^^^^^^^^^
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\pluggy\_callers.py:121: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
item = <Function test_09_hover_over_tooltips_in_battery_manager>
    def pytest_runtest_setup(item: Item) -> None:
        _update_current_test_var(item, "setup")
>       item.session._setupstate.setup(item)
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\_pytest\runner.py:164: 
_ _ _...<truncated>
```

</details>

---

## [C51250254] FixtureLookupError — `battery`

**Failure Location:** `packages\_pytest\runner.py:164`

**What it indicates:** A `FixtureLookupError` occurred in the 'battery' module during test execution.

**Most likely causes:**
- Failed at: `lambda: runtest_hook(item=item, **kwds), when=when, reraise=reraise`
- Occurred inside: `def pytest_runtest_setup(item: Item) -> None:`
- A required pytest fixture is not registered in the current scope. Check conftest.py and plugin dependencies.

**Typical fix direction:** The test in 'battery' requires 'the referenced fixture' which is not registered. Check that the fixture is defined in the correct conftest.py scope, the plugin providing it is installed, and it is spelled correctly.

<details>
<summary>Stack trace excerpt</summary>

```
                            next(function_gen)  # first yield
                            teardowns.append(function_gen)
                        except StopIteration:
                            _raise_wrapfail(function_gen, "did not yield")
                    else:
>                       res = hook_impl.function(*args)
                              ^^^^^^^^^^^^^^^^^^^^^^^^^
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\pluggy\_callers.py:121: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
item = <Function test_10_deeplink_support_for_battery_manager>
    def pytest_runtest_setup(item: Item) -> None:
        _update_current_test_var(item, "setup")
>       item.session._setupstate.setup(item)
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\_pytest\runner.py:164: 
_ _ _ _ _ _ _ _ _ _ _ _...<truncated>
```

</details>

---

## [C51250235] FixtureLookupError — `battery`

**Failure Location:** `packages\_pytest\runner.py:164`

**What it indicates:** A `FixtureLookupError` occurred in the 'battery' module during test execution.

**Most likely causes:**
- Failed at: `lambda: runtest_hook(item=item, **kwds), when=when, reraise=reraise`
- Occurred inside: `def pytest_runtest_setup(item: Item) -> None:`
- A required pytest fixture is not registered in the current scope. Check conftest.py and plugin dependencies.

**Typical fix direction:** The test in 'battery' requires 'the referenced fixture' which is not registered. Check that the fixture is defined in the correct conftest.py scope, the plugin providing it is installed, and it is spelled correctly.

<details>
<summary>Stack trace excerpt</summary>

```
                        except StopIteration:
                            _raise_wrapfail(function_gen, "did not yield")
                    else:
>                       res = hook_impl.function(*args)
                              ^^^^^^^^^^^^^^^^^^^^^^^^^
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\pluggy\_callers.py:121: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
item = <Function test_01_ac_power_thresholds>
    def pytest_runtest_setup(item: Item) -> None:
        _update_current_test_var(item, "setup")
>       item.session._setupstate.setup(item)
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\_pytest\runner.py:164: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
self = <_pytest.runner.SetupState object at 0x000002727E5C61B0>
item = <Function tes...<truncated>
```

</details>

---

## [C51250249] FixtureLookupError — `battery`

**Failure Location:** `packages\_pytest\runner.py:16`

**What it indicates:** A `FixtureLookupError` occurred in the 'battery' module during test execution.

**Most likely causes:**
- Failed at: `lambda: runtest_hook(item=item, **kwds), when=when, reraise=reraise`
- Occurred inside: `def pytest_runtest_setup(item: Item) -> None:`
- A required pytest fixture is not registered in the current scope. Check conftest.py and plugin dependencies.

**Typical fix direction:** The test in 'battery' requires 'the referenced fixture' which is not registered. Check that the fixture is defined in the correct conftest.py scope, the plugin providing it is installed, and it is spelled correctly.

<details>
<summary>Stack trace excerpt</summary>

```
                            function_gen = cast(Generator[None, object, object], res)
                            next(function_gen)  # first yield
                            teardowns.append(function_gen)
                        except StopIteration:
                            _raise_wrapfail(function_gen, "did not yield")
                    else:
>                       res = hook_impl.function(*args)
                              ^^^^^^^^^^^^^^^^^^^^^^^^^
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\pluggy\_callers.py:121: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
item = <Function test_02_verify_max_capacity_new_capacity_values>
    def pytest_runtest_setup(item: Item) -> None:
        _update_current_test_var(item, "setup")
>       item.session._setupstate.setup(item)
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\_pytest\runner.py:16...<truncated>
```

</details>

---

## [C51250252] FixtureLookupError — `battery`

**Failure Location:** `packages\pluggy\_callers.py:121`

**What it indicates:** A `FixtureLookupError` occurred in the 'battery' module during test execution.

**Most likely causes:**
- Failed at: `lambda: runtest_hook(item=item, **kwds), when=when, reraise=reraise`
- Occurred inside: `def pytest_runtest_setup(item: Item) -> None:`
- A required pytest fixture is not registered in the current scope. Check conftest.py and plugin dependencies.

**Typical fix direction:** The test in 'battery' requires 'the referenced fixture' which is not registered. Check that the fixture is defined in the correct conftest.py scope, the plugin providing it is installed, and it is spelled correctly.

<details>
<summary>Stack trace excerpt</summary>

```
                            function_gen = cast(Generator[None, object, object], res)
                            next(function_gen)  # first yield
                            teardowns.append(function_gen)
                        except StopIteration:
                            _raise_wrapfail(function_gen, "did not yield")
                    else:
>                       res = hook_impl.function(*args)
                              ^^^^^^^^^^^^^^^^^^^^^^^^^
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\pluggy\_callers.py:121: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
item = <Function test_03_fcc_max_capacity_value_when_mbh_selected>
    def pytest_runtest_setup(item: Item) -> None:
        _update_current_test_var(item, "setup")
>       item.session._setupstate.setup(item)
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\_pytest\run...<truncated>
```

</details>

---

## [C53231326] FixtureLookupError — `battery`

**Failure Location:** `packages\pluggy\_callers.py:121`

**What it indicates:** A `FixtureLookupError` occurred in the 'battery' module during test execution.

**Most likely causes:**
- Failed at: `lambda: runtest_hook(item=item, **kwds), when=when, reraise=reraise`
- Occurred inside: `def pytest_runtest_setup(item: Item) -> None:`
- A required pytest fixture is not registered in the current scope. Check conftest.py and plugin dependencies.

**Typical fix direction:** The test in 'battery' requires 'the referenced fixture' which is not registered. Check that the fixture is defined in the correct conftest.py scope, the plugin providing it is installed, and it is spelled correctly.

<details>
<summary>Stack trace excerpt</summary>

```
                        try:
                            res = hook_impl.function(*args)
                            function_gen = cast(Generator[None, object, object], res)
                            next(function_gen)  # first yield
                            teardowns.append(function_gen)
                        except StopIteration:
                            _raise_wrapfail(function_gen, "did not yield")
                    else:
>                       res = hook_impl.function(*args)
                              ^^^^^^^^^^^^^^^^^^^^^^^^^
C:\Users\exec\AppData\Local\Programs\Python\Python312\Lib\site-packages\pluggy\_callers.py:121: 
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
item = <Function test_05_battery_commercial_contextual_config_for_battery_manager>
    def pytest_runtest_setup(item: Item) -> None:
        _update_current_test_var(ite...<truncated>
```

</details>

---
