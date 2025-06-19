# Advanced Tab Groups  

CSS for Zen Browser's experimental Tab Groups using `userChrome.css`.  

Easy Installation: https://github.com/CosmoCreeper/Sine, go to Sine Mods (Where Zen Mods used to be) and put in "Anoms12/Advanced-Tab-Groups"

![Advanced Tab Groups](https://github.com/user-attachments/assets/9541500c-4c91-4bf0-97b2-f8a519a0144f)  


Good news on official support! https://github.com/zen-browser/desktop/tree/tab-folders

> [!WARNING]
> 
> * This is not reccomended by the creator of [Zen Browser](https://github.com/zen-browser/desktop) only use this if you have an understandying of CSS or are ok with the following things:
>
>  * When maruo finishes tab folders you NEED to disable this CSS, or the groups will break, _be coutious_!!!
>  * Tab groups may be deleted in other workspcaes besides your default when you close the browser, causing them to be unredeamable
>  * Nested tab groups are not possible with pure CSS
>  * saving a tab group may break the group and make it unredeamable (please activate the config to avoid saving issues.) -This no longer is an issue on twilight as you can save tab groups, scroll down to learn more.
>  * This does not work with the expand sidebar on hover mod.
>  * Any issues you encounter please create a ticket on the GitHub page and I will do what I can to help you quickly.




## Setup

_To use this CSS, you must configure Zen Browser's `userChrome.css` and enable the listed preferences in `about:config`._  

If you're unfamiliar with `userChrome.css`, please refer to [this guide](https://docs.zen-browser.app/guides/live-editing). If you encounter any issues, feel free to create an issue on this repository.  

---

## How to Use  

1. Enable `browser.tabs.groups.enabled` in `about:config` to activate Firefox's experimental Tab Groups feature (works in all versions of Zen Browser).  
2. Follow [this guide](https://docs.zen-browser.app/guides/live-editing) to set up `userChrome.css`.  
3. Copy the CSS from this repository into your `userChrome.css` file.  
4. Add the configuration booleans listed below in `about:config` and adjust them to your liking.
5. Right click on the tab you want to group, select add tab to new group then follow the settup. (If this is not an option please check step 1)
6. Enjoy your customized tab groups!  

---

## Configuration Options  

**Add** these preferences to `about:config` to enable additional features **(They have to be added and are not there by default.)**:  

- **`tab.groups.add-arrow`**  
- **`tab.groups.background`**  
- **`tab.groups.borders`**  
- **`tab.groups.theme-folders`**  
- **`tab.groups.fill-folders`**
- **`tab.groups.display-tab-range`**
- **`tab.groups.disable-animations`**
---

## What Does This Do?  

This CSS improves the functionality and appearance of Zen Browser's experimental Tab Groups.  

---

## Features  

### 1. **Custom Background for Tab Groups**  
Apply a background that matches the tab group color for a cleaner and more cohesive look.

![Group Background](https://github.com/user-attachments/assets/072399e3-6d1a-4e18-bcb6-d4ffc14e99b4)

---

### 2. **Border Around Tab Groups**  
Add a subtle border to enhance the visual separation of tab groups (requires background to be enabled).  

![Group Background With Borders](https://github.com/user-attachments/assets/45e87a2a-da2b-485f-bcb0-7dc1c35da1ac)

---

### 3. **Expandable Tab Groups with Arrows**  
Add an arrow icon to indicate whether a tab group folder is open or closed.  

![Add Arrows](https://github.com/user-attachments/assets/b813a989-5622-4b79-9aa6-0528b48d9850)

---

### 4. **Themed Folder Icons**  
Color folder icons based on the tab group color to visually differentiate groups.  

![Theme Icons](https://github.com/user-attachments/assets/cb4e4c1e-73d6-4688-bb41-76675ef4afae)

---

### 5. **Folder Icon Fill**  
Customize the folder icon fill with your tab group color—or leave it empty, depending on your preference.  

![Fill Icons](https://github.com/user-attachments/assets/befc0ac8-2861-4ff8-9b16-e5ce00cf647a)

---

### 5. **Display Tab Range**  
Have a line sowing where the folder starts and stops  

![Tab Range](https://github.com/user-attachments/assets/e0bf30d3-39df-46da-b746-7cfb54f82f09)

---

## Suggestions  

Have an idea for a feature? Start a discussion! I'm happy to explore any Zen CSS-related requests.  

---

## Credit  

Special thanks to [https://github.com/nieffka/bubble-clean-zen](https://github.com/nieffka/bubble-clean-zen) for the original CSS theme and inspiration!

<img src="https://github.com/heyitszenithyt/zen-browser-badges/raw/fb14dcd72694b7176d141c774629df76af87514e/light/zen-badge-light.png" alt="Made For Zen Badge">
