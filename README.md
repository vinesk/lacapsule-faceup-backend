<img src="assets/faceup.png" alt="Face Up Logo" width="350"/>

# Face Up

**Face Up** is a full-stack mobile application that allows users to take photos and store them in an image gallery.

## Features

- **Camera Integration**: Take photos using the device's camera.
- **Image Gallery**: View and manage captured photos.
- **Cloud Storage**: Upload photos to Cloudinary for secure storage.
- **React Native & Expo**: Cross-platform mobile development.
- **TypeScript**: Enhanced code quality and developer experience.

## Tech Stack

**Frontend**: React Native, Expo, TypeScript  
**Backend**: Node.js, Express  
**Cloud Storage**: Cloudinary

## Repositories

- **Frontend**: [lacapsule-faceup-frontend](https://github.com/vinesk/lacapsule-faceup-frontend)
- **Backend**: [lacapsule-faceup-backend](https://github.com/vinesk/lacapsule-faceup-backend)

## Setup

### Frontend

1. Clone the frontend repo:

   ```bash
   git clone https://github.com/vinesk/lacapsule-faceup-frontend.git
   cd lacapsule-faceup-frontend
   ```

2. Install frontend dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file with the following:

   ```bash
   BACKEND_URL=https://your-backend-url
   ```

4. Start the frontend:

   ```bash
   npx expo start
   ```

5. Scan the QR code with Expo Go app on your iOS or Android device to see the app in action

### Backend

1. Clone the backend repo:

   ```bash
   git clone https://github.com/vinesk/lacapsule-faceup-backend.git
   cd lacapsule-faceup-backend
   ```

2. Install backend dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file with the following:

   ```bash
   CLOUDINARY_URL=your-cloudinary-url
   ```

4. Start the backend:

   ```bash
   npm run start
   ```

## Usage

- **Take Photos**: Use the camera screen to capture images.
- **View Gallery**: Browse and manage your captured photos.
- **Cloud Sync**: Photos are automatically uploaded to Cloudinary.

## License

MIT License. See the [LICENSE](./LICENSE) file for details.
