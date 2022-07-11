# PoorMansPocket
A NodeJS and ReactJS and Redis webapp to store articles I want to save

# Data Design
### Article
1. Tags
2. Title
3. Brief Overview
4. URL
5. Date Added
6. Date Modified
# Features
### Singular Data Operations
1. Create Article (POST)
2. Read Article (GET)
3. Update Article (PUT)
4. Delete Article (DEL)
### Bulk Data Operations
1. ~~Create Articles~~ I'm not planning to add more than one article at a time
2. Read Articles (GET)
3. ~~Update Articles~~ I'm not planning to update more than one article at a time
4. Delete Articles (DEL)
5. Sort Articles (GET with query args)
6. Filter Articles (GET with query args)
7. Paginate Articles (GET with query args)
8. Rename tag
9. Add tag to several articles
10. Delete tag from several articles
### Create Article
1. Add tag(s)
    - Enter existing tag
    - Create new tag
2. Copy/paste title from article
3. Write a brief overview of the article
4. Add the URL
    - Copy/paste URL
    - Upload a document and automatically save it in S3 and use the S3 URL as the article URL
5. When user hits "Save Article" button and the corresponding method 
