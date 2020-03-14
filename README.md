# One-liner-collection
#### Extracts all API endpoints from AngularJS & Angular javascript files ####
<pre><code> curl -s URL | grep -Po “(\/)((?:[a-zA-Z\-_\:\.0–9\{\}]+))(\/)*((?:[a-zA-Z\-_\:\.0–9\{\}]+))(\/)((?:[a-zA-Z\-_\/\:\.0–9\{\}]+))” | sort -u <code><pre>
