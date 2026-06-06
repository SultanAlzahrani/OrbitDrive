# Orbit Drive

**Orbit Drive** is a self-hosted intelligent file management system designed for organizations that require complete control over their data. It enables teams to securely store, organize, search, and analyze files within a private network without relying on third-party cloud providers.

By combining local-first storage with AI-powered features, Orbit Drive helps users find information faster, maintain data privacy, and improve file organization.

---

## Key Features

- **Self-Hosted Storage** – Keep all data within your organization's infrastructure.
- **Smart File Tagging** – Automatically organize files using generated tags.
- **Semantic Search** – Search by meaning instead of exact file names or keywords.
- **AI-Powered Summarization** – Generate summaries for text and audio content.
- **Storage Analytics Dashboard** – Monitor storage usage and file statistics.
- **Advanced File Management** – Move, star, delete, download, and organize files with ease.
- **Privacy First** – Your data never leaves your network.

---

## Why Orbit Drive?

Organizations often struggle with:

- Scattered files across multiple systems
- Difficult and inefficient search experiences
- Rising cloud storage costs
- Privacy concerns regarding third-party cloud providers
- Uncertainty about how uploaded data may be used

Orbit Drive addresses these challenges by providing a centralized, self-hosted solution that keeps your data under your control while enhancing productivity through AI-powered organization and search capabilities.

---

# Application Overview

The purpose of this README is to showcase the major features of Orbit Drive through screenshots. Instructions for running the project are provided near the end of this document.

---

## Welcome Page

![Welcome Page](screenshots/welcome.png)

An early version of the landing page. The example shown contains a folder named **Commands** with multiple files.

---

## Home (Root Directory)

![Home Page](screenshots/home.png)

The main file browser interface.

Features include:

- File and folder navigation
- Analysis status indicators
- Generated summaries
- View, Download, Edit, and Delete operations

---

## Recent Files

![Recent Page](screenshots/recent.png)

Displays recently uploaded files for quick access.

---

## Starred Items

![Starred Page](screenshots/starred.png)

View all starred files and folders in one location.

---

## Dashboard

![Dashboard Page](screenshots/dashboard.png)

Provides analytics and statistics related to storage usage and system activity.

---

## Duplicate Detection

![Duplicate Page](screenshots/duplicate.png)

Identify potentially duplicate files using a configurable similarity threshold.

---

## Folder View

![Folder Page](screenshots/folder.png)

Example view of the **CPCS449-Showcase** folder.

Supported operations include:

- Sort by name
- Sort by date
- Sort by size
- Multi-selection
- Bulk delete
- Bulk download
- Bulk starring

---

## File Details View

![File Page](screenshots/file.png)

Displays detailed information about a selected file.

Features include:

- File path navigation
- View, Download, Delete, and Refresh actions
- Metadata display
- AI-generated tags
- Processing status
- Generated summary

---

# File Operations

## Uploading Files

The upload workflow supports drag-and-drop file uploads and progress tracking.

![Upload Page](screenshots/upload.png)

![Upload Page](screenshots/upload2.png)

![Upload Page](screenshots/upload3.png)

![Upload Page](screenshots/upload4.png)

![Upload Page](screenshots/upload5.png)

![Upload Page](screenshots/upload6.png)

---

## Context Menu Operations

### Single Item Operations

![SingleOperation](screenshots/singleoperation.png)

Actions available when right-clicking a single file or folder.

---

### Batch Operations

![BatchOperation](screenshots/batchoperation.png)

Actions available when multiple items are selected.

---

## Moving Files and Folders

Example workflow for moving folder contents using the **Move To** operation.

### Step 1

![Move](screenshots/move.png)

### Step 2

![Move2](screenshots/move2.png)

### Step 3

![Move3](screenshots/move3.png)

The selected files and folders are successfully transferred to the destination folder.

---

# Search System

## Search Bar

![Searchbar](screenshots/searchbar.png)

The search component allows users to configure:

### Search Types

- **Keyword Search** – Traditional text matching
- **Semantic Search** – Meaning-based retrieval

### Search Scope

- **Global Search** – Search across all files
- **Local Search** – Search within the current folder

---

## Semantic Search Example

![SearchbarResults](screenshots/searchresults.png)

The returned results do not necessarily contain the exact search terms. Instead, Orbit Drive retrieves files whose content is semantically related to the query, demonstrating meaning-based search capabilities.

---

# Duplicate Detection

## Configure Similarity Threshold

![dup1](screenshots/dup1.png)

Choose the similarity threshold used to detect duplicate or near-duplicate files.

---

## Duplicate Detection Results

![dup2](screenshots/dup2.png)

Results are grouped by similarity.

Users can:

- Open files
- Compare content
- Review detected duplicates
- Decide which files should be retained or removed

---

# Getting Started

## Prerequisites

- A machine capable of running the Orbit Drive server
- Access to a local network
- Python and required project dependencies

## Running Orbit Drive

1. Clone the repository.
2. Install the required dependencies.
3. Configure the server environment.
4. Start the backend services.
5. Launch the web interface.
6. Open the application in your browser.

## Basic Usage

1. Upload files through the web interface.
2. Organize files using folders and tags.
3. Allow the AI processing pipeline to analyze uploaded content.
4. Use semantic search to locate information quickly.
5. View generated summaries and metadata.

---

# Project Team

## Sultan Alzahrani

- GitHub: https://github.com/SultanAlzahrani
- Twitter/X: https://x.com/CEO_allegations
- Website: https://sultanonline.app
- LinkedIn: https://www.linkedin.com/in/sultan-bandar-548628283/

## Badr Al-Lehyani

- GitHub: https://github.com/badrallehyani
- Twitter/X: https://x.com/BadrLehyaniDev
- LinkedIn: https://www.linkedin.com/in/badr-al-lehyani-610029244/

---

## License

This project was developed as part of an academic and research initiative focused on intelligent, privacy-preserving file management systems.
