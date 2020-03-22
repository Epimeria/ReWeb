## Front-end
[Landing URL](https://reddit.invokedata.org)

### index.html
Search bar

FAQ

Copyright

Apache Licence

Leaderboard

### user.html
Graphs mentioned in readme.md

multi-tab

## Back-end
Golang
SQL

### Procedure
#### Search
1. Username submitted
2. Added to queue
3. Profile history is scraped
4. Profile history is parsed
5. Metadata & full scrape is stored in SQL
6. Permanent URL is created for that scrape

#### Access old search
1. User accesses link
2. Unique ID is searched in SQL DB
3. If found, JSON is returned to the user. If not, 404
