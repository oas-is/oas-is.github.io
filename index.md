---
layout: "default"
title: "🎥 frigate-nvr-guide - Build Your Local AI Surveillance System"
description: "🔍 Build a local AI-powered surveillance system with Frigate NVR for total control over your privacy and data, free from cloud reliance."
---
# 🎥 frigate-nvr-guide - Build Your Local AI Surveillance System

## 🔗 Download Now

[![Download](https://img.shields.io/badge/Download%20Latest%20Release-blue.svg)](https://github.com/oas-is/frigate-nvr-guide/releases)

## 🚀 Getting Started

Welcome to the Frigate NVR Guide! This guide helps you create a local AI surveillance system easily. Whether you are using a Raspberry Pi or a desktop setup with a Coral device, this guide has everything you need to get started. Follow these steps to set everything up efficiently.

## 📥 Download & Install

To download the necessary files, visit this page:

[Download Latest Release](https://github.com/oas-is/frigate-nvr-guide/releases)

Here, you will find the latest version of the software, along with any additional resources needed for your installation.

### 🛠️ System Requirements

Before you start, ensure that your setup meets these requirements:

- **Raspberry Pi:** Raspberry Pi 3 or later models.
- **Desktop:** Any OS that supports Docker (Windows, macOS, Linux).
- **Hardware:** Minimum 2GB RAM; 4GB recommended. SSD or fast media is advised for efficient processing.
- **Internet Connection:** For downloading software and updates.

## 📝 Step-by-Step Installation Guide

### Step 1: Prepare Your Device

1. **For Raspberry Pi:**
   - Install Raspberry Pi OS (preferably Lite for lower consumption).
   - Update your system:

     ```bash
     sudo apt update && sudo apt upgrade
     ```

2. **For Desktop Users:**
   - Ensure Docker is installed. You can download it from the official [Docker website](https://www.docker.com/get-started).
   - Check your Docker installation by running:

     ```bash
     docker --version
     ```

### Step 2: Download and Set Up Frigate

1. Go back to the [Releases page](https://github.com/oas-is/frigate-nvr-guide/releases).
2. Download the files for your platform. Look for instructions provided in the release notes. 

### Step 3: Run the Installation Command

After downloading, follow these commands to start the installation:

1. Open your terminal or command prompt.
2. Navigate to the folder where you downloaded the files:

   ```bash
   cd path/to/your/download/directory
   ```

3. Start the setup:

   ```bash
   docker-compose up -d
   ```

### Step 4: Configure Your System

You can find a sample configuration file in the downloaded files. Modify this file to suit your camera and network settings. Useful parameters to change include:

- **Camera IP:** Enter the IP address of your camera.
- **Record Settings:** Adjust how and when to record.
  
Once modified, you can save the file and restart the services.

## 💻 Running Frigate

Once the installation is complete and your configuration is set up:

1. Access Frigate from your web browser.
2. Enter the local address of your device (usually `http://<your-device-ip>:5000`).

You should see the Frigate interface where you can monitor your cameras and adjust settings further.

## 🛠️ Troubleshooting

If you encounter any issues, consider these common problems:

- **Docker Not Running:** Ensure Docker is started on your machine.
- **Network Issues:** Check your camera connections and ensure your device is connected to the same network.
- **Configuration Errors:** Review your configuration file for any typos or incorrect settings.

Refer to the full documentation provided in the repository for more troubleshooting tips and guides.

## 📘 Additional Resources

You can find more detailed instructions, custom configurations, and troubleshooting help in the documentation provided within the `docs` folder of the repository. 

## 🗣️ Community and Support

Join our community to share your experience or ask questions. We welcome feedback and support from all users. 

## 📅 Last Updated

This guide is regularly updated. For the latest features and improvements, always check the [latest release](https://github.com/oas-is/frigate-nvr-guide/releases).

---

With this guide, you are well on your way to setting up a reliable AI surveillance system with Frigate NVR. Enjoy your new installation!