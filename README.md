# Book Inventory System

Demo: https://next-books-search.vercel.app

This is a book inventory app built with Next.js, Drizzle, and PostgreSQL. The database contains over 2,000,000 books from Goodreads. [Full dataset here](https://mengtingwan.github.io/data/goodreads.html).

## Database Setup

This is currently using a Postgres extension called `unaccent` to remove accents from the book titles. This also uses the pgvector extension to use Postgres as a vector store. To install these extensions, run the following command on your database:

```clone

```
