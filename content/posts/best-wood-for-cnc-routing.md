---
title: "Best Wood for CNC Routing: What Cuts Clean and What Destroys Bits"
date: 2026-06-23
draft: false
tags: ["cnc router", "wood", "materials", "beginners"]
categories: ["Guides"]
description: "A practical guide to choosing wood species for CNC routing. Which woods machine cleanly, which ones tear out, and how grain direction affects your results."
---

The wood you put on your CNC bed matters as much as the machine cutting it. A €2,000 router will produce ugly results in the wrong wood with the wrong settings, and a €400 hobby machine can produce beautiful work in a forgiving species. Understanding which woods suit CNC work (and why) saves you wasted material, broken bits, and frustration.

This guide comes from consensus across r/hobbycnc, CNCZone forums, and woodworking YouTube channels where people share real cutting results rather than theoretical recommendations.

## Why CNC and Hand Woodworking Prefer Different Species

When you cut wood with a hand tool or table saw, you can adjust pressure, angle, and speed in real time. You feel the resistance change and compensate. A CNC router runs a predetermined toolpath at fixed parameters. It can't feel when the grain direction changes or when it hits a knot.

This means CNC routing punishes wood characteristics that hand woodworkers manage instinctively. Interlocking grain, high resin content, internal tension, and extreme hardness all cause problems when a spinning bit meets them at 18,000 RPM with no human feedback loop.

The ideal CNC wood is: consistent in density (no dramatic difference between early and late growth rings), fine and straight-grained, moderately hard (soft enough to cut easily but hard enough not to tear), low in resin, and stable (doesn't move or warp dramatically with humidity changes).

## The Best Woods for CNC (Community Consensus)

**MDF (Medium Density Fiberboard)** is where most people start, and for good reason. It's perfectly consistent in all directions because it has no grain. It cuts cleanly at almost any speed/feed combination. It holds fine detail well. The downsides are obvious: it's heavy, it doesn't look like "real wood," and it produces hazardous dust (wear a respirator, always). For prototyping, jigs, and painted projects, MDF is the easiest material to machine on any CNC router.

**Baltic Birch Plywood** is the most popular "real wood" choice for CNC projects. The thin, consistent layers mean you get predictable cutting behavior regardless of direction. The face veneer is fine-grained birch that machines cleanly. Edge quality is good enough to leave exposed (unlike construction plywood). It comes in precise metric thicknesses (3mm, 6mm, 12mm, 18mm) which makes CAD modeling straightforward. Available almost everywhere for €40-80 per 1525x1525mm sheet.

**Hard Maple** (Acer saccharum) is the premium choice for solid wood CNC work. It's hard enough to hold crisp detail, fine-grained enough to machine without tearout in most directions, and it finishes beautifully. The hardness means you need sharp bits and appropriate feeds (too slow and you burn; too fast and you chip), but once dialed in, the results are exceptional. Most high-end cutting boards, signs, and furniture components you see CNC'd from solid wood are maple.

**Cherry** (Prunus serotina) machines almost as well as maple but is slightly softer, making it more forgiving for beginners. It cuts clean across the grain, rarely chips, and the natural color darkens beautifully with UV exposure. The downside is cost and availability outside North America.

**Walnut** (Juglans nigra) is popular for decorative CNC work because of its rich color. It machines well in most operations but can be stringy in end-grain cuts. Slightly more prone to fuzzing on pocket floors than maple or cherry. Sharp, fresh bits solve most walnut problems.

**Poplar** is the budget-friendly option when you want solid wood results without paying maple prices. It cuts very easily (it's quite soft for a hardwood), holds detail reasonably well, and takes paint excellently. It doesn't look great with a clear finish (the grain is bland and it has green/purple streaks), so it's best for painted projects.

## Woods That Cause Problems

**Oak** (Red and White) is a common choice because it's readily available and looks impressive. On a CNC, it's problematic. The grain is open and ring-porous, meaning early-growth wood is dramatically softer than late-growth wood within the same board. When a bit crosses from soft to hard in the same pass, you get tearout, fuzzing, and inconsistent depths. It can work with very sharp bits, slow feeds, and finishing passes, but it's never as clean as maple or cherry.

**Pine and Spruce** (construction softwoods) are too soft and resinous for detail work. The resin gums up bits, the soft wood tears rather than cuts cleanly, and the dramatic density difference between growth rings means your bit alternately falls through soft wood and bounces off hard wood. Avoid for anything requiring precision. Acceptable for rough signage or large-scale projects where tearout won't be visible.

**Spalted Wood** (any species with fungal decay patterns) looks incredible but machines terribly. The spalting creates zones of completely different hardness within millimeters of each other. The dark lines are actually harder than surrounding wood, while areas near them may be punky-soft. Your bit doesn't know what it's hitting next. Expect broken bits, inconsistent depths, and lots of sanding.

**Exotic Hardwoods** (Ipe, Purpleheart, Padauk) are extremely hard and often have interlocking grain. They dull bits quickly, generate excessive heat, and some (like Cocobolo) contain oils that prevent glue adhesion. They can be CNC'd with carbide bits at slow feeds, but they're advanced materials. Not where you want to start.

## Practical Settings Starting Points

For a standard 6mm single-flute upcut bit in a hobby-class CNC router (spindle speed 12,000-24,000 RPM):

Soft wood (poplar, MDF): 18,000 RPM, 40-60 mm/s feed, 3mm depth per pass.
Medium hardwood (cherry, walnut): 18,000 RPM, 25-40 mm/s feed, 2mm depth per pass.
Hard wood (maple, birch ply): 20,000 RPM, 20-30 mm/s feed, 1.5-2mm depth per pass.

These are starting points. Your specific machine's rigidity determines how aggressive you can be. A rigid machine with linear rails can push these numbers 30-50% higher. A machine with flex (roller wheels, thin aluminum frame) needs to run at or below these numbers.

## Grain Direction and Climb vs Conventional

When routing solid wood (not plywood or MDF), grain direction relative to the bit path determines surface quality. Cutting with the grain produces the cleanest surface. Cutting against the grain produces tearout on one side.

For pocket operations where the bit travels in all directions, the best strategy is to use a finishing pass (a final very shallow cut at 0.1-0.2mm depth) at higher speed and lower chip load. This cleans up any tearout from the roughing passes.

Upcut bits pull chips out of the pocket (cleaner cut floor) but can tear the top surface of the workpiece. Downcut bits press fibers down (clean top edge) but pack chips into the pocket. Compression bits do both (upcut at the bottom, downcut at the top) and are ideal for plywood where both faces matter.

## The Bottom Line

Start with MDF or Baltic Birch plywood while you learn your machine's capabilities and dial in your feeds and speeds. Move to hard maple when you're ready for solid wood. Avoid oak, pine, and exotics until you understand your machine's limits. Keep your bits sharp (replace or resharpen every 10-20 hours of cutting in hardwood), and always run test cuts in scrap before committing your good material.
