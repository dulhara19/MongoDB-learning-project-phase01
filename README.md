# MongoDB-learning-project-phase01

# MongoDB Commands Cheat Sheet

## 📌 Basic Commands
```sh
show dbs                     # List all databases
use your_database            # Switch to a database
show collections             # List collections in the current database
db.your_collection.find()    # Show all documents in a collection
db.your_collection.find().pretty()  # Show documents in a readable format
```

## 🔍 Querying Data
```sh
db.your_collection.find({ key: value })      # Find documents matching a condition
db.your_collection.findOne({ key: value })   # Find one document
db.your_collection.find().limit(5)           # Limit results to 5 documents
db.your_collection.find().sort({ key: 1 })   # Sort in ascending order (-1 for descending)
db.your_collection.countDocuments()          # Count documents in a collection
```

