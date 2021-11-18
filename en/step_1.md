## Setup Unity for WebGL export

If this is your first time exporting a project to WebGL, you need to change your build settings.

Click on the **File** menu and select **Build Settings...**.

![File menu selected and Build Settings highlighted](images/1_file_build_settings.png)

On the next screen select **WebGL** and click on the **Install with Unity Hub** button.

![WebGL option selected and the Install with Unity Hub button highlighted](images/2_install_webgl.png)

On the next screen, click the **Install** button, then wait for the WebGL module to be installed.

![Add modules screen with Install button highlighted](images/3_add_modules.png)

Once the module has installed, you can close Unity Hub and then close Unity and restart it.

Once Unity has opened, check that the **Build Settings** from the **File** menu have updated, and showing that WebGL has been installed. Then click on the **Player Settings** button

![Build Settings window shown with the WebGL options highlighted and the Player Settings button highlighted](images/5_webgl_installed.png)

From the **Player** menu on the left, in the collapsible menu for **Publishing Settings**, select **Disabled** from the **Compression Format** options.

![Project setting window with the Player menu highlighted and the Compression format set to Disabled and highlighted](images/6_disable_compression.png)

You can close the settings window and now move on to building the project.