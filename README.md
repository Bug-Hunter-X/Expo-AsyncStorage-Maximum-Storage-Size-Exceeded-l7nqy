# Expo AsyncStorage Maximum Storage Size Exceeded

This repository demonstrates a bug and its solution related to exceeding the maximum storage size limit in Expo's AsyncStorage. AsyncStorage is not designed for storing very large amounts of data.  Exceeding the limit can lead to unexpected behavior and app crashes. This example shows how to handle this scenario.

## Bug

The `bug.js` file contains code that attempts to store a large amount of data in AsyncStorage, resulting in an error.

## Solution

The `bugSolution.js` file demonstrates a solution using alternative storage mechanisms like SQLite or MMKV to handle larger data sets, preventing the AsyncStorage limit error.

## Setup

1. Clone the repository.
2. `npm install` or `yarn install`
3. Run the app using Expo Go.
