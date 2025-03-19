# Learn Dinamic Routes with Next.JS 15 
create Dashboard Movie-infomation , Key Learning include use Dinamic Routes

## ✨ Feature 
- Responsive layout
- Nested Route for navigation ( dinamic by movie id )
- use Link to navigate

## 🔑 Key Learnings
- using **Dinamic Routes**  : href = {`/movies/${ movie.id }`}
- Create  Dinamic Route Folder : [id]
- /app
    /movies
      /[id]  <-- Dynamic route folder
        page.tsx  <-- Renders each dynamic page
- When create [id].tsx : Next.JS provides Route Parameters inside **params** ( object )

## 🛠️ Tech Stack
- React
- TailwindCSS
- Next.JS
- TypeScript
