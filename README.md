# Custom-Splash-Image

An add-on for Blender that lets you change the splash image. You can choose a single image or a folder of images to create a slideshow.

# Download

Download [custom_splash_image_*version*.zip](https://github.com/Pazelock/Custom-Splash-Image/releases/tag/Latest)

# How does it work?

The add-on edits your user environment variable called `BLENDER_CUSTOM_SPLASH`.
It may take a couple of seconds for the splash image to update after you apply the changes.
As far as I know, there is no way to display GIFs. Even if they are split into frames, they take too long to form an animation.

# Usage

Prepare your image(s). The aspect ratio is up to you, but if you want your artwork to be scaled like Blender's splash image, use a 2:1 aspect ratio (e.g. 1000 × 500 px).

Allowed formats: `.png` `.jpg` `.jpeg`

Sometimes, for a reason I couldn't figure out, a certain image will always crash Blender whenever it tries to display the splash screen. If this happens to you, continue to the **Issue Resolution** section.
Navigate to `Edit > Preferences > Add-ons`.
Search for `Custom Splash Image` and click the dropdown.
Fill in the required fields.

<img width="666" height="359" alt="image" src="https://github.com/user-attachments/assets/35dbf8a4-3483-477e-8da0-a31b30ff5a03" />

You'll figure it out.

# Issue Resolution

Open the `Edit Environmental Variables for your account` Windows app (preinstalled).

<img width="408" height="465" alt="Screenshot 2026-09-03 123807" src="https://github.com/user-attachments/assets/411e91ab-696c-4b8f-a86f-5205f418171a" />

Click `Environmental Variables...`.

<img width="340" height="auto" alt="image" src="https://github.com/user-attachments/assets/1135d27b-3a4e-4bc6-aab6-bb19904a3bb3" />

Delete `BLENDER_CUSTOM_SPLASH`. Don't worry, it won't break the add-on.

Apply the changes and fully close Blender before opening it again.
