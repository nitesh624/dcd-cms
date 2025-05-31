# DCD Drupal Custom Theme

This is the custom Drupal theme named **DCD**, built with SCSS support and structured for modern frontend development.

---

## 🚀 Quick Start – Setup After Clone

### 1. Clone the Theme

Clone or copy the theme into your Drupal project’s custom themes directory:

bash
cd themes/custom
git clone <repo-url> dcd

### 2. navigate into the theme directory and install the required Node.js dependencies, then compile the SCSS files into CSS by running
cd dcd  
npm install  
npm run build      # Compile SCSS to CSS once  
npm run watch      # (Optional) Keep watching for changes and auto-compile  

### 3.Enable the theme in Drupal and set it as the default theme by running these commands from the root of your Drupal project
drush theme:enable dcd  
drush config:set system.theme default dcd  
drush cr
