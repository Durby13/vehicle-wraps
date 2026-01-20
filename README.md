# SAESRPG - Custom Vehicle Wraps

This is the community vehicle wrap repository.

This repository allows players to upload and manage their custom vehicle wraps for use within **SAESRPG**.

## ℹ️ Information about wraps
Custom wraps can be used by organisations and players with donation points.

If you need further information, it can be found here: https://github.com/saesrpg/vehicle-wraps/wiki

## 📂 Repository Structure

To keep things organised, wraps are stored using a specific folder hierarchy.

### The Path
All wraps must reside in the following path:
`RPGvehicleWrapAssets/wraps/custom/users/<your-username>/<wrap-name>/`

### Example
If your username is **ronseal** and this is your first wrap, your folder structure will look like this:

```text
RPGvehicleWrapAssets/
└── wraps/
    └── custom/
        └── users/
            └── ronseal/       <-- Your Username
                └── 001/       <-- Sequential Number
                    ├── wrap.png
                    └── allowed.txt (Optional)
```
## 🚀 How to Add a New Wrap
Follow these steps to contribute your custom wrap:

### Fork the Repository
Click the "Fork" button in the top-right corner of this page to create your own copy of the repository.

### Create the Directory
Inside your forked repo, navigate to `RPGvehicleWrapAssets/wraps/custom/users/`.
* If you are new: Create a folder with your exact username.
* Inside your user folder: Create a new folder using the next available sequential number (e.g., `001`).
* Example: If `001` and `002` already exist, name your new folder `003`.

### Add Your Files
Upload the following files into your specific numbered folder:
* The Wrap (wrap.png)
    * It must be in PNG format.
    * The file must be named wrap.png.

* Access Control (allowed.txt)
    * This is optional; however, if you want to restrict people who can use this wrap, then create this file.
    * List the SAES username of allowed users inside the file (one per line).

#### Example (allowed.txt):
```text
ronseal
nanobob
brophy
```
If this file is omitted, the wrap may be accessible publicly.

### Commit and Push
Commit your changes to your forked repository. Use a descriptive message, for example: Added custom wrap: ronseal/001.

### Create a Pull Request (PR)
Go back to the original SAESRPG/vehicle-wraps repository.

Click Pull Requests > New Pull Request.

Select your fork and submit the PR for review.