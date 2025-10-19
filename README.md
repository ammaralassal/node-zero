# Node_Zero – Custom Computer Part Picker


An interactive web app that allows users to assemble custom PC builds by selecting compatible components inspired by PCPartPicker. Built using React, Django, and MongoDB, and deployed with Docker on AWS.

## Features

- **Browse Components**: View a wide range of CPUs, GPUs, motherboards, RAM, SSDs, PSUs, and cases.
- **Compatibility Engine**: Only shows compatible parts based on user selections.
- **Custom Build Mode**: Interactive wizard for building a PC from scratch.
- **Save Builds**: Authenticated users can save and revisit builds.
- **User Auth**: Secure JWT-based login and registration.
- **API Backend**: RESTful Django API serving PC part data and user builds.
- **Deployment**: Fully containerized with Docker and hosted on AWS.


## Tech Stack

### Frontend
- **React** with **TypeScript**
- **TailwindCSS** + **ShadCN UI**
- **Next.js**

### Backend
- **Django REST Framework**
- **MongoDB** (MongoEngine)

### DevOps / Deployment
- **Docker**
- **AWS ECS / Fargate**
