📦 Minecraft Asset Structure (Blockbench-Friendly)

This repository follows a clean, scalable structure for organizing Blockbench assets so that models, textures, and related files stay grouped together.

🎯 Goals
Keep assets self-contained
Make it easy to find/edit/export
Support ItemsAdder / resource packs / custom models
Avoid messy global texture/model folders

⚙️ Workflow
1. Create Asset
Make a new folder under /Assets/
Name it after your asset pack
Create 2 new folders under your pack name /Source/ & /Textures/
3. Build in Blockbench
Save .bbmodel inside the source folder
Keep textures inside the texture folder
4. Export
Export to .json directly into the same folder
5. Import to Server
Copy/export assets into your plugin/resource pack structure (e.g., ItemsAdder) (Wait for Ryan to do this step)
