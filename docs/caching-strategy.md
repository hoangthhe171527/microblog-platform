Cache Types
1. Hot Post Cache

Key: post:{id}

TTL: 24h

Invalidate on update/delete

2. Feed Cache

Key: feed:{userId}

TTL: 30s

3. Trending Cache

Key: trending:posts

TTL: 2m

Cache Invalidation Rules

Write-through for posts

Delayed invalidation for feed cache