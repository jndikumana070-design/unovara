# UNOVARA API Documentation

## Authentication

### Register
POST /api/auth/register

### Login
POST /api/auth/login

### Logout
POST /api/auth/logout

---

## Users

### Get Profile
GET /api/users/{id}

### Update Profile
PUT /api/users/{id}

---

## Posts

### Get Posts
GET /api/posts

### Create Post
POST /api/posts

### Like Post
POST /api/posts/{id}/like

### Comment
POST /api/posts/{id}/comment

---

## Messages

### Send Message
POST /api/messages

### Get Conversations
GET /api/messages

---

## Opportunities

### Get Opportunities
GET /api/opportunities

### Create Opportunity
POST /api/opportunities

### Update Opportunity
PUT /api/opportunities/{id}

### Delete Opportunity
DELETE /api/opportunities/{id}
