

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)



## <a name="introduction">🤖 Introduction</a>

Developed a state-of-the-art AI-driven SaaS platform specialized in image enhancement that integrates advanced image processing technologies, secure payment systems, and sophisticated image search capabilities. It includes a wide array of AI functionalities such as image restoration, recoloring, object removal, creative filling, and background elimination. 



## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- TypeScript
- MongoDB
- Clerk
- Cloudinary
- Stripe
- Shadcn
- TailwindCSS

## <a name="features">🔋 Features</a>

👉 Secure User Management: Implement robust security for user access through registration, login, and protected routes.

👉 Image Community Hub: Navigate through user-shared image transformations with pagination for easy browsing.

👉 Enhanced Image Discovery: Quickly locate images by their content or specific objects within them.

👉 Revitalize Images: Effortlessly restore the quality of old or damaged photos.

👉 Creative Image Recoloring: Easily modify image colors or object hues according to preference.

👉 Seamless Generative Image Filling: Autonomously fill in missing parts of images.

👉 Precise Object Elimination: Remove undesired objects from images with accuracy.

👉 Effortless Background Removal: Isolate subjects from their backgrounds smoothly.

👉 Image Downloading: Conveniently save and distribute AI-enhanced images.

👉 Insightful Transformation Details: Obtain information on each image's transformation process.

👉 Transformation Control: Manage the deletion and modification of image transformations.

👉 Flexible Credits System: Utilize a credits mechanism for accessing image transformation features.

👉 Personalized Profile Area: View your own transformed images and track credit balances.

👉 Credits Acquisition: Safely purchase credits through Stripe for continuous service.

👉 Adaptive Design: Enjoy a consistent, user-friendly experience across all devices, complemented by an intuitive interface and extensive features like code modularization and component reusability.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/kunal-05/VisionCraft.git
cd VisionCraft
```

**Installation**

Install the project dependencies using npm:

```bash
npm run dev
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
#NEXT
NEXT_PUBLIC_SERVER_URL=

#MONGODB
MONGODB_URL=

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#CLOUDINARY
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

#STRIPE
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

Replace the placeholder values with your actual respective account credentials. You can obtain these credentials by signing up on the [Clerk](https://clerk.com/), [MongoDB](https://www.mongodb.com/), [Cloudinary](https://cloudinary.com/) and [Stripe](https://stripe.com)

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

