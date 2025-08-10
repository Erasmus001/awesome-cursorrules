# Next.js App Router Enterprise Scale Development Rules

## Description

This `.cursorrules` file provides comprehensive guidelines for building medium-to-high scale applications using Next.js App Router with modern enterprise-level best practices. It covers the complete technology stack including TypeScript, Mantine UI, Shadcn UI, and TanStack Query.

## Features

- **Complete Technology Stack Coverage**: Next.js 15+, TypeScript, Mantine UI, Shadcn UI, TanStack Query
- **Enterprise Architecture Patterns**: Server-first approach, route groups, parallel routes, intercepting routes
- **Performance Optimization**: Streaming, caching strategies, code splitting, image optimization
- **State Management**: TanStack Query for server state, React hooks for client state
- **UI Component Architecture**: Comprehensive examples for both Mantine UI and Shadcn UI
- **Type Safety**: Extensive TypeScript patterns, interfaces, and utility types
- **Security Best Practices**: Input validation, authentication, authorization, security headers
- **Testing Strategy**: Unit testing, integration testing, and testing utilities
- **Error Handling**: Global error handling, error boundaries, and monitoring
- **Deployment & DevOps**: Environment configuration, build optimization, monitoring

## Use Cases

- Enterprise applications requiring scalability and maintainability
- Applications with complex UI requirements and state management
- Projects requiring strict type safety and code quality
- Applications needing comprehensive error handling and monitoring
- Projects requiring modern React patterns and best practices

## Technology Stack

- **Framework**: Next.js 15+ with App Router
- **Language**: TypeScript with strict configuration
- **UI Libraries**: Mantine UI (complex components) + Shadcn UI (base components)
- **State Management**: TanStack Query (server state) + React hooks (client state)
- **Styling**: Tailwind CSS for utility-first styling
- **Authentication**: NextAuth.js with multiple providers
- **Database**: Prisma ORM with PostgreSQL/MySQL
- **Validation**: Zod for runtime type validation
- **Testing**: Jest + React Testing Library
- **Monitoring**: Sentry for error tracking, analytics for performance

## Key Principles

1. **Server-First**: Use Server Components by default, Client Components only when necessary
2. **Performance**: Implement streaming, parallel data fetching, and proper caching with TanStack Query
3. **Type Safety**: Use TypeScript with strict configuration and comprehensive type definitions
4. **UI Consistency**: Leverage Mantine UI for complex components and Shadcn UI for base components
5. **State Management**: Use TanStack Query for server state and React's built-in state for client state
6. **Security**: Validate all inputs, implement proper authentication, and use security headers
7. **Testing**: Write comprehensive tests for components, API routes, and integration
8. **Monitoring**: Track performance metrics and application errors
9. **Code Quality**: Follow consistent coding standards and use proper tooling
10. **Documentation**: Document all components, APIs, and architectural decisions
11. **Scalability**: Design for horizontal scaling and implement proper error handling
12. **Maintainability**: Use clear naming conventions and modular architecture

## Author

This comprehensive set of rules was curated to provide enterprise-level development guidelines for Next.js App Router applications, incorporating modern best practices and tools for building scalable, maintainable applications.

## License

This file is part of the Awesome CursorRules collection and follows the same license as the parent repository.