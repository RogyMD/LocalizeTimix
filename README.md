# Timix Translations Repository

Welcome to the Timix Translations repository!  
Your interest in helping translate Timix to make it accessible for users around the world is very much appreciated.

For more details about Timix, visit the [Timix page](https://rogy.app/timix).

Download Timix for free on [App Store](https://apps.apple.com/app/id6477807870).

---

## Supported Languages

Below is the list of languages currently supported along with their translation status:

| Language             | Status | Code    | Contributor |
| -------------------- | ------ | ------- | ----------- |
| English              | ✅      | en      | @rogymd     |
| Romanian             | ✅      | ro      | @rogymd     |
| Russian              | ✅      | ru      | @rogymd     |
| Spanish              | ✅      | es      | ChatGPT     |
| German               | ❌      | de      |             |
| French               | ❌      | fr      |             |
| Croatian             | ❌      | hr      |             |
| Italian              | ❌      | it      |             |
| Chinese (Simplified) | ❌      | zh-Hans |             |

*✅: Translation Complete*  
*❌ Translation In Progress*

If you'd like to add a new language or update an existing translation, please follow the instructions below.

---

## How to Add a New Translation (macOS Instructions)

1. **Install Xcode**  
   Make sure you have Xcode installed on your Mac. You can download it from the [Mac App Store](hhttps://apps.apple.com/app/xcode/id497799835).

2. **Clone the Repository**  
   Open Terminal and run:
   ```bash
   git clone https://github.com/RogyMD/LocalizeTimix.git
   ```

3. **Create a New Branch**

Create a branch with a name that includes the language identifier (for example, feature/de for German):

```
git checkout -b feature/de
```

4. **Open the Translations Folder**

In Finder, navigate to the cloned repository and locate the folder containing the translation files.

5. **Open app_strings.xcloc in Xcode**

Double-click the `app_strings.xcloc` file to open it in Xcode. This file displays all the localizable strings for the app.

6. **Review and Update Each File**

In Xcode, go through each file listed in the sidebar of the `app_strings.xcloc` window and add or update the translations for your language.

7. **Optional: Translate App Store Text**

If there are additional text files for the App Store listing, feel free to translate those as well.

8. **Commit Your Changes**

After completing the translations, commit your changes:

```
git add .
git commit -m "Add/update [LANGUAGE] translations"
```

9. **Push Your Branch**

Push your branch to the repository:

```
git push origin feature/de
```

10. **Create a Pull Request**

Go to your repository on GitHub and create a Pull Request from your branch. Please make sure you follow the checklist from the pull request.

11. **Review Process**

I will review your Pull Request, and if everything looks good, I’ll merge it. Your contribution will be added to the Timix contributors list!

---

**Questions or Issues**

If you encounter any issues or have questions about the translation process, please [open an issue](https://github.com/RogyMD/LocalizeTimix/issues) or contact me directly.

Thank you for helping make Timix accessible to users worldwide!
