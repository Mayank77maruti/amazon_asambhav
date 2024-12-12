# Onestop Vyapar

## 1. 🚀 Project Overview

**Onestop Vyapar** is an AI-powered integration hub tailored for small and medium-sized businesses (SMBs). It seamlessly combines Amazon’s Multi-Channel Fulfillment (MCF) services with a custom marketplace for manufacturers. This platform provides:

- Unified inventory and order management.
- AI-powered inventory suggestions.
- Dynamic pricing and oversell prevention.
- Geolocation heatmaps for return rate analysis.
- International fulfillment and PAN India logistics.
- Real-time analytics for business optimization.

## 2. 🔧 Technical Stack

### **Frontend**
- **Framework**: Next.js
- **Styling**: Tailwind CSS, Material-UI

### **Backend**
- **Core**: Node.js (Express/NestJS)
- **APIs**: AWS Lambda, AWS API Gateway

### **DevOps and Infrastructure**
- **Containerization**: Docker
- **Orchestration**: AWS ECS, AWS ELB
- **Storage**: AWS DynamoDB, AWS RDS, AWS S3
- **Security**: AWS IAM, AWS KMS, AWS Cognito

### **AI/ML Tools**
- PyCaret
- AWS Personalize

---

## 3. 🎨 Features

1. **Unified Inventory and Order Management**:
   - Real-time visibility across multiple platforms.
2. **AI-Powered Inventory Suggestions**:
   - Predictive analytics for stock management.
3. **Dynamic Pricing**:
   - AI-driven pricing adjustments using PyCaret.
4. **Oversell Prevention**:
   - Real-time alerts powered by AWS Lambda and SNS.
5. **Geolocation Heatmaps**:
   - Insights into regions with high return rates.
6. **International Fulfillment**:
   - Simplified global expansion with Amazon APIs.
7. **Built-in Marketplace**:
   - Connects manufacturers, wholesalers, and dropshippers with sellers.
8. **DevOps with AWS**:
   - Leverages AWS ECR, ECS, and S3 for streamlined deployment and scaling.
9. **SSL Certificate**:
   - Secures data transmission with encryption.
10. **User-Friendly Interface**:
    - AI chatbot for inventory and delivery management.
11. **Amazon MCF Integration**:
    - Utilizes Amazon’s PAN India logistics network.
12. **Real-Time Analytics**:
    - AI-driven insights for inventory and pricing optimization.

---

## 4. 🎨 Methodology

![Architecture Diagram](https://github.com/user-attachments/assets/8d6faa7f-0711-468a-bd7e-096532201299)

---

## 5. ✅ Getting Started

### **Using Daytona**

1. **Install Daytona**: Follow the [Daytona Installation Guide](https://www.daytona.io/docs/installation/installation/).
2. **Create the Workspace**:

   ```bash
   daytona create https://github.com/Mayank77maruti/amazon_asambhav.git
   ```

### **Manual Installation**

1. Run the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

   Open [http://localhost:3000](http://localhost:3000) to view the application.

2. Start editing by modifying `app/page.tsx`. Changes will auto-update the application.

3. Learn more about Next.js through the [Next.js Documentation](https://nextjs.org/docs) or the [interactive tutorial](https://nextjs.org/learn).

### **Docker Installation**

1. Build the image:

   ```bash
   docker build -t amazon-asambhav-app .
   ```

   ![Build Image](https://github.com/user-attachments/assets/3b199ee9-4643-4303-8033-b27dc2f5cb91)

2. Run the image:

   ```bash
   docker run -p 3000:3000 amazon-asambhav-app
   ```

3. Stop the container:

   ```bash
   docker ps
   docker stop <container_id>
   ```

   ![Stop Image](https://github.com/user-attachments/assets/0faf2d70-bd17-40a2-999d-dc5d23615f6a)

---

## 6. ✨ Deployment

### **Vercel Deployment**

The easiest way to deploy your Next.js app is via [Vercel](https://vercel.com/new). Learn more in the [deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying).

### **Prototype Demonstration**

- [Demo Link](https://drive.google.com/drive/folders/1zgua0Z-7xckWaaR21-l1juH-s15EPIFs?usp=sharing)
- [Deployment Link](https://amazon-asambhav.vercel.app/)

---

## 7. 🌐 Open Source Disclosure

| **Technology**      | **Version** | **License**         | **Source Link**                                       |
|----------------------|-------------|---------------------|-------------------------------------------------------|
| Tailwind CSS         | v3.4.1      | MIT License         | [GitHub](https://github.com/tailwindlabs/tailwindcss) |
| Next.js              | v13.5.6     | MIT License         | [GitHub](https://github.com/vercel/next.js)          |
| React                | v18.2.0     | MIT License         | [GitHub](https://github.com/facebook/react)          |
| Axios                | v1.7.7      | MIT License         | [GitHub](https://github.com/axios/axios)             |
| Prisma               | v5.22.0     | Apache License 2.0  | [GitHub](https://github.com/prisma/prisma)           |
| CopilotKit           | v1.3.15     | MIT License         | [GitHub](https://github.com/copilotkit/copilotkit)   |

---

## 8. 🔗 Additional Resources

- [Learn Next.js](https://nextjs.org/learn)
- [Next.js GitHub Repository](https://github.com/vercel/next.js)
- [Daytona Integration Guide](https://dev.to/mayank_mohapatra/integrate-daytona-and-let-the-magic-begin-38hg)

