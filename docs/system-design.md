Main Components
1. User Service

Register, Login, JWT auth

Profile, follow/unfollow

2. Post Service

CRUD posts, media upload

Like, comment

3. Feed & Recommendation Service

Personalized feed

Trending detection

4. Search Service

Fulltext search by hashtags, content, users

Scaling Strategy

API Gateway + Load balancer

Separate read/write DB (future)

Redis caching for hot posts