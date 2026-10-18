# Natural-Moulded-Pulp-Forming
### Reusing natural fibers with 3d printing to create new things!
A small research-and-build project on **pressing waste fibre (cardboard, paper, fallen leaves) into solid 3D objects** using reusable, 3D printed, 3-part moulds, a printer, a blender and a vise (or press if you have).
<img width="685" height="674" alt="Screenshot 2026-10-18 at 13 31 42" src="https://github.com/user-attachments/assets/0f5688d2-95c9-4421-823a-bd62a82e91aa" />

## What is this?

Paper is almost always flat, because it is made by draining water through a screen. Moulded pulp does it differently: you turn the fibre into a wet pulp, press it into a shape and let it dry. This project asks how far you can take it at home and are we evel limited to conventional fibers?

The goals:

- **Design reusable 3-part moulds** (base, wall, press) that anyone can print and that survive repeated pressing.
- **Find pulp recipes that work**, starting from recycled cardboard and testing other natural fibers like fallen leaves
- **Make the parts stronger and more water resistant** using mostly experimental chemistry.

The idea builds on an Instructable by XYZAidan,

## How it works

1. **Make pulp.** Soak and blend the fibre with a water-soluble binder (rice paste).
2. **Pre-press.** Squeeze most of the water out in a cloth until it feels like wet clay.
3. **Fill the mould** in layers. The mould has a base, a wall frame and a press.
4. **Press.** Compress it in a vise or press as far as it will go. Water leaves through the small gap between wall and press, and through weep holes.
5. **Dry.** Leave it under pressure for about a day, release the press, then dry the part in the mould and finish with a fan or a low oven.
6. **Finish.** Trim any flashing and sand if needed. Optionally add a protective coat.

## Repository content
| Path | Contents |
|------|----------|
|[Docs/](Docs/)|	Test recipes ([Recepies/](Docs/Recepies)) and the research they are based on ([Researsch/](Docs/Researsch))|
|[Forms/](Forms/)| Mould designs: Fusion 360 source files (.f3d) and print-ready .stl parts|
|[BOM.md](BOM.md)|	Bill of materials|
|[JOURNAL.md](JOURNAL.md)|	Devlog, synced from Half Life|
|[LICENSE](LICENSE)|	MIT licence|
|[README.md](README.md)| You are here|

## The moulds

Each mould is a set of printed parts plus its Fusion 360 file, so you can change the dimensions and re-export. 

### Print settings (speculative)

These are the Instructable's settings, in PLA. Adjust for your printer, and see the recipes for which plastics survive an oven.

| Part | Infill | Shells | Floor / ceiling layers |
| --- | --- | --- | --- |
| Base | 10 to 15% | 2 | 2 to 3 / 3 to 4 |
| Wall | 15 to 20% | 3 | 2 / 2 |
| Press | 10 to 15% | 2 | 2 to 3 / 2 to 3 |


## The recipes

Four starter recipes, each sized to make a part of about **100 g oven-dry**. Full ingredient lists and step-by-step instructions are in [`Docs/Recepies/Readme.md`](Docs/Recepies/Readme.md).

| # | Recipe | Fibre | Extra step |
| --- | --- | --- | --- |
| 1 | Cardboard and rice starch | Cardboard | None, this is the baseline |
| 2 | Cardboard, alginate and calcium chloride | Cardboard | Alginate coat, then calcium chloride, for water resistance |
| 3 | Leaf | Maple leaves | None, untreated |
| 4 | Leaf+ | Maple leaves | Baking soda bath first |

## Research

The recipes are built on the papers in [`Docs/Researsch`](Docs/Researsch). 

## Getting started

1. **Print a mould.** Pick one from [`Forms`](Forms), print the base, wall, press and clips, and check that the press slides into the wall.
2. **Gather materials and equipment.** The recipes list what you need. The basics are cardboard or dried leaves, cooked rice, a blender, cheesecloth, a scale and a vise or clamps.
3. **Pick a recipe** and make a quarter-size batch first.
4. **Press and dry** following the recipe.

## Bill of materials
| Item | Qty | Supplier | Cost/item | Total Cost | link |
| --- | --- | --- | --- | --- | --- |
| PLA+ Lime green|1|PRUSA |$17.99 | $17.99 | https://www.prusa3d.com/product/pla-lime-green/ |
| Estimated total shipping | 1 |  | $6.15 |


This project can be done with equipment I all have at home leftover funds will be spent on household items at the supermarket like baking soda and rice for the pulp making process.

## Help

Contact author 

## Author

Lucas Klemmer  
klinksolutions22@gmail.com

## License
MIT LIcense

If anyone ends up reproducing this project  or making it even better I would be happy to see your improvements and add them to the official release.
