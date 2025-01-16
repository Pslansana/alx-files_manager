# 0x04. Files Manager

## Description

This project is a **simple file management platform** that allows users to upload, view, and manage files. The project was built as part of a back-end curriculum focused on mastering key back-end concepts such as authentication, data storage, background processing, and API development.

The platform provides the following features:

- **User Authentication** via a token system
- **File Upload** with support for different file types
- **File Listing** to view all uploaded files
- **File Permissions** to change access permissions
- **File Viewing** with support for generating image thumbnails
- **Background Workers** for processing tasks in the background

The goal of this project was to build a complete product by assembling different back-end components into a cohesive system.

---

## Learning Objectives

By completing this project, we learned how to:

1. Create an API using **ExpressJS**
2. Implement user authentication with **JWT (JSON Web Tokens)**
3. Store persistent data using **MongoDB**
4. Store temporary data using **Redis**
5. Set up and use background workers with **Kue**
6. Handle file uploads and generate image thumbnails

---

## Technologies Used

- **Node.js**: JavaScript runtime for building the back-end
- **ExpressJS**: Framework for building APIs
- **MongoDB**: NoSQL database for storing persistent data
- **Redis**: In-memory data store for caching and temporary data
- **Kue**: Job queue for background task processing
- **Mocha & Chai**: Testing framework and assertion library
- **Nodemon**: Tool for monitoring changes during development
- **ESLint**: Linter to enforce code quality and consistency

---

## Requirements

- **Editors**: `vi`, `vim`, `emacs`, `Visual Studio Code`
- **OS**: Ubuntu 18.04 LTS
- **Node.js Version**: 12.x.x
- All files must end with a new line
- All code must use the `.js` extension
- The project will be verified using **ESLint**

---

## Features

### 1. User Authentication
- Users can register and log in to receive an authentication token.
- Authenticated users can perform operations such as uploading and viewing files.

### 2. File Upload
- Users can upload files of various types (text, image, etc.).
- Files are stored in MongoDB, and metadata is managed efficiently.

### 3. File Listing
- Authenticated users can view all their uploaded files.
- Pagination is supported for large file lists.

### 4. File Permissions
- Users can change the permissions of their files to control access.

### 5. File Viewing
- Users can view files directly, and for images, thumbnails are generated.

### 6. Background Processing
- Background tasks such as thumbnail generation are handled using **Kue** and processed asynchronously.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/0x04-files-manager.git
   cd 0x04-files-manager

