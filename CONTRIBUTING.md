# Contributing
If for some reason you are contributing to this, here are some handy guidelines:

- As a licensee, your modified design should add a record of *your* changes to the design of the project. These changes should go into [CHANGES.txt](CHANGES.txt), and that is where you will also find a guide to writing about design changes. This is much like a humans.txt, but is intended as part of the License to track design changes and this should follow the Source at all times.

- Any notices, such as license information and source code location should NOT be modified. They are intended to be visible on the design for future reference. For more information on this, please read about the [license.](LICENSE.md)

- Any pull requests should follow the format:
```
# Description

Please make note of any design changes below this paragraph, as well as a *brief* description in the CHANGES.txt file, if you haven't already. This is mandatory!

Any issues this fixes should be listed below with the associated issue number ie: "Fixes #1111,#1112"

## Type of design change
(Please delete any that do not apply.)

- Design change (To PCB/Schematic)
- Firmware/Software change
- Bug fix (there should be an associated issue, use the area above)
- Feature addition (new functionality)
- Breaking change (breaks existing functionality)
- Requires new documentation
- Optimisation (simplification of design, for example)

## Testing

Please show/describe how you tested your changes. Board changes and firmware should be tested prior to being put in a pull request

# Acknowledgements

- [ ] I have read CONTRIBUTING.md and agree to adhere by the guidelines in good faith.
```

# A note on derivative works

If you don't intend on contributing your additions back to the original repo (whose notices should remain intact), you are free to add additional notices indicating a source for your derivative work, and indicating a source for future changes in CHANGES.txt (for example, saying "Changes past DD MM YYYY are available from https://example-url/ .".)
