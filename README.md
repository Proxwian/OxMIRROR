## OxMIRROR

A place for mod files, which can't be downloaded directly from CurseForge.com in custom Minecraft launchers like [OxLAUNCHER](https://github.com/Proxwian/OxLAUNCHER), GDLauncher, etc.

You can add project files via merge requests with this structure:
- **/curseforge-project-id/file-id**
- **/curseforge-project-id/README.md** with Mod name, direct link to the project, and list of file-ids with human-friendly file name to download
- **/cached/file-id** for files that not present on CurseForge site or doesn't have a project
- **/manifests/curseforge-project-id.json** additional manifest to download files for project with curseforge-project-id
- **/addons** folder contains json for downloadable files from /manifests
