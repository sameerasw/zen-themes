# Transparent Zen
Make the Zen Browser's background transparent allowing the macOS system window blur or Windows mica blur to come through. Known to be supported on macOS, Windows 11, KDE and Hyprland but Windows 10 is not supported while Gnome doesn't have a proper implementation for transparency either.

Website specific transparency need to be achieved with the [Zen Internet addon](https://addons.mozilla.org/en-US/firefox/addon/zen-internet/).

## Full guide for website transparency : [sameerasw.com/zen](https://www.sameerasw.com/zen)

![CleanShot 2025-02-03 at 5  26 38@2x Large](https://github.com/user-attachments/assets/b7c0fbb4-75cc-4457-ba64-c46cc486338c)

> Make sure to visit Zen Browser settings > mods > Transparent Zen settings to enable after install. Enabling transparency might need a re-start of the browser.

<img width="1344" alt="CleanShot 2025-05-03 at 4  50 40@2x" src="https://github.com/user-attachments/assets/d2f7c692-b84d-499a-99f6-e66e08489db3" />


## Feature explanation

1. `"Allow transparency"` - This will toggle the `browser.tabs.allow_transparent_browser` and `zen.widget.linux.transparency` (Linux only) flag in `about:config` to `true`. This remove the default backplate from the browser webpage view so it shows what's behind it instead so when the browser sidebar is also transparent, this allows the whole webpage to be transparent as well (if the webpage also modified to be transparent with the addon). Turn off before uninstalling since this will not be reset by Zen.
       
      <img width="435" alt="CleanShot 2025-05-03 at 4  56 41@2x" src="https://github.com/user-attachments/assets/eb37f988-8b84-4086-a3fb-ca66ac668c3d" />

2. `"Custom background color"` - These two options allows you to override the default workspace theme gradient and colors and use a custom color for it to instantly apply themes like Nord if you use it's default background color. You can also use expanded css properties like `light-dark(#fff, #222)` here so it becomes dynamic.

     <img width="773" alt="CleanShot 2025-05-03 at 4  58 06@2x" src="https://github.com/user-attachments/assets/aee697ec-9936-42c9-8790-59ca0e993d1b" />

3. `"Light website tint"` - Zen 1.8b added a white tint to the background of the webpage but it does not switch to a dark color in the dark theme. These options allows you to either flip the color or to completely remove the tint.

     <img width="286" alt="CleanShot 2025-05-03 at 5  00 28@2x" src="https://github.com/user-attachments/assets/b9eb8ea3-e7d2-44e4-bba2-f7afdad7afd0" />
     <img width="1236" alt="image" src="https://github.com/user-attachments/assets/507f1120-9440-4c78-9da0-b5d0bc043fe7" />

4. `"Remove the shadow aroudn the webpage"` - Removes the drop shadow around the website area allows the sidebar and the website to be a seamless, one glass like a view.

     <img width="305" alt="CleanShot 2025-05-03 at 5  06 24@2x" src="https://github.com/user-attachments/assets/1fa187a5-046d-4319-b227-9a75f2135348" />

5. `"Tab switch animation"` - Adds a nice smooth animation to switch between tabs

     <img width="218" alt="CleanShot 2025-05-03 at 5  09 07@2x" src="https://github.com/user-attachments/assets/2e92db0d-671d-4aaf-acbc-9c0cfc0708d5" />

     ![CleanShot 2025-05-03 at 5  13 16](https://github.com/user-attachments/assets/acd79174-a35c-4c79-b51e-0165e97911af)

6. `"URLbar zoom animation"` - Adds a smooth depth animation effect to the urlbar when opened

     <img width="246" alt="CleanShot 2025-05-03 at 5  15 39@2x" src="https://github.com/user-attachments/assets/8b79775b-aceb-4dfd-98a6-802ed62837ff" />

     ![CleanShot 2025-05-03 at 5  17 04](https://github.com/user-attachments/assets/ff81146c-3289-4838-9dd7-92878ca39f34)

7. `"Trackpad animation"` - Adds a movement animation to the trackpad gestures to visualize the navigation direction better.

     <img width="212" alt="CleanShot 2025-05-03 at 5  18 38@2x" src="https://github.com/user-attachments/assets/8bde5447-0eca-4bab-99a5-66d64c90d242" />

     ![CleanShot 2025-05-03 at 5  20 16](https://github.com/user-attachments/assets/7302f58c-ff66-40a7-9b38-2b5adc456772)

8. `"no tab screen background image"` - Allows you to add a custom background image or a logo for the boring screen when no tabs are opened or active. Better to use local images to reduce loading delay and when changing the image, use the full css url() selector with the link `url('example.com/1.png')`. For Windows, `file:///` prefix might be necessary `url('file:///C:/Users/mom/Pictures/topography-black.jpeg')` for example.
   - You can customize the image size, opacity too.
   - You can also grayscale the image and make it flip the color in light theme as well.
   - For flipping colors, better to use a white png icon.

   ![CleanShot 2025-05-11 at 5  43 50@2x](https://github.com/user-attachments/assets/0348f3d3-f4ca-4245-98ae-5c44d15e596e)

   <img width="1731" alt="image" src="https://github.com/user-attachments/assets/7da25d57-bd05-41c8-90c6-073a8fbf8359" />

<br>

For any support, feel free to contact [me personally](https://www.sameerasw.com), post on [r/zen_browser](https://www.reddit.com/r/zen_browser/), in [discord](https://discord.com/channels/1088172780480114748/1335963848087306333) tagging me or in [telegram in my community](https://t.me/tidwib) but preferably in [Github as an issue, feature request or a discussion](https://github.com/sameerasw/my-internet/issues). :3

