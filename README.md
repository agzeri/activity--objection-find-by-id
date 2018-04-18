# Objection

## Retrieve a single record using the id property

### Indications

#### (1) Create a route to get a single Tweet. It could be like this: `/tweets/:tweetId`

**Don’t forget how to get a parameter from the request object. You’ll need it to select information related to that tweet from database.**

#### (2) Read [Objection Docs](https://vincit.github.io/objection.js/) to see how can you interact with your Model and ask a single record to our database.

### Test

#### (1) Go to your Postman app, and make a GET request to: `/tweets/1`

#### (2) It must show you the data related to Tweet with id = 1

```json
{
  "id": "...",
  "description": "...",
  "createdAt": "...",
  "likes": "...",
  "retweets": "..."
}
```
