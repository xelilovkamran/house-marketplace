# House Marketplace

## Features

Here are some of the current features that Property Pulse has:

- [ ] User authentication with Google & Next Auth
- [ ] User authorization
- [ ] Route protection
- [ ] User profile with user listings
- [ ] Property Listing CRUD
- [ ] Property image upload (Multiple)
- [ ] Property search
- [ ] Internal messages with 'unread' notifications
- [ ] Photoswipe image gallery
- [ ] Mapbox maps
- [ ] Toast notifications
- [ ] Property bookmarking / saved properties
- [ ] Property sharing to social media
- [ ] Loading spinners
- [ ] Responsive design (Tailwind)
- [ ] Custom 404 page

Property Pulse uses the following technologies:

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)
- [NextAuth.js](https://next-auth.js.org/)
- [React Icons](https://react-icons.github.io/react-icons/)
- [Photoswipe](https://photoswipe.com/)
- [Cloudinary](https://cloudinary.com/)
- [Mapbox](https://www.mapbox.com/)
- [React Map GL](https://visgl.github.io/react-map-gl/)
- [React Geocode](https://www.npmjs.com/package/react-geocode)
- [React Spinners](https://www.npmjs.com/package/react-spinners)
- [React Toastify](https://fkhadra.github.io/react-toastify/)
- [React Share](https://www.npmjs.com/package/react-share)

## Getting Started

### Prerequisites

- Node.js version 18 or higher
- MongoDB Atlas account and a cluster. Sign up and create a cluster at [MongoDB](https://www.mongodb.com/)
- Cloudinary account. Sign up at [Cloudinary](https://cloudinary.com/)
- Google console account. Sign up at [Google Cloud](https://console.cloud.google.com/)
- Mapbox account. Sign up at [Mapbox](https://www.mapbox.com/)

### `.env` File

Rename the `env.example` file to `.env` and fill in the following environment variables:

- Get your MongoDB connection string from your MongoDB Atlas cluster and add it to `MONGODB_URI`.
- Get your Google client ID and secret from your Google console account and add them to `GOOGLE_CLIENT_ID` and `GOOGLE_CLIENT_SECRET`.
- Add a secret to `NEXTAUTH_SECRET`. You can generate with the following command:
  ```bash
  openssl rand -base64 32
  ```
- Get your Cloudinary cloud name, API key, and API secret from your Cloudinary account and add them to `CLOUDINARY_CLOUD_NAME`, `CLOUDINARY_API_KEY`, and `CLOUDINARY_API_SECRET`.
- Get your Mapbox token from your Mapbox account and add it to `NEXT_PUBLIC_MAPBOX_TOKEN`.
- Get your Google Geocoding API key from your Google console account and add it to `NEXT_PUBLIC_GOOGLE_GEOCODING_API_KEY`.

### Install Dependencies

```bash
npm install
```

### Run the Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
