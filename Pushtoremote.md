Push: https://git-scm.com/docs/git-push
git push [--all | --branches | --mirror | --tags] [--follow-tags] [--atomic] [-n | --dry-run] [--receive-pack=<git-receive-pack>]
	 [--repo=<repository>] [-f | --force] [-d | --delete] [--prune] [-q | --quiet] [-v | --verbose]
	 [-u | --set-upstream] [-o <string> | --push-option=<string>]
	 [--[no-]signed | --signed=(true|false|if-asked)]
	 [--force-with-lease[=<refname>[:<expect>]] [--force-if-includes]]
	 [--no-verify] [<repository> [<refspec>…​]]

Method 1: Using the Visual Source Control Interface (Easiest)
If you prefer not to type commands, VS Code has excellent built-in Git integration:
1. Open Source Control: Click on the Source Control icon in the left activity bar (or press Ctrl + Shift + G).
2. Stage your changes: Hover over Changes and click the + (plus) icon to stage all modified files.
3. Commit your changes: Type your update message in the text box at the top and click the Commit button (or checkmark icon).
4. Push to the repository: Click the blue Sync Changes button that appears, or click the ... (More Actions) menu next to the commit area and select Push.

Command line: 
git add .
git commint -m "message"
git push

git push --set-upstream origin <branch>
git push -u origin <branch>

with different branch
git push -u origin <Source Branch>:<Target Branch>