reference files


- tutorial plan trace image [mutlistorey-trace-image.png](./mutlistorey-trace-image.png)
- door ifc file [D-800-leftswing.ifc](./D-800-leftswing.ifc)
- library used [IFC4-AU-Library.ifc](.IFC4-AU-Library.ifc)
- final ifc file [multistorey2floor.ifc](./multistorey2floor.ifc)

---

## BlenderBIM - git
- BIM [github colab youtube](https://www.youtube.com/watch?v=cJZhSCSSWdA) for this BIM [github example project](https://github.com/brunopostle/ifc-demo)
	- [ ] IFC Git panel [tc 2:48](https://youtu.be/cJZhSCSSWdA?t=168)
	- [ ] git show uncommited changes [tc 5:52](https://youtu.be/cJZhSCSSWdA?t=352)
	- [ ] git commit message [tc 6:25](https://youtu.be/cJZhSCSSWdA?t=385)
	- [ ] git load prev commit [tc 6:30](https://youtu.be/cJZhSCSSWdA?t=390)
	- [ ] git commit on new branch "mybranch" [tc 7:35](https://youtu.be/cJZhSCSSWdA?t=455)
	- [ ] git merge branches [tc 8:25](https://youtu.be/cJZhSCSSWdA?t=515)
	- [ ] IFC would allow windows in the same place as they are objects, so you need to run object clash detection process [tc 10:51](https://youtu.be/cJZhSCSSWdA?t=651)
	- [ ] git push to github [tc 18:07](https://youtu.be/cJZhSCSSWdA?t=1087)
	- [ ] git add remote repo under BlenderBIM [tc 23:04](https://youtu.be/cJZhSCSSWdA?t=1384)
	- [ ] github fork [tc 24:03](https://youtu.be/cJZhSCSSWdA?t=1443)
	- [ ] git clone remote repo [tc 25:04](https://youtu.be/cJZhSCSSWdA?t=1504)
	- [ ] submit PR to repo from fork [tc 27:30](https://youtu.be/cJZhSCSSWdA?t=1650)
	- [ ] merge PR to repo [tc 29:00](https://youtu.be/cJZhSCSSWdA?t=1740)
	- [ ] fetch from github (remote) [tc 30:19](https://youtu.be/cJZhSCSSWdA?t=1819)
	- [ ] Inspect PR request changes [tc 30:32](https://youtu.be/cJZhSCSSWdA?t=1832)
- BlenderBIM - Git [BlenderBIM experimental IFC Git add-on Demo](https://www.youtube.com/watch?v=-Y5-LR4oik8)
	- [ ] git create repo [tc 0:11](https://youtu.be/-Y5-LR4oik8?t=11)
	- [ ] git house.ifc add [tc 0:15](https://youtu.be/-Y5-LR4oik8?t=15)
	- [ ] making changes [tc 0:42](https://youtu.be/-Y5-LR4oik8?t=42)
	- [ ] git show uncommitted changes [tc 1:09](https://youtu.be/-Y5-LR4oik8?t=69)
	- [ ] git commit message [tc 1:19](https://youtu.be/-Y5-LR4oik8?t=79)
	- [ ] git commit [tc 1:20](https://youtu.be/-Y5-LR4oik8?t=80)
	- [ ] git revert move back to earlier commit [tc 1:29](https://youtu.be/-Y5-LR4oik8?t=89)
	- [ ] modify earlier version [tc 1:40](https://youtu.be/-Y5-LR4oik8?t=100)
	- [ ] git show detatched head uncommitted changes [tc 2:07](https://youtu.be/-Y5-LR4oik8?t=127)
	- [ ] git commit message to new branch [tc 2:12](https://youtu.be/-Y5-LR4oik8?t=132)
	- [ ] go back to main branch [tc 3:33](https://youtu.be/-Y5-LR4oik8?t=153)
	- [ ] select forked branch to merge with main branch [tc 2:47](https://youtu.be/-Y5-LR4oik8?t=167)
	- [ ] git show uncommitted changes [tc 3:05](https://youtu.be/-Y5-LR4oik8?t=185)
	- [ ] git commit changes [tc 3:09](https://youtu.be/-Y5-LR4oik8?t=189)
	- [ ] git commit changes [tc 3:09](https://youtu.be/-Y5-LR4oik8?t=189)

---
# BlenderBIM - quick reference

- Snap Settings: [BlenderBIM Tutorial - tc 1:00](https://youtu.be/kF2k_VW-yrQ?t=60) and  [BlenderBIM MultiStory - tc 0L28](https://youtu.be/ewvlodE1Nxg?t=28)
	- Snap to: Vertex, Edge, Face Project, Edge Center
	- Closest
	- Move
- Gizmo Settings  [BlenderBIM Tutorial - tc 1:147](https://youtu.be/kF2k_VW-yrQ?t=74)
	- enable Move so it shows in view
- But Joint: [BlenderBIM Tutorial - tc 3:16](https://youtu.be/kF2k_VW-yrQ?t=196)
	- Left Click Priority wall
	- Shift Left Click lapping wall
	- Shift - T (will but Join the two walls)

---


## blenderbim-tutorial

- [x] [Blender.org](https://www.blender.org/) 
	- [x] releases [download](https://download.blender.org/release/) current 4.1
	- [x] run blender-xxxx-xxx.msi should install in C:\Program Files\Blender Foundation
- [ ] Examples followed [Ifc Architect - youtube](https://www.youtube.com/@IfcArchitect/videos)
	- [x] 0.0.240402 [BlenderBim - Install](https://www.youtube.com/watch?v=I-937k6fvKk)
		- [x] [BlenderBim release - download](https://github.com/IfcOpenShell/IfcOpenShell/releases)
		- [x] [Addon Install tc 3:17](https://youtu.be/I-937k6fvKk?t=197) File -> Preferences - Addons -> Install select Bim download zip
		- [x] Go back and click on the BIM Addon to activate
		- [x] Should see Blender 4.1.1 and BlenderBIM v0.0.230402 in bottom right
---
## blenderbim-tutorial [github](https://github.com/2cld/blenderbim-tutorial)
- [ ] Uses blender 3.4 and blenderbim-230202-py310-win
- [ ] [x] [Blender.org](https://www.blender.org/) 
	- [x] releases [download](https://download.blender.org/release/) current 4.1
	- [x] run blender-xxxx-xxx.msi should install in C:\Program Files\Blender Foundation
- [ ] Examples followed [Ifc Architect - youtube](https://www.youtube.com/@IfcArchitect/videos)
	- [x] 0.0.240402 [BlenderBim - Install](https://www.youtube.com/watch?v=I-937k6fvKk)
		- [x] [BlenderBim release - download](https://github.com/IfcOpenShell/IfcOpenShell/releases)
		- [x] [Addon Install tc 3:17](https://youtu.be/I-937k6fvKk?t=197) File -> Preferences - Addons -> Install select Bim download zip
		- [x] Go back and click on the BIM Addon to activate
		- [x] Should see Blender 4.1.1 and BlenderBIM v0.0.230402 in bottom right
		- [ ] Snaps enabled (magnet): 
			- [ ] Vertex, Edge, Face, 
			- [ ] Edge Center, Edge Perp, 
			- [ ] Closest, 
			- [ ] Move
		- [ ] Viewpoint Gismos
			- [ ] Nav, Active Tools, Active Opbect
			- [ ] Default: Move
			- [ ] Empty: all
			- [ ] Light: All
			- [ ] Camera: All
	- [ ] [2cld - github repo release 1 multistorey2floor](https://github.com/2cld/blenderbim-tutorial) using tutorial [BlenderBim - Multistorey building](https://www.youtube.com/watch?v=ewvlodE1Nxg) tutorial
		- [x] site for image and ifc files here: [Multistorey Assets page](https://community.osarch.org/discussion/1344/blenderbim-beginner-tutorial-multistorey-building-in-40mins/p1?new=1)
		- [x] enable snaps (upper magnet mix virt edge face)
		- [x] enable import images as planes
		- [x] Import drawing in plan view (num 7 - click z) drag in image
		- [x] right click -> trace image with grease pencil scale 0.98
		- [x] line up object to origin point
		- [x] rtclick -> set Origin -> Origin to 3D Cursor
		- [x] IFC Project Info -> IFC Project -> IFC4, Metric, Millimeters, Square Metre, Cubic Meter, IFC4 Demo Library
		- [ ] Select IfcStorey object - first floor
		- [ ] press n
		- [ ] Select IfcWallType WAL100 length 5000
		- [ ] shift-a (add wall) shift- r,r,r to rotate so it's going down
		- [ ] s scale to grease image to garage wall 3.6
		- [ ] copy plan and scale to 
	- [ ]   [2cld - github repo release 2 section](https://github.com/2cld/blenderbim-tutorial) using  tutorial [BlenderBim Section](https://www.youtube.com/watch?v=ClS-6taDO1M)
		- [ ]   tbd [tbd](tbd)
		- [ ]   tbd [tbd](tbd)
		- [ ]   tbd [tbd](tbd)
		- [ ]   tbd [tbd](tbd)
		- [ ]   tbd [tbd](tbd)
		- [ ]   tbd [tbd](tbd)
		- [ ]   tbd [tbd](tbd)
		- [ ]   tbd [tbd](tbd)
	- [ ]   End of Multistorey Ifc Architect tutorial mods
- [ ] tbd [tbd](tbd)
- [ ] tbd [tbd](tbd)
- [ ] tbd [tbd](tbd)
- [ ] tbd [Adding Texture](https://youtu.be/ZyRzAX4x-FQ?t=2932)
- [ ] tbd [Stable Diffusion - Arch AI](https://youtu.be/ZyRzAX4x-FQ?t=4568)
- [ ] tbd [tbd](tbd)
---
### Blender Site Layout
- [Google Maps to Blender 2023 - GIS Solutions](https://www.youtube.com/watch?v=h2_39L2fxkc)
	- [GIS Solutions - Videos](https://www.youtube.com/@gissolutions4604/videos)
- [Google Maps 3D: Data into Blender](https://www.youtube.com/watch?v=F_XsmoZJmG8)
	- [Nicko16 - Videos](https://www.youtube.com/@Nicko16/videos)
- [Google Maps to Blender 2024](https://www.youtube.com/watch?v=4qYM3Gwfw00)
- https://github.com/eliemichel/MapsModelsImporter
