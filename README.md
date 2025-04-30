# **InspireTab \- Chrome Web Extension**

**Main Branch**

*InspireTab is a **source-available** Chrome web extension that transforms your new tab page into a visually inspiring and highly functional workspace. Each time you open a new tab, InspireTab provides a scenic background visual, personalized dynamic greetings, inspirational quotes, quick search functionality, integrated bookmarks, customizable shortcuts, a handy mini to-do list, and an entertaining random name generator. Designed as an ethical alternative to MomentumDash, InspireTab emphasizes efficiency, and a modern user experience.*

## **Features**

* **Rotating Scenic Backgrounds**: Fresh, inspiring images every time you open a tab.  
* **Dynamic Greetings**: Personalized messages that change depending on the time of day.  
* **Inspirational Quotes**: Secular along with biblical quotes.   
* **Integrated Search Bar**: Quick and easy access to search immediately upon entering a new name.  
* **Bookmarks and Shortcuts**: Add your own shortcuts or utilize integrated Google Bookmarks by clicking the extension icon.  
* **Mini To-Do List**: Positioned towards the right side of the screen, helping you manage daily tasks.  
* **Random Name Generator**: Generates creative and amusing names instantly.

## **Installation**

To clone the main branch of InspireTab, use the following command: (check if you have git with: git  \--version in the cli/terminal)

**git clone \-b main \--single-branch https://github.com/danielPapovic1/InspireTab.git**

This ensures you are using the most current and actively maintained version. InspireTab will also be available in the Chrome Web Store soon.

## **Previous Versions**

For access to older releases or historical reference, please see the `previous-versions` branch.

## **Setup & Usage**

1. **Clone the repository** using the provided command.  
2. **Load the extension** into Chrome:  
   * Open Chrome and go to `chrome://extensions`.  
   * Enable "Developer mode" (toggle at the top-right corner).  
   * Click "Load unpacked" and select the cloned repository folder.  
3. **Personalize your experience** by entering your name and preferences directly on the new tab page.

## **Development**

* Built with **Manifest V3**, meeting the latest security and performance standards.  
* Utilizes a modular approach to HTML, CSS, and JavaScript for clear and maintainable code.  
* Uses GitHub Pages for hosting of the “About” link.   
* Integrates third-party resources and libraries:  
  * **DataMuse API**: Enables the random name generation feature.  
  * **Bulma**: Modern, responsive CSS framework.  
  * **Font Awesome**: Provides scalable vector icons.  
  * **Animate.css**: Adds engaging CSS animations.  
* Employs Chrome's storage API for efficient state management and cross-device synchronization. (Name synced across all devices; other details stored locally only)
* Permissions for Bookmarks and the Side Panel are also specified in the Manifest V3 file.

## **Images**

![InspireTab Screenshot 1](https://i.postimg.cc/YS4ngxwh/ss1.png)


![InspireTab Screenshot 2](https://i.postimg.cc/LsMZSz3r/ss2.png)

## **Planned Upcoming Updates**
