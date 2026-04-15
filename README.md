# aspcore-uploader-webservices

## Repository Description
A comprehensive guide for implementing server-side file upload web services in ASP.NET Core using EJ2 Uploader, including save and remove action handlers for complete upload process management.

## Overview
This repository demonstrates how to manage the complete upload process on the server using ASP.NET Core. It provides implementations for handling file uploads, managing server-side save operations, and optionally managing file removal from the server.

## Features
- **Save Handler Implementation**: Handle file uploads with a dedicated save action URL that manages the upload process
- **Remove Handler Support**: Optional remove action handler for managing file deletion from the server
- **File Management**: Receive and process submitted files with robust server-side handling
- **URL-Based Configuration**: Configure save and remove operations using dedicated URLs through the saveUrl property
- **EJ2 Uploader Integration**: Full integration with Syncfusion EJ2 Uploader component

## Project Prerequisites
Ensure you have the following installed on your machine:
- .NET Core SDK (compatible version for ASP.NET Core)
- Visual Studio or Visual Studio Code
- Basic understanding of ASP.NET Core web development
- Syncfusion EJ2 Uploader component (for client-side)

## How It Works

### Save Handler
The save handler receives the submitted files and manages the save process on the server. Configure the save action URL using the saveUrl property. The handler processes incoming file uploads and persists them to the server storage.

### Remove Handler
The remove action is optional. When configured, the remove handler receives the posted files and handles the removal operation on the server. This allows users to delete previously uploaded files from the server storage.

## Implementation Details
Create server endpoints that handle:
1. File upload requests from the save handler
2. File removal requests from the remove handler
3. Proper error handling and response management
4. File validation and storage operations

## Getting Started
To implement EJ2 Uploader web services in ASP.NET Core, refer to the official documentation link below for comprehensive setup and implementation instructions.

## Documentation and Resources
For detailed instructions on creating and configuring EJ2 Uploader web services in ASP.NET Core:
- **Official Documentation**: https://blazor.syncfusion.com/documentation/file-upload/async#with-server-side-api-endpoint
