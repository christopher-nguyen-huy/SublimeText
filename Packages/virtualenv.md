# Virtualenv
This package allows you to use a virtualenv for a python project.

- Create a sublime project and save it beside all the folders included in the project
- Create the virtualenv beside the project
- Edit the `.sublime-project` file and add this the virtualenv line like this
```
{
	"folders":
	[
		{
			"follow_symlinks": true,
			"path": "app"
		}
	],
	"virtualenv":"I:\\test\\aproject\\venv"
}
```
- Ctrl-B should now run the file with the python of the virtualenv