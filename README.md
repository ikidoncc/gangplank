# Steam Marketplace - Development Roadmap

**Objective:** Build a Steam-inspired marketplace platform to demonstrate knowledge in Java (Spring Boot), Angular, and modern software architecture.

# Sprint 0 - Project Infrastructure

## Objective

Set up the project environment and architecture.

### Tasks

- [ ] **0.1** Create monorepo
- [ ] **0.2** Create Spring Boot project
- [ ] **0.3** Create Angular project
- [ ] **0.4** Configure Docker Compose
- [ ] **0.5** Configure PostgreSQL
- [ ] **0.6** Configure Flyway migrations
- [ ] **0.7** Configure GitHub Actions
- [ ] **0.8** Configure Swagger/OpenAPI
- [ ] **0.9** Configure environments (development/production)
- [ ] **0.10** Configure Docker development environment

**Difficulty:** 🟢

---

# Sprint 1 - Authentication System

## Objective

Build the complete authentication and authorization system.

### Tasks

- [ ] **1.1** User registration
- [ ] **1.2** User login
- [ ] **1.3** JWT authentication
- [ ] **1.4** Refresh Token implementation
- [ ] **1.5** Logout functionality
- [ ] **1.6** Password recovery flow
- [ ] **1.7** Email verification
- [ ] **1.8** Google OAuth2 login
- [ ] **1.9** GitHub OAuth2 login
- [ ] **1.10** Role management (USER, ADMIN)
- [ ] **1.11** Angular route guards
- [ ] **1.12** Angular HTTP interceptors

**Difficulty:** 🟠

---

# Sprint 2 - User Profile

## Objective

Create user profile management.

### Tasks

- [ ] **2.1** Edit user profile
- [ ] **2.2** Avatar upload
- [ ] **2.3** Change password
- [ ] **2.4** User preferences
- [ ] **2.5** Login history tracking

**Difficulty:** 🟢

---

# Sprint 3 - Game Catalog

## Objective

Build the game marketplace catalog.

### Tasks

- [ ] **3.1** Game CRUD operations
- [ ] **3.2** Category CRUD operations
- [ ] **3.3** Developer CRUD operations
- [ ] **3.4** Publisher CRUD operations
- [ ] **3.5** Image upload system
- [ ] **3.6** Trailer upload system
- [ ] **3.7** Game tag system
- [ ] **3.8** Search functionality
- [ ] **3.9** Pagination
- [ ] **3.10** Sorting
- [ ] **3.11** Filtering system

**Difficulty:** 🟡

---

# Sprint 4 - Steam Library System

## Objective

Implement the user's game library.

### Tasks

- [ ] **4.1** Purchase game flow
- [ ] **4.2** User game library
- [ ] **4.3** Favorite games
- [ ] **4.4** Purchase history
- [ ] **4.5** Simulated game download

**Difficulty:** 🟡

---

# Sprint 5 - Shopping Cart

## Objective

Create the shopping cart system.

### Tasks

- [ ] **5.1** Add game to cart
- [ ] **5.2** Remove item from cart
- [ ] **5.3** Update cart items
- [ ] **5.4** Apply discount coupons
- [ ] **5.5** Cart persistence
- [ ] **5.6** Redis cache integration

**Difficulty:** 🟡

---

# Sprint 6 - Payment System

## Objective

Implement external payment integration.

### Tasks

- [ ] **6.1** Stripe integration
- [ ] **6.2** Checkout flow
- [ ] **6.3** Payment webhooks
- [ ] **6.4** Payment approval flow
- [ ] **6.5** Payment cancellation
- [ ] **6.6** Refund process

**Difficulty:** 🔴

---

# Sprint 7 - Messaging System

## RabbitMQ

## Objective

Implement asynchronous communication between services.

### Tasks

- [ ] **7.1** Configure RabbitMQ
- [ ] **7.2** Create exchanges
- [ ] **7.3** Create queues
- [ ] **7.4** Create message producers
- [ ] **7.5** Create message consumers
- [ ] **7.6** Implement retry mechanism
- [ ] **7.7** Implement Dead Letter Queue
- [ ] **7.8** Create PurchaseCompleted event
- [ ] **7.9** Create UserCreated event
- [ ] **7.10** Create PaymentApproved event

**Difficulty:** 🔴

---

# Sprint 8 - Email Notification System

## Objective

Build email communication flows.

### Tasks

- [ ] **8.1** Create HTML email templates
- [ ] **8.2** Registration email
- [ ] **8.3** Password recovery email
- [ ] **8.4** Purchase confirmation email
- [ ] **8.5** Promotional emails
- [ ] **8.6** Mailpit integration
- [ ] **8.7** SendGrid integration

**Difficulty:** 🟡

---

# Sprint 9 - Reviews and Ratings

## Objective

Allow users to review games.

### Tasks

- [ ] **9.1** Game reviews
- [ ] **9.2** Like reviews
- [ ] **9.3** Comments system
- [ ] **9.4** Review moderation
- [ ] **9.5** Report reviews

**Difficulty:** 🟡

---

# Sprint 10 - Wishlist

## Objective

Implement user wishlists.

### Tasks

- [ ] **10.1** Create wishlist
- [ ] **10.2** Price drop notifications
- [ ] **10.3** Share wishlist

**Difficulty:** 🟢

---

# Sprint 11 - Administration Panel

## Objective

Create administrative features.

### Tasks

- [ ] **11.1** Admin dashboard
- [ ] **11.2** User management
- [ ] **11.3** Game management
- [ ] **11.4** Category management
- [ ] **11.5** Coupon management
- [ ] **11.6** Reports generation

**Difficulty:** 🟠

---

# Sprint 12 - Observability

## Objective

Implement monitoring and system visibility.

### Tasks

- [ ] **12.1** Spring Actuator setup
- [ ] **12.2** Prometheus integration
- [ ] **12.3** Grafana dashboards
- [ ] **12.4** Structured logging
- [ ] **12.5** Application metrics

**Difficulty:** 🟠

---

# Sprint 13 - Caching Strategy

## Objective

Improve application performance.

### Tasks

- [ ] **13.1** Redis product caching
- [ ] **13.2** Redis category caching
- [ ] **13.3** Redis dashboard caching
- [ ] **13.4** Cache eviction strategies

**Difficulty:** 🟠

---

# Sprint 14 - Testing

## Objective

Create a reliable test suite.

## Backend

### Tasks

- [ ] **14.1** Unit tests
- [ ] **14.2** Integration tests
- [ ] **14.3** Testcontainers
- [ ] **14.4** MockMvc tests

## Frontend

### Tasks

- [ ] **14.5** Jasmine tests
- [ ] **14.6** Cypress end-to-end tests

**Difficulty:** 🟠

---

# Sprint 15 - Deployment

## Objective

Prepare the application for production.

### Tasks

- [ ] **15.1** Create Docker images
- [ ] **15.2** Production Docker Compose
- [ ] **15.3** Nginx reverse proxy
- [ ] **15.4** HTTPS configuration
- [ ] **15.5** Complete CI/CD pipeline
- [ ] **15.6** Deploy to VPS or Cloud

**Difficulty:** 🔴

---

# Sprint 16 - Advanced Features

## Objective

Implement additional marketplace features.

### Tasks

- [ ] **16.1** User chat system
- [ ] **16.2** Friends system
- [ ] **16.3** User invitations
- [ ] **16.4** Achievements system
- [ ] **16.5** Badges system
- [ ] **16.6** Item marketplace
- [ ] **16.7** Real-time notifications (WebSocket)
- [ ] **16.8** Game recommendation system
- [ ] **16.9** Activity auditing
- [ ] **16.10** Feature flags

**Difficulty:** 🔴

---

# Recommended Development Order

| Sprint | Priority |
|--------|----------|
| Sprint 0 | ⭐⭐⭐⭐⭐ |
| Sprint 1 | ⭐⭐⭐⭐⭐ |
| Sprint 2 | ⭐⭐⭐⭐ |
| Sprint 3 | ⭐⭐⭐⭐⭐ |
| Sprint 4 | ⭐⭐⭐⭐ |
| Sprint 5 | ⭐⭐⭐⭐ |
| Sprint 6 | ⭐⭐⭐⭐⭐ |
| Sprint 7 | ⭐⭐⭐⭐⭐ |
| Sprint 8 | ⭐⭐⭐ |
| Sprint 9 | ⭐⭐⭐ |
| Sprint 10 | ⭐⭐ |
| Sprint 11 | ⭐⭐⭐⭐ |
| Sprint 12 | ⭐⭐⭐ |
| Sprint 13 | ⭐⭐⭐ |
| Sprint 14 | ⭐⭐⭐⭐ |
| Sprint 15 | ⭐⭐⭐⭐⭐ |
| Sprint 16 | ⭐⭐⭐⭐⭐ |

---

# Technology Stack

## Backend

- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- JWT
- OAuth2
- RabbitMQ
- Redis
- Flyway
- PostgreSQL

## Frontend

- Angular
- Angular Material
- RxJS
- Signals
- Route Guards
- HTTP Interceptors

## Infrastructure

- Docker
- Docker Compose
- Nginx
- GitHub Actions
- Prometheus
- Grafana
- Mailpit
- MinIO
