# Next.js 15: Page is not a valid React component

This repository demonstrates a common error encountered when upgrading to Next.js 15 and using React 18. The error message is:  `Error: Page "/index" is not a valid React component. It should export a default component or a function that returns a valid React component.`

## Problem

The `pages/index.js` file is not correctly exporting a React component.

## Solution

Ensure your Next.js page exports a valid React component, either by default or as a function that returns a component. The bug is fixed by updating the export statement to explicitly export a function that returns a React component.

## Setup

1. Clone this repo.
2. Install dependencies: `npm install`
3. Run the app: `npm run dev`

The `bug.js` file shows the erroneous code. The `bugSolution.js` file demonstrates the correction. 