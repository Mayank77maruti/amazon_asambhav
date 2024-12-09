# Amazon Smbhav Hackathon 2024: Prototype Submission

## 1. Team Details

**Team Name:** Vyapaari

**Team Members:**
- Anshuman Rai
- Mayank Mohapatra
- Swaparup Mukherjee
- Priyanshu Das

---

## 2. Theme Details

**Theme Name:**  
**Theme No. 3:** Develop a user-friendly tool or plug-in that seamlessly integrates online stores with Amazon's Multi-Channel Fulfillment (MCF) service. This would allow businesses to leverage Amazon's logistics network with minimal coding effort.

### Theme Benefits:
- **User-friendly interface:** AI chatbot for managing e-commerce tasks like inventory and delivery handling.  
- **Amazon's MCF integration:** PAN India logistics network for effortless scaling.  
- **Unified order management:** Single dashboard to handle orders from multiple platforms.  
- **SLAs and Delivery Speed Estimation:** Improves customer experience.  
- **Real-time analytics and AI-based suggestions:** Inventory and pricing optimization.  
- **Marketplace integration:** Connects small manufacturers with sellers.  
- **Order verification system:** Reduces cancellations.  

---

## 3. Idea and Approach Details

### Solution Overview:  
"Our platform, **One Stop Vyapaar**, is an AI-powered integration hub for small and medium-sized businesses (SMBs). It combines Amazon’s MCF with a tailored marketplace for manufacturers, enabling seamless inventory and quality management."

---

### Key Features:
- **Unified inventory and order management:** Real-time view across multiple platforms.  
- **AI-powered inventory suggestions:** Predictive analytics for optimal stock management.  
- **Dynamic pricing:** AI-based pricing adjustments using PyCaret.  
- **Oversell prevention:** Real-time alerts powered by AWS Lambda and SNS.  
- **Geolocation heatmaps:** Identify and manage regions with high return rates.  
- **International fulfillment:** Expand globally with Amazon’s API.  
- **Built-in marketplace:** Connect manufacturers, wholesalers, and dropshippers with sellers.  

---

### Technical Stack:
- **Frontend:** Next.js, Tailwind CSS, Material-UI.  
- **Backend:** Node.js (Express/NestJS), AWS Lambda, AWS API Gateway.  
- **Core Technologies:** Docker, AWS ECS, AWS ELB.  
- **Storage:** AWS DynamoDB, AWS RDS, AWS S3.  
- **Security:** AWS IAM, AWS KMS, AWS Cognito.  
- **AI/ML Tools:** PyCaret, AWS Personalize.  

---

## 4. Methodology/Architecture Diagram

![Image](https://github.com/user-attachments/assets/8d6faa7f-0711-468a-bd7e-096532201299)


---

## 5. Open Source Disclosure

| **Technology**      | **Version**      | **License**          | **Source Link**                                                  |
|----------------------|------------------|----------------------|------------------------------------------------------------------|
| Tailwind CSS         | v3.4.1          | MIT License          | [GitHub](https://github.com/tailwindlabs/tailwindcss)            |
| Next.js              | v13.5.6         | MIT License          | [GitHub](https://github.com/vercel/next.js)                      |
| React                | v18.2.0         | MIT License          | [GitHub](https://github.com/facebook/react)                      |
| Axios                | v1.7.7          | MIT License          | [GitHub](https://github.com/axios/axios)                         |
| Prisma               | v5.22.0         | Apache License 2.0   | [GitHub](https://github.com/prisma/prisma)                       |
| CopilotKit           | v1.3.15         | MIT License          | [GitHub](https://github.com/copilotkit/copilotkit)               |

---

## 6. Prototype Demonstration

- **[Demo Link](https://drive.google.com/drive/folders/1zgua0Z-7xckWaaR21-l1juH-s15EPIFs?usp=sharing)**  
- **[Deployment Link](https://amazon-asambhav.vercel.app/)**  

---

## 🚀 Getting Started

### Open Using Daytona

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).

2. **Create the Workspace**:

   ```bash
   daytona create https://github.com/Mayank77maruti/amazon_asambhav.git
   ```

3. **Start the Application**:
   ```bash
   npm run dev
   ```

---

## 🤔 **Why Use DevContainer and Daytona?**

### **DevContainer**

- Simplifies development environment setup in VS Code.
- Perfect for team collaboration in open-source projects.
- Eliminates the hassle of creating dev environments for contributors.
- Automatically configures extensions and settings for a consistent experience.

### **Daytona**

- Works with **any Git platform**: GitHub, GitLab, Bitbucket.
- Compatible with **any IDE**: Vim, VS Code, JetBrains IDEs.
- Runs **anywhere**: Localhost, AWS, Azure, GCP, Digital Ocean.
- Flexible and efficient for modern development workflows.

> **Note:**  
> Learn how to integrate Daytona into your Next.js app by reading this article:  
> [Integrate Daytona in Your Next.js App](https://dev.to/komsenapati/integrate-dayotana-in-your-nextjs-app-36ei)

---

## Getting Started {Simple Start}

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result

Docker Installation Process 
1. To build the image
```bash
docker build -t amazon-asambhav-app .
```
![installwrite](https://github.com/user-attachments/assets/3b199ee9-4643-4303-8033-b27dc2f5cb91)


2. To run the image
```bash
docker run -p 3000:3000 amazon-asambhav-app
```
3. To stop the image
First -> open another terminal and run docker ps take the container id from their
```bash
docker ps
```
then 
```bash
docker stop <container_id>
```
![dockerinstallimg](https://github.com/user-attachments/assets/0faf2d70-bd17-40a2-999d-dc5d23615f6a)


You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
