# Installation
### Install Blender IFC Add-On
1. Install Blender using the graphical installer from [the Blender download page](https://www.blender.org/download/)
1. Download IFCOpenShell from [The IFCOpenShell download page](http://ifcopenshell.org/)
   Make sure you have the right version. For your Blender Version, the 0.5.0 preview 2 works fine with Blender 2.79. ![IFCOpenShell for Blender](images/blender_install_ifc.PNG?raw=true)
1. Start Blender and press CTRL-ALT-U to open the User Settings
1. click on "Add-ons" and then the "Install Add-on from File..." button
   ![install addon](images/blender_install_addon.png?raw=true).
1. Select the downloaded IfcOpenShell-zip file and import it.
1. Now the Import-Export IfcBlender-Add-On should be available. If you search for "ifc" you should see it. Activate it by clicking on the checkbox to the left of its entry:
   ![activate addon](images/blender_activate_addon.png?raw=true).
1. (optional) if you like to load the Add-on every time Blender starts click the "Save User Settings"-button.
1. Close the "User Preferences" window and make sure the installation was successful. Under "File" -> "Import" you should see "Industry Foundation Classes (.ifc)"<br/>
   ![IFC in Blender](images/blender_start_ifc_addon.png?raw=true).
1. Make sure to remove everything (cameras, lights, other meshes, ...)  before you import a building! Just press `a` in 'Object Mode' to select everything (you might need to press it twice if there is something selected) and `x` and confirm by clicking on `Delete X`.

### Install IfcBlender
1. Quit Blender if it is running
1. Download/Checkout [python-ifc-model](https://github.com/brean/python-ifc-model)
1. Download [IfcOpenShell for python](http://www.ifcopenshell.org/python.html) for your blender version (for Blender 2.79 you can use "IfcOpenShell-python for python 3.5 64bit Windows")
1. Extract the downloaded files and copy the folders `ifc_model/ifc_model` (the sub-folder) and `ifcopenshell`  to `<Blender Installation Folder>\<Blender Version>\python\lib`
   ![Python-libs inside Blender](images/ifc_model_path.png?raw=true)

(TODO: installing this as Blender Add-On from the UI would be nice...)
