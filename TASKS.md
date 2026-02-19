# GenZ Cap Store - Implementation Tasks

A modern e-commerce store for caps and hats targeting Gen Z audience, built with Next.js and Supabase.

---

## Phase 1: Project Setup & Configuration

- [ ] **Task 1.1**: Initialize Next.js project with TypeScript and Tailwind CSS
  - Files: `package.json`, `next.config.js`, `tsconfig.json`, `tailwind.config.ts`, `postcss.config.js`
  - Create basic project structure with `app/` directory

- [ ] **Task 1.2**: Set up project folder structure
  - Files: Create directories `app/`, `components/`, `lib/`, `types/`, `public/images/`, `supabase/migrations/`

- [ ] **Task 1.3**: Configure environment variables template
  - Files: `.env.local.example` with Supabase configuration

---

## Phase 2: Database Schema & Supabase Setup

- [ ] **Task 2.1**: Create database migration for products table
  - Files: `supabase/migrations/001_create_products.sql`
  - Table: products (id, name, description, price, image_url, category, stock, created_at, updated_at)

- [ ] **Task 2.2**: Create database migration for cart functionality
  - Files: `supabase/migrations/002_create_cart.sql`
  - Tables: cart_items, orders, order_items

- [ ] **Task 2.3**: Set up Supabase client configuration
  - Files: `lib/supabase.ts` - Initialize Supabase client with env vars

---

## Phase 3: Core Components

- [ ] **Task 3.1**: Create layout and global styles
  - Files: `app/layout.tsx`, `app/globals.css`
  - Include navigation, footer, and global styling

- [ ] **Task 3.2**: Create navigation component
  - Files: `components/Navbar.tsx`
  - Logo, nav links, cart icon with count

- [ ] **Task 3.3**: Create product card component
  - Files: `components/ProductCard.tsx`
  - Display product image, name, price, add to cart button

- [ ] **Task 3.4**: Create cart components
  - Files: `components/CartDrawer.tsx`, `components/CartItem.tsx`
  - Slide-out cart drawer with item management

---

## Phase 4: Pages & Routing

- [ ] **Task 4.1**: Create home page with hero and product grid
  - Files: `app/page.tsx`
  - Hero section, featured products, categories

- [ ] **Task 4.2**: Create products listing page
  - Files: `app/products/page.tsx`
  - Filter by category, sort options, product grid

- [ ] **Task 4.3**: Create single product detail page
  - Files: `app/products/[id]/page.tsx`
  - Product images, details, add to cart functionality

- [ ] **Task 4.4**: Create cart page
  - Files: `app/cart/page.tsx`
  - Full cart management, checkout button

---

## Phase 5: State Management & Hooks

- [ ] **Task 5.1**: Create cart context/provider
  - Files: `context/CartContext.tsx`
  - Global cart state management

- [ ] **Task 5.2**: Create custom hooks
  - Files: `hooks/useCart.ts`, `hooks/useProducts.ts`
  - Data fetching and cart operations

---

## Phase 6: Types & Utilities

- [ ] **Task 6.1**: Create TypeScript types
  - Files: `types/index.ts`
  - Product, CartItem, Order interfaces

- [ ] **Task 6.2**: Create utility functions
  - Files: `lib/utils.ts`
  - Format price, calculate totals

---

## Phase 7: Sample Data & Assets

- [ ] **Task 7.1**: Add sample product data
  - Files: `lib/sample-data.ts`
  - Seed data for caps/products

- [ ] **Task 7.2**: Add placeholder images
  - Files: `public/images/` - cap placeholder images

---

## Phase 8: Final Polish

- [ ] **Task 8.1**: Create loading and error states
  - Files: `app/loading.tsx`, `app/error.tsx`

- [ ] **Task 8.2**: Add responsive design improvements
  - Files: Update all component files for mobile responsiveness

- [ ] **Task 8.3**: Update README with full documentation
  - Files: `README.md`

---

## Progress

- **Completed**: 0/18 tasks
- **In Progress**: 0/18 tasks
- **Remaining**: 18/18 tasks