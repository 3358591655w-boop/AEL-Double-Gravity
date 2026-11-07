# Test report — AEL V2.6.50

- `python -m py_compile app.py pro_gravity_live.py`: PASS
- `python -m unittest discover -s tests -v`: 23 tests PASS
- Added regression test confirming objective R computes when the real-yield series is unavailable, using the algebraically simplified formula.
- Live remote-source download and Railway production runtime: NOT VERIFIED in this environment.
