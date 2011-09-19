# Useful Bits and Bobs for Developing Boxee Apps

## Automated Packaging

Download the build script (GreatBoxee.Builds\package.build) and put in a folder inside your app in a folder called "Build".

Create 3 descriptor files in your app root, one for each location the app will exist or be deployed to. They must have these names (conventions!).

* descriptor.xml - the version of the app that your developing in your current apps folder on your dev machine. This will have the test-app tag in it. eg App Id = greatboxee.myvids
* descriptor.beta.xml - the version of the app that will be deployed to your custom repository eg App Id = greatboxee-beta.myvids
* descriptor.prod.xml - the version of the app that will be deployed to the official Boxee repository eg App Id = myvids

Full details here on how to use the packaging script
[http://www.greatboxee.com/index.php/2011/04/04/automate-your-app-packaging/]

The Examples folder contain a full working example.

# Thumbnail Template
A photoshop template for creating app thumbnails. With a sash for each environment type (dev, beta etc) to distinguish between the environments the app is from.