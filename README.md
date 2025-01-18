# Pitchy

Pitchy is a platform where founders can list their startups and promote their vision and ideas. The project aims to connect entrepreneurs and showcase innovative ideas in a streamlined and user-friendly interface.

## Features

- **Live Content API**: Dynamically displays the latest startup ideas on the homepage using Sanity's Content API.
- **GitHub Authentication**: Users can log in easily using their GitHub accounts, implemented via NextAuth.
- **Pitch Submission**: Submit startup ideas with title, description, category, and multimedia links (images).
- **View Pitches**: Browse through submitted ideas with filtering options by category.
- **Pitch Details Page**: View detailed information for any pitch, including multimedia and description.
- **Profile Page**: Users can view a list of their submitted pitches.
- **Editor Picks**: Admins can highlight top startup ideas through the "Editor Picks" feature managed via Sanity Studio.
- **Views Counter**: Tracks the number of views for each pitch instead of using an upvote system.
- **Search Functionality**: Efficiently search and load pitches based on user input.
- **Minimalistic Design**: Clean and straightforward UI with only essential pages for ease of use.
- **Performance Optimization**: Implemented concepts of Partial Pre-Rendering (PPR) and Server-Side Rendering (SSR) for improved performance.
- **Parallel Fetching**: Used parallel fetching techniques to enable faster API calls.

## Technologies Used

- **Next.js 15**
- **React 19**
- **Sanity**
- **TailwindCSS**
- **ShadCN**
- **TypeScript**
- **NextAuth (GitHub provider)**

## Folder Structure
```
📦 Pitchy
├── app/
│   ├── (root)/
│   ├── api/
│   ├── fonts/
│   └── studio/
├── components/
│   └── ui/
├── hooks/
├── lib/
├── public/
└── sanity/
├── lib/
└── schemaTypes/
```
