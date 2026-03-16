Full-Stack MERN Final Project Specification Document


1. Project Overview
Project Name: [To be decided]

Short Description:
A gym management platform where members can track their remaining sessions, view membership expiration, and share workout programs. Gym owners can manage memberships, create and assign programs, and sell products like protein, creatine, and gym accessories directly through the platform.



2. Group Members
Name	Email	GitHub Profile
Neil	neilberguiga2017@gmail.com	Neil01e


3. Selected Theme
Task Management Application

E-Commerce Website

Real-time Chat Application

Book Recommendation App

MERN Application



4. Features & Functionalities
Frontend Features

User authentication (Signup/Login with JWT)

Role-based dashboards (Member, Trainer, Gym Owner, Admin)

Member dashboard:

View remaining sessions count

Membership expiration countdown

List of received workout programs

Share programs via link

QR code for gym check-in

Browse and purchase products (protein, creatine, accessories)

Trainer dashboard:

Create workout programs (exercises, sets, reps, video links)

Assign programs to members

Gym Owner dashboard:

Manage memberships (create, edit, delete)

Assign memberships to members

Manually add sessions or extend expiration

View all members and their session status

Manage product inventory (add, edit, delete products)

View product orders and update status

Admin dashboard:

Manage users and gyms

Platform overview

Product store page with categories (supplements, accessories, etc.)

Shopping cart and order management

Responsive UI with Tailwind CSS and DaisyUI

Backend Features

User authentication with JWT and role-based access control

CRUD operations for:

Users (members, trainers, owners, admin)

Gyms

Memberships

Workout programs

Products

Orders

Session tracking system (decrement on check-in)

QR code generation and verification for check-ins

Program sharing logic (generate shareable links)

Product inventory management

Order processing system

Database models with Mongoose

Input validation with Zod

Additional Features

Email notifications (welcome email, membership expiring soon, order confirmation)

Program completion tracking

Basic analytics for gym owners (popular classes, product sales)

Mobile-friendly responsive design

Product reviews and ratings

Stock management (low stock alerts)



5. Technologies Used
Frontend: Next.js (TypeScript), Tailwind CSS 4, DaisyUI, TanStack Query, Zod, React Hook Form

Backend: Node.js, Express.js, TypeScript, MongoDB with Mongoose, JWT, Bcrypt

Database: MongoDB Atlas

Additional Libraries/Tools:

QR code generator (qrcode.react)

Cloudinary (for image uploads)

Dotenv, Nodemon




6. Additional Notes
Development will start with backend first, then frontend integration

Points system and payment integration will be considered for future phases

Multi-gym support can be added later as platform grows

Focus on core membership tracking, program sharing, and product sales for initial release

Mobile-responsive design from the start

Product section will include supplements, accessories, and gym gear
