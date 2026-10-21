
# TODO list

## Stuff We Can Fix

- [ ] Update comments in all `.tex` files (and fix wrong ones)


## Delegated Task to the Librarian

- [ ] Check if the Glossary formatting is correct


## LaTeX Warnings

- [ ] (babel.sty: Name 'brazil' is deprecated)
  - John: The source code of `abntex2.cls` calls `babel` with the option 'brazil', which in fact causes this warning. I tried substuting it directly in the `abntex2.cls` source code and the warning disappeared. I have oppened an issue so that the error (and the solution) is registered. It is available [here](https://github.com/abntex/abntex2/issues/278).
- [ ] (datatool-base.sty: No 'datatool' support for dialect 'english')
- [ ] (datatool-base.sty: No 'datatool' support for dialect 'brazilian')
  - John: these are caused by abntex and aren't our responsability.
- [ ] (abntex2.cls: `settocpreprocessor` is marked deprecated)
  - John: this seems to be an issue with the class abntex that abntex is yet to fix. This is not our responsibility. The open issue can be found [here](https://github.com/abntex/abntex2/issues/274).
