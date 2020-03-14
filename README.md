# One-liner-collection
## extracts all API endpoints from AngularJS & Angular javascript files ##
curl -s URL | grep -Po “(\/)((?:[a-zA-Z\-_\:\.0–9\{\}]+))(\/)*((?:[a-zA-Z\-_\:\.0–9\{\}]+))(\/)((?:[a-zA-Z\-_\/\:\.0–9\{\}]+))” | sort -u
