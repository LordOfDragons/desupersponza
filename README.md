# Drag[en]gine Super Sponza
Test project using the Super Sponza (2022) scene. For Super Sponza credits see
file __supersponza_credits_license.txt__.

The scene has been edited with these changes:
- Converted textures to 1k resolution (*.webp where suitable) to cut down their overall size
- Cleaned up meshes to allow exporting to *.demodel files (removed some manifold problems)
- Replaced unique meshes with instance meshes where suitable. This looses some uniqueness but allows using element classes for better testing.
- Added GI LOD meshes (~300 triangles) to allow using the scene with fragment shader ray traced GI
- Added environment map probes

Todo:
- Adding choosable scene configurations for testing different graphical setups

To test download the *.delga file and run it using Drag[en]gine Game Engine (https://dragondreams.ch/?page_id=152#downloads-dragengine).

To edit the test scene download the repository and open the *.degp file using Drag[en]gine IGDE (https://dragondreams.ch/?page_id=152#downloads-igde).

NOTE:
Due to Github LFS quotas data objects are not included in the source code download only code. Use GIT client to fetch all data.
To do this install GIT LFS then call:
  git lfs pull --exclude=
