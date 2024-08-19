# CowTopia Auto-Manager

CowTopia Auto-Manager is a Node.js application designed to automate various tasks in the CowTopia game. It helps manage multiple accounts, automatically purchase cows, upgrade factories, and claim offline profits.

## Features

- Multi-account management
- Automatic cow purchases
- Factory upgrades
- House upgrades
- Offline profit claiming
- Configurable auto-buy options
- Register Cowtopia [here](https://t.me/cowtopiabot/app?startapp=350874250)

## Prerequisites

Before running the CowTopia Auto-Manager, make sure you have the following installed:

- Node.js (version 12 or higher)
- npm (Node Package Manager)

## Installation

1. Clone this repository or download the source code.
2. Navigate to the project directory in your terminal.
3. Install the required dependencies by running:

```
npm install
```

## Configuration

1. Create a file named `data.txt` in the project root directory.
2. Add your CowTopia account tokens to `data.txt`, one per line.

Example `data.txt`:

```
query_id=
query_id=
```

## Usage

To start the CowTopia Auto-Manager, run the following command in your terminal:

```
node main.js
```