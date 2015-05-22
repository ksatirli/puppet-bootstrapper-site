# Code Checking Toolkit for Codecademy

This repository contains a collection of tools useful for checking snippets from sites like [Codecademy](http://codecademy.com/).

# Installation

To get started with this toolbox, carry out the following steps:

1.) Make sure you have [Node](http://nodejs.org/) installed. You can verify this by starting `Terminal.app` or any other shell emulator like PuTTY and executing the following command:

```
node --version
```

This should tell you the version you are running on. The result will likely be along the lines of `v0.12.01`.

If the above command gives you an error, follow the installation instructions on the `Node.js` site.

2.) Clone this Git repository using `Terminal.app` or any other shell emulator like PuTTY and executing the following command:

```
git clone https://bitbucket.org/ksatirli/codechecker.git
```

This will _clone_ the contents of the repository into a sub-directory of the current directory you are in.

3.) Install the required Node modules using `Terminal.app` or any other shell emulator like PuTTY and executing the following command:

```
cd codechecker

npm install
```

The `npm install` step takes a bit of time to download and install all associated modules. Be patient.

# Usage

To test your snippet, create a file with the `.js` extension and save it in the root of the repository then run the check using the `npm test` action using `Terminal.app` or any other shell emulator like PuTTY.
