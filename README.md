# Lumina Glass Theme for Home Assistant

A sleek, modern Glassmorphism theme inspired by the Lumina Energy Card design.

## 🚀 Installation

1. Make sure you have **HACS** installed.
2. Go to HACS -> Frontend -> 3 dots menu -> **Custom Repositories**.
3. Add this URL and select **Theme**.
4. Click Install.
5. Add the following to your `configuration.yaml`:
   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
