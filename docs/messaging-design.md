Kafka Topics

post.created

post.liked

user.followed

behavior.event

Event Structure Example
{
  "eventId": "uuid",
  "type": "POST_CREATED",
  "userId": 123,
  "postId": 456,
  "timestamp": 17123123
}
Consumers

TrendingConsumer

BehaviorAnalyticsConsumer

RecommendationEngine