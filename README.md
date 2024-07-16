# Documentation

If you want to contribute to the documentation, you can find the source files in the `docs` directory. The documentation is written in Markdown and built using [Retype](https://retype.com/).

## Running documentation locally

To run the documentation locally, you need to run the following commands:

1. Install Retype CLI globally:

```bash
# Using bun
bun add -g retypeapp

# Using npm
npm install -g retypeapp

# Using yarn
yarn global add retypeapp
```

2. Run the following command in the root directory of the repository:

```bash
retype start
```

This will start a local server and open the documentation in your default browser. Every time you make a change to the documentation, the server will automatically rebuild the documentation and refresh the page.
