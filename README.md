# NEXUS - AI-Powered Cloud Storage Platform

> *"Store Here, Access Anywhere - Powered by AI"*  

## Overview

Nexus is a modern, intelligent cloud storage platform that combines secure file storage with AI-powered analysis. Built with cutting-edge technologies, it offers seamless file management, smart content analysis, and universal accessibility through your Gmail account.

## Key Features

### **Secure Authentication**
- Gmail-based OAuth integration
- GitHub social login support
- Email/password authentication with Better Auth

### **Intelligent Cloud Storage**
- Secure file upload and management
- AWS S3-compatible storage with Cloudflare R2
- Real-time file organization and categorization

### **AI-Powered Analysis**
- **Document Intelligence**: Automatic text extraction and summarization
- **Image Recognition**: OCR, object detection, and color analysis
- **Smart Categorization**: AI-driven file organization and tagging
- **Content Search**: Search files by content, not just names

### **Advanced Dashboard**
- Interactive file management table
- Real-time upload progress tracking
- File analytics and insights
- Responsive design for all devices

### **Modern UI/UX**
- Beautiful animated cloud backgrounds
- Dark/light theme support
- Responsive design with Tailwind CSS
- Smooth animations with Framer Motion

## Tech Stack

### **Frontend**
- **Framework**: Next.js 15.5.2 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS 4.1.13 with custom animations
- **UI Components**: Radix UI primitives
- **Animations**: Framer Motion
- **State Management**: TanStack Query (React Query)
- **Forms**: React Hook Form with Zod validation

### **Backend & Database**
- **Runtime**: Node.js with TypeScript
- **Database**: PostgreSQL with Neon serverless
- **ORM**: Drizzle ORM with migrations
- **Authentication**: Better Auth with social providers

### **AI & Machine Learning**
- **Text Analysis**: Groq SDK for document processing
- **Image Processing**: Hugging Face Transformers
- **Text Extraction from PDF**: Used gemini-2.5-flash for PDF-Text Extraction
- **OCR**: Xenova Transformers for text extraction
- **File Parsing**: Mammoth (DOCX)

### **Cloud Infrastructure**
- **File Storage**: AWS S3 SDK with Cloudflare R2
- **CDN**: Cloudflare integration
- **Deployment**: Vercel-ready configuration

### **Development Tools**
- **Build Tool**: Turbopack (Next.js)
- **Linting**: ESLint with Next.js config
- **Package Manager**: Bun/PNPM support
- **Type Safety**: Full TypeScript coverage

## Project Structure

```
dampe/
├── src/
│   ├── app/               
│   │   ├── (auth)/          
│   │   ├── api/              
│   │   ├── dashboard/         
│   │   └── settings/           
│   ├── components/           
│   │   ├── dashboard/         
│   │   ├── ui/               
│   │   └── FileAnalysis.tsx  
│   ├── db/                  
│   ├── lib/                 
│   ├── hooks/                
│   └── types/                
├── drizzle/                 
└── public/                 
```
