# Contributing to Social media

We are always welcome to contribute to this project!

## Code commit

### 🧩 Adding a New Social Media Platform Data
```
git commit -m "Add <SOCIAL_MEDIA_PLATFORM_NAME>"
```
💡Note: When you add a new platform data, please update _number of platforms_ in `README.md` as well:)

### 🧩 Updating Social Media Platform Data
**We recommend using these commit templates:**
```
git commit -m "Update offical name: <SOCIAL_MEDIA_PLATFORM_NAME>"

git commit -m "Update offical link: <SOCIAL_MEDIA_PLATFORM_NAME>"

git commit -m "Add new tag(s): <SOCIAL_MEDIA_PLATFORM_NAME>"

git commit -m "Delete tag(s): <SOCIAL_MEDIA_PLATFORM_NAME>"
```

**Social media platform data structure:**
```
"cara": {
  "name": "Cara",                   // Official name
  "link": "https://cara.app/",      // Official link
  "tags": ["art"]                   // Tags
}
```

💡Note: When you add/update tag data in `social_media.json`, please search if it's a new one in `tags.json`. If you can't find it there, please update `tags.json` as well:)