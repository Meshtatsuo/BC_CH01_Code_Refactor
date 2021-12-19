# Challenge Assignment #1

## Overview

This markdown lays out my observations on the current codebase, my plans to fix them, and my checklist of problems to be solved.

## Observations and Solutions

| Observations                                                                                                                                                                               | Solutions                                                                                                |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------- |
| The code is sloppy and hard to read, I find myself jumping around the CSS to find things.                                                                                                  | Reorganize code into a more logical hiearchy, such as "universal stylings->classes->IDs"                 |
| I see lots of `<Div>` tags that can easily be replaced with `<secton>` tags.                                                                                                               | Replace `<div>` tags with more appropriate elements                                                      |
| Many `<Div>` tags are being assigned classes that are very specific to that single `<Div>`, instead of a more general purpose class. Will have to refactor the classes and IDs being used. | Refactor the classes to be more general purpose, assign new IDs to elements that need specific stylings. |

## Tasks

### index.html

- [ ] Ensure all newly created classes and IDs are assigned to their appropriate elements.
- [ ] Assess use of `<div>` element. Replace with more appropriate tag if neccessary
- [ ] Ensure new CSS file is properly linked
- [ ] Check that all images have alt text where appropriate

### style.css

- [ ] Reorganize code into a more logical and readable layout.
- [ ] Analyze CSS to find repeat stylings and create new general purpose class to cover them.
- [ ] Determine a better approach to handling specific font stylings scattered throughout CSS.
- [ ] Analyze stylings for specific sections, consolidate any duplicates into a general purpose class, and create descriptive IDs for the more specific styling needs.
- [ ] Ensure newly created styling sheet properly recreates the same webpage look and layout of the original styling sheet.
