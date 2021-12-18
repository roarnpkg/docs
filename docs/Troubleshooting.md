### No version set for command roarn (when using asdf version manager)

Create a `.tool-versions` file, and add the version of Node.js that you desire.

### roarn_modules is not a valid member of ReplicatedStorage

If you get this error it probably means you did not add the roarn_modules path to the `default.project.json` file.

Go to that file, and replace the **ReplicatedStorage** part to this:

```json
"ReplicatedStorage": {
			"$className": "ReplicatedStorage",
			"Common": {
				"$path": "src/shared"
			},
			"roarn_modules": {
				"$path": "roarn_modules"
			}
		},
```
