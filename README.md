
## Instructions

### Prerequisites

> If you wish to run this app **without installing/running a database**, you can easily do so. Read more [here](https://github.com/choonkending/react-webpack-node/blob/master/docs/databases.md).

**Install MongoDB as your database**:

```bash
# Update brew formulae
brew update
# Install MongoDB
brew install mongodb
```

If you hate MongoDB with a passion and would like to see a postgresql example, check [this](https://github.com/choonkending/react-webpack-node/blob/master/docs/databases.md) out!

**Setup your mongoDB directory**

Note: Make sure you have the directory and its permissions setup (i.e. `/data/db`):
```bash
sudo mkdir -p /data/db
sudo chown -R `id -u` /data/db
```

**Run your mongoDB server**
```bash
mongod
```

### Build & Dev

**Installation**
```bash
# Install node modules - this includes those for production and development
# You only need to do this once :)
npm install
```

**Development**

```bash
# Starts the server with Hot Reloading
# Run webpack through webpack.config.dev.js
npm run dev


License
===============
MIT



Note:
------

1. As per requirement added static right side bar with default menus from top nav (this can be changed to fixed sidebar or scrollable if provided with detailed requirements.)
2. As per requirement added "Product Listing" . (Can be filled with required list of items based on detail requirements.)