- Clarify separation of concerns wrt macro processing (see comment at top of `macro_processing.py`)
- Split out per-macro logic for cell-level (%%) macros
- Reimplement HIDE macros as cell-level (rather than using 'expander' $ syntax)
- can (probably) remove `/kaggle/working` hack from pip install learntools hack.
- would be useful to have macros like `#!WARN!` that would emit a warning during rendering (or even halt rendering in prod mode?). Basically a way to put down a TODO/XXX with teeth.
