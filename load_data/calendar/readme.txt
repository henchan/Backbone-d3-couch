Bulk load sample calendar data into couchdb:

export DB=http://127.0.0.1:5984/crashes
curl -H "Content-Type: application/json" -d @calendar.bulk.json -X POST $DB/_bulk_docs
