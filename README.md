# Chronicle - Travel Diary

A beautiful and personal travel diary application to document your journeys.

## Features

- **Create Entries**: Document your travels with stories, dates, and locations.
- **View Diary**: Browse through your past travel experiences.
- **Edit & Update**: Keep your memories fresh by updating entries.
- **Delete**: Remove entries you no longer wish to keep.
- **Supabase Integration**: Secure data storage for your diary entries.

## Tech Stack

- **Frontend**: React, TypeScript, Vite
- **UI Framework**: Tailwind CSS, Shadcn UI
- **Database**: Supabase
- **Icons**: Lucide React

## Getting Started

1.  **Clone the repository**
    ```bash
    git clone <repository-url>
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Set up Environment Variables**
    Create a `.env` file in the root directory and add your Supabase credentials:
    ```env
    VITE_SUPABASE_URL=your_supabase_url
    VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
    ```

4.  **Run the development server**
    ```bash
    npm run dev
    ```

## Building for Production

```bash
npm run build
```

## License

MIT
