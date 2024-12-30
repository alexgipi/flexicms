# FlexiCMS

FlexiCMS is a lightweight, fast, and powerful Content Management System (CMS) written in Node.js, express, and Astro. It is designed to be easy to use and customizable, with a focus on performance and security.

## Features

- Lightweight and fast
- Easy to use and customize
- Built-in security features
- Support for multiple databases
- Support for multiple languages
- Support for multiple themes
- Support for multiple file types
- Support for multiple file uploads
- Support for multiple file storage locations
- Support for multiple file storage providers
- Support for multiple file processing providers
- Support for multiple file processing locations
- Support for multiple file processing providers
- Support for multiple file processing locations

## Getting Started

To get started with FlexiCMS, follow these steps:

1. Install Node.js and npm (if you haven't already)
2. Clone the FlexiCMS repository to your local machine
3. Navigate to the FlexiCMS directory
4. Run the following command to install the required dependencies:

```
npm install
```

5. Create a new file called `flexi.config.js` in the FlexiCMS directory

6. Open the `flexi.config.js` file in a text editor and add the following code:

```javascript
const Collections = [];
const Settings = [];
const Globals = [];
const AdminChanges = {}

export const lexiConfig = {
  collections: Collections,
  settings: Settings,
  globals: Globals,
  adminChanges: AdminChanges,
  adminChangesEnabled: true,
  ssgDeployEnabled: true,
}