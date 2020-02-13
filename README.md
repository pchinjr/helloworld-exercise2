# Foundations / Hello World / Exercise 2 - Node HTTP Functions

1. Initialize with node

To create an HTTP function with Node, open a terminal window and run the following command:

```bash
arc init --runtime node ./my-node-app
```

You should see the terminal output:

```bash
⚬ Create Bootstrapping new Architect project
  | Project name .. my-node-app
  | Creating in ... /my-node-app
✓ Create Created Architect project manifest (.arc)
✓ Create Created new project files in src/http
✓ Create Done!
```

2. Create a `package.json` file

Change directories to the new `my-node-app` directory and run the following commands. The `--yes` flag will automatically populate `package.json` with information from the directory.

```bash
cd my-node-app
npm init --yes
```

3. Install the npm package dependencies

```bash
npm install @architect/sandbox
```

5. Add a start script to `package.json`

```bash
  "start": "arc sandbox"
```

6. Start the server

To start the server using npm, run the following command:

```bash
npm start
```

7. Preview in browser

Visit [`http://localhost:3333`](http://localhost:3333) in your web browser to preview your Node application.