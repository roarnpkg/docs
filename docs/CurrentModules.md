# Importing your current modules to Roarn

You probably already created a bunch of modules outside of Roarn. You are so cool! Now its time to make your modules more accessible by importing them to Roarn.

You may find it complicated, but with these steps it will be a piece of cake.

## Step 1

Create a `roarn.json` file at the root of your project. If your project was not made with the Rojo structure you will have to transfer it before continuing.

## Step 2

Now that you have your `roarn.json` file, lets add some content to it to make your package what its supposed to be.

```json
{
  "name": "yourPackageName EX: (roarn_package)",
  "version": "theCurrentVersionOfYourPackage EX: (1.0.0)",
  "description": "a brief description of your package"
}
```

These are the required fields for your `roarn.json` file. Your package will most likely not have any dependencies on it so you don't have to worry about that.

## Step 3

Its now time to publish your package! Use,

```bash
roarn publish
```

to publish your package to the registry. If it all goes as planned you should get that sweet success message at the end. Once you go to your Roarn account you will see your package there.

## Need help?

Refer to :point_right: [Assistance](./Community.md) so our team can help you out.
