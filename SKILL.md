---
name: xxd-panel-221
description: "XXD Panel 221｜New-Chinese Spot-Colour Print: condenses a photo into a small, seal-like New-Chinese print — silhouettes, large flat colour areas, white carved lines and positive-negative shapes with slightly rough edges, ink dropouts, slight misregistration and paper fibre, so it looks printed by woodcut, screen or stencil rather than painted — in two to four low-to-mid saturation spot colours taken from the photo (one structural colour, one focal colour, black or a dark tone for text, cream paper for space), set in wide Eastern-style white space with a few slim, modern book-typography words. Outputs PNG top-bottom or left-right comparisons, design-only images, or phone/tablet/desktop/watch wallpapers, from one photo or a folder. Use when the user invokes xxd-panel-221 or asks for New-Chinese, woodcut, risograph or spot-colour print illustration with Eastern white space from a photo."
---

# XXD Panel 221

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

## Panel-specific overlay

The transformed design is a New-Chinese spot-colour woodcut and silkscreen: silhouettes, large colour planes, cut lines and positive/negative shapes, not a literal redraw of the photograph. Keep a small stamp-like subject and abundant Eastern whitespace. Take two to four low-to-medium saturation inks from the source: one structural colour, one accent, dark for type and a few contours, paper white for the field. Type stays sparse, thin and editorial. It is not a filled scene, a realistic illustration, a cartoon, 3D, a commercial poster or a template.

These overlay rules add to `references/soldier-runtime.md`. They never replace the source brief or the family runtime contract.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-221/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-221-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks
