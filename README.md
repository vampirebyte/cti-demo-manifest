# CTI Yocto Meta-Layer Setup

## Introduction

This README provides instructions for setting up the CTI Yocto meta-layer using the default demo manifest.

## Requirements

Ensure you have the following installed on your system before proceeding:

- Git
- Repo tool
- A compatible Linux environment

## Instructions

Follow these steps to initialize and sync the repository using the default manifest file.

### Step 1: Initialize Repo

Run the following command to initialize the repo:

```sh
repo init -u git@github.com:vampirebyte/cti-demo-manifest.git -b feature/create-default-manifest
```

### Step 2: Sync Repositories with the Manifest

Once initialized, sync the repositories using:

```sh
repo sync -j12
```

This will download all necessary meta-layers and dependencies as specified in the manifest.

---

For any issues, please refer to the repository's issue tracker or documentation.
