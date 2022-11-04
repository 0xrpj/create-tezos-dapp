Hi. 

![Tezos](https://user-images.githubusercontent.com/56220537/199964017-900f6f09-1a28-42fe-ac67-edfec80bc5fc.png)

This repo will guide you to create / compile and deploy your smartpy contracts on tezos network.

Here's how you should start.

# Prerequisites (Don't skip this)
Install SmartPy CLI Tool: https://smartpy.io/docs/cli/
Now, you are good to go.

# Folder structure
```
|---bin (You should totally ignore this, its npmjs shit)
|---config
|------config.ts (Declaring config constants)
|---contracts
|------build (This is where your compiled Michaelson contracts are saved as json files.)
|------src (This is where you keep your smartpy contracts. 
|---scripts (This is where deploy script is saved, more if created in future.)
```

NOTE: A sample contract has been kept in the repo and compiled for reference.

# Commands you should know

## Compiling a contract
```
npm run compile [contractName]

Example: npm run compile counter
```
Note: Make sure the contract name is in lowercase and is inside the contract/src/ folder.

## Originating (Deploying) a contract
npm run deploy [contractName]

Example: npm run deploy counter
```
Note: Make sure the compiled contracts are inside the contract/build/ folder.
```

## More commands coming soon.
