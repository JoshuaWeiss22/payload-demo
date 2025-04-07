# Payload Demo App

This is a demo application built with [Payload CMS](https://payloadcms.com/) and [Next.js](https://nextjs.org/). It demonstrates how to integrate Payload CMS into a modern web application, including features like user authentication, media management, and API routes.

## Features

- **CMS Integration**: Powered by Payload CMS for content management.
- **Next.js**: Server-side rendering and API routes.
- **MongoDB**: Database integration using the `@payloadcms/db-mongodb` adapter.
- **Authentication**: Built-in user authentication with Payload.
- **Media Management**: Upload and manage media files.
- **GraphQL API**: GraphQL playground and API integration.
- **Customizable**: Easily extendable collections and configurations.

## Project Structure

```plaintext
src/
├── app/                # Next.js app directory
│   ├── (payload)/      # Payload CMS admin and API routes
│   ├── (frontend)/     # Frontend pages and styles
├── collections/        # Payload collections (e.g., Users, Media)
├── [`src/payload.config.ts`](src/payload.config.ts )   # Payload CMS configuration
├── [`src/payload-types.ts`](src/payload-types.ts )    # Auto-generated Payload types
```
