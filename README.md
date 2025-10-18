# Vue Enhancer Kit for Sublime Text 🚀

Welcome to the **Vue Enhancer Kit**! This is a curated collection of tools designed to supercharge your Vue 3 development workflow in Sublime Text. If you love Vue and the speed of Sublime, this kit is built for you.

This repository bundles three essential components to create a seamless and visually pleasing coding experience:
1.  **Custom Vue Syntax (`VueEnhancer.sublime-syntax`)**: A tailored syntax definition that correctly recognizes modern Vue 3 features, including the `<script setup>` block.
2.  **Vibrant Color Scheme (`VueEnhancer-Neon.tmTheme`)**: A striking neon/synthwave-inspired color theme that makes your code pop. It provides high contrast and clear differentiation between tags, attributes, directives, and functions.
3.  **Essential Snippets**: A collection of handy snippets to accelerate common tasks like creating components, defining props, and using the Composition API.

---

## ✨ Features

* **Smart Syntax Highlighting**: Accurately highlights Vue 3 SFCs.
* **Vibrant Neon Theme**: A beautiful, high-contrast theme designed for long coding sessions.
* **Boilerplate Snippet**: Create a full Vue component structure with `vue-sfc`.
* **Composition API Snippets**: Quickly add `ref`, `computed`, `defineProps`, and `defineEmits`.
* **Lightweight & Fast**: Designed to keep your editor snappy.

---

## 🛠️ Installation

Follow these steps to set up the kit in your Sublime Text editor.

### 1. Browse Packages

Open Sublime Text and go to **Preferences > Browse Packages...**. This will open the `Packages` folder on your computer. All files will be placed inside the `User` folder.

### 2. Install the Components

#### a. Syntax Highlighting
1.  Copy the `VueEnhancer.sublime-syntax` file from this repository.
2.  Paste it into your `User` folder.

#### b. Color Scheme
1.  Copy the `VueEnhancer-Neon.tmTheme` file.
2.  Paste it into your `User` folder.
3.  Activate it by going to **Preferences > Select Color Scheme...** and choosing **VueEnhancer (Vibrant Neon)**.

#### c. Snippets
1.  Copy all the `.sublime-snippet` files.
2.  Paste them into your `User` folder.

### 3. Set as Default for Vue Files
To make the syntax and theme apply automatically to all `.vue` files, go to **Preferences > Settings - Syntax Specific** while a `.vue` file is open and add the following:
