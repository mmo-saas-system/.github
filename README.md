Tiemtaphoa Organization
Multi-Service SaaS Platform for SMS Verification, Proxy Services & Messaging

Overview
Tiemtaphoa develops production-grade SaaS solutions for businesses and developers requiring temporary phone numbers, SMS verification services, proxy infrastructure, and cloud messaging capabilities. Our flagship product, MMO SMS System, provides a comprehensive platform integrating multiple third-party services through a unified API.

Core Products
MMO SMS System
A multi-tenant platform offering:

SMS Verification Services - Temporary phone numbers for OTP verification
Phone Number Rentals - Extended rentals with auto-renewal capabilities
Proxy Services - Residential and datacenter proxies
Cloud Messaging - Direct SMS/WhatsApp sending via Plivo integration
Payment Processing - Integrated Polar payment gateway
Reward System - Gamification with mini-games and points
Affiliate Program - Multi-tier referral system with commission tracking
Support System - Hierarchical ticket management
Technology Stack
Backend:

Laravel 12 (PHP 8.4)
PostgreSQL 16
MongoDB 7
Redis 7
Frontend:

Vite + TailwindCSS 4
Real-time updates via WebSockets (Laravel Reverb)
Infrastructure:

Docker & Docker Compose
Nginx + Supervisor
Queue-based job processing
Architecture Principles
Clean Architecture - Separation of concerns with Controllers → Services → Repositories → Models
Provider Abstraction - Pluggable adapters for third-party APIs (SMS Pool, Proxy-Cheap, Plivo)
State Machine Design - Immutable state transitions with comprehensive audit trails
Financial Integrity - MongoDB append-only transaction logs, balance verification
Real-time Capabilities - WebSocket broadcasting for instant updates
Microservices-Ready - Stateless services, horizontal scaling support
Key Features
High Performance - Redis caching, connection pooling, optimized database queries
Security-First - API token authentication, rate limiting, blacklist management
Admin Dashboard - Comprehensive user/order management and analytics
Background Processing - Queue workers for polling and async operations
Webhook Integration - Real-time status updates from providers
Multi-Provider Support - Flexible provider switching and failover
Scalable - Designed for horizontal scaling and high availability

Use Cases
Developers - Integrate SMS verification into applications
Marketing Teams - Bulk SMS/WhatsApp campaigns
QA Engineers - Test multi-account workflows with temporary numbers
Web Scrapers - Access proxies for data collection
Businesses - White-label SMS verification solutions
Project Stats
20+ Database Models
350+ API Routes
16+ Core Services
20+ Database Migrations
Full Docker Deployment Pipeline
Contributing
We follow:

PSR-12 coding standards
Repository pattern for data access
Service layer for business logic
Comprehensive testing with Pest
License
[Your License Here]

Contact
[Your Contact Information]

Built with care by the Tiemtaphoa Team
