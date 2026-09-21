Fix the syntax error in `/SWE-agent__test-repo/src/testpkg/missing_colon.py`.

The function definition on line 4 is missing a colon:

```python
def division(a: float, b: float) -> float
```

Change it to:

```python
def division(a: float, b: float) -> float:
```

Do not modify any test files. Run `python -m py_compile src/testpkg/missing_colon.py` to verify the fix, then submit.
