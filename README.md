<div align="center">
  <h1>Hi there! <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px" alt="wave" /></h1>
  <p>
    I'm <strong>Liantsoa</strong> — a Full-Stack Engineer who builds and ships in the cloud ☁️. AWS Certified, systems thinker, and always thinking about how the whole thing fits together.
  </p>
</div>

## Tech Stack

### ☁️ Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

### ⚙️ Backend
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/Postgres-336791?logo=postgresql&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white)
![REST API](https://img.shields.io/badge/REST-0B94DE?logo=apachespark&logoColor=white)
![Strapi](https://img.shields.io/badge/Strapi-4945FF?logo=strapi&logoColor=white)

### 🎨 Frontend
![JavaScript](https://img.shields.io/badge/JS-F7DF1E?logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TS-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Redux](https://img.shields.io/badge/Redux-764ABC?logo=redux&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?logo=jest&logoColor=white)
![Cypress](https://img.shields.io/badge/Cypress-17202C?logo=cypress&logoColor=white)
![Storybook](https://img.shields.io/badge/Storybook-FF4785?logo=storybook&logoColor=white)
![Chromatic](https://img.shields.io/badge/Chromatic-FC521F?logo=chromatic&logoColor=white)

---

<h2>📝 Latest Blog Posts</h2>

<ul>
  <li>
    <a href="https://medium.com/@rmliantsoa/the-orchestrated-saga-explained-with-a-london-weekend-39ba1ad16d24">The Orchestrated Saga, Explained with a London Weekend</a> — Nov 21, 2026 • 5 min read
  </li>
  <li>
    <a href="https://medium.com/@rmliantsoa/your-sqs-consumer-will-process-the-same-message-twice-is-your-code-ready-690f24283a75">Your SQS Consumer Will Process the Same Message Twice. Is Your Code Ready?</a> — Oct 24, 2026 • 5 min read
  </li>
  <li>
    <a href="https://medium.com/@rmliantsoa/building-a-rag-system-from-scratch-9-lessons-from-a-real-project-d5ec4555580b">Building a RAG System from Scratch: 9 Lessons from a Real Project</a> — Apr 10, 2026 • 6 min read
  </li>
  <li>
    <a href="https://medium.com/@rmliantsoa/how-to-design-a-system-when-you-dont-know-where-to-start-6d83ea324bdb">How to Design a System When You Don't Know Where to Start</a> — Feb 24, 2026 • 4 min read
  </li>
  <li>
    <a href="https://medium.com/@rmliantsoa/understanding-kubernetes-on-gke-core-concepts-for-beginners-876abdfa73c9">Understanding Kubernetes on GKE: Core Concepts for Beginners</a> — Jan 23, 2026 • 6 min read
  </li>
  <li>
    <a href="https://medium.com/@rmliantsoa/building-a-production-ready-file-uploader-a-practical-approach-71825b21d497">Building a Production-Ready File Uploader: A Practical Approach</a> — Dec 16, 2025 • 4 min read
  </li>
  <li>
    <a href="https://medium.com/@rmliantsoa/how-i-split-my-terraform-infrastructure-into-independent-layers-9cfa014a7fce">How I Split My Terraform Infrastructure into Independent Layers</a> — Oct 26, 2025 • 4 min read
  </li>
  <li>
    <a href="https://medium.com/aws-tip/connect-your-ecs-tasks-to-s3-or-dynamodb-using-a-gateway-vpc-endpoint-its-free-and-more-secure-e47d7fc7f6b7">Connect your ECS Tasks to S3 or DynamoDB using a Gateway VPC Endpoint — it’s Free and more Secure</a> — Oct 21, 2025 • 4 min read
  </li>
  <li>
    <a href="https://medium.com/@rmliantsoa/detect-inappropriate-images-in-s3-with-aws-rekognition-terraform-b1ddd185c1db">Detect inappropriate images in S3 with AWS Rekognition + Terraform</a> — Oct 18, 2025 • 5 min read
  </li>
</ul>

---

<h2>📌 Highlighted Projects</h2>
<table>
  <tr>
    <td align="center" width="240">
      <a href="https://github.com/lrasata/trip-conductor">
        <strong>Trip Conductor</strong><br />
        <img src="./docs/trip-conductor-saga.svg" width="200px" alt="Trip Conductor booking saga: reserve, charge, confirm, compensate" />
      </a>
    </td>
    <td>
      <p>
        Orchestrated trip booking: a Step Functions saga reserves a flight and a hotel, charges the payment and confirms both, compensating in reverse on failure. Commands over SQS with task tokens, a shared circuit breaker in DynamoDB, and a CQRS read model rebuilt by replaying EventBridge events.
      </p>
      <p>
        ☁️ <strong>AWS:</strong> Step Functions, Lambda, API Gateway, SQS, EventBridge, DynamoDB, SES, SNS, CloudWatch, X-Ray<br />
        🧱 <strong>IaC:</strong> Terraform<br />
        🔁 <strong>CI/CD:</strong> Yes (GitHub Actions, OIDC)<br />
        🎯 <strong>Shows:</strong> saga with a pivot and compensations, circuit breaker, idempotency, CQRS + event replay<br />
        🧠 <strong>Complexity:</strong> High
      </p>
    </td>
  </tr>

  <tr>
    <td align="center" width="240">
      <a href="https://github.com/lrasata/apply-relay">
        <strong>Apply Relay</strong><br />
        <img src="./docs/eda.png" width="200px" alt="Apply Relay event-driven architecture" />
      </a>
    </td>
    <td>
      <p>
        Event-driven job application pipeline: five Python Lambda microservices that talk only through events (SNS → SQS fan-out), with idempotent consumers, dead-letter queues and end-to-end tracing.
      </p>
      <p>
        ☁️ <strong>AWS:</strong> Lambda, API Gateway, SNS, SQS, DynamoDB, S3, SES, CloudWatch, X-Ray<br />
        🧱 <strong>IaC:</strong> Terraform<br />
        🔁 <strong>CI/CD:</strong> Yes (GitHub Actions, OIDC)<br />
        🎯 <strong>Shows:</strong> choreography, fan-out with filter policies, idempotent consumers, DLQs, end-to-end tracing<br />
        🧠 <strong>Complexity:</strong> Medium
      </p>
    </td>
  </tr>

  <tr>
    <td align="center" width="240">
      <a href="https://github.com/lrasata/infra-image-uploader">
        <strong>File Uploader</strong><br />
        <img src="./docs/upload-image-infra.png" width="200px" alt="Image uploader infrastructure" />
      </a>
    </td>
    <td>
      <p>Serverless file upload system with automated file validation, storage and antivirus scanning.</p>
      <p>
        ☁️ <strong>AWS:</strong> S3, API Gateway, Lambda, DynamoDB, Route53, WAF, CloudWatch, SNS<br />
        🧱 <strong>IaC:</strong> Terraform (module for reusable automation)<br />
        🔁 <strong>CI/CD:</strong> Yes (GitHub Actions)<br />
        🚀 <strong>Production-ready:</strong> Yes<br />
        🧠 <strong>Complexity:</strong> Medium–High
      </p>
    </td>
  </tr>

  <tr>
    <td align="center" width="240">
      <a href="https://github.com/lrasata/infra-trip-planner-webapp">
        <strong>3-Tier Web App</strong><br />
        <img src="./docs/trip-planner-infra.png" width="200px" alt="Trip planner infrastructure" />
      </a>
    </td>
    <td>
      <p>
        3-tier AWS infrastructure for a full-stack travel planner
        (React frontend, Spring Boot backend, PostgreSQL).
      </p>
      <p>
        ☁️ <strong>AWS:</strong> ECS Fargate, VPC, RDS, S3, CloudFront, Route53, API Gateway, Lambda, WAF, SNS<br />
        🧱 <strong>IaC:</strong> Terraform<br />
        🔁 <strong>CI/CD:</strong> Yes<br />
        🚀 <strong>Production-ready:</strong> Staging<br />
        🧠 <strong>Complexity:</strong> High
      </p>
    </td>
  </tr>
  <tr>
    <td align="center" width="240">
      <a href="https://github.com/lrasata/docu-chat-ai">
        <strong>RAG Docu chat app </strong><br />
        <img src="./docs/doc-chat-ai-rag.png" width="200px" alt="Doc chat using RAG" />
      </a>
    </td>
    <td>
      <p>
        AI-powered document chat using RAG. Upload PDFs and ask questions about them. Built with AWS Bedrock (Claude 4 + Titan), RDS PostgreSQL + pgvector, React, and Terraform.
      </p>
      <p>
        ☁️ <strong>AWS:</strong> S3, CloudFront, Route53, ACM Cert, Lambda, API Gateway, DynamoDB, Amazon Bedrock, RDS + pgvector<br />
        🧱 <strong>IaC:</strong> Terraform<br />
        🔁 <strong>CI/CD:</strong> Yes<br />
        🚀 <strong>Production-ready:</strong> Staging<br />
        🧠 <strong>Complexity:</strong> Medium
      </p>
    </td>
  </tr>

  <tr>
    <td align="center" width="240">
      <a href="https://github.com/lrasata/infra-s3-image-moderator">
        <strong>Image Moderator</strong><br />
        <img src="./docs/s3-image-moderator.png" width="200px" alt="Image moderator infrastructure" />
      </a>
    </td>
    <td>
      <p>
        Automated content safety scanner that periodically reviews S3 images using AWS Rekognition and flags or quarantines unsafe content.
      </p>
      <p>
        ☁️ <strong>AWS:</strong> S3, Lambda, Rekognition, EventBridge, SNS<br />
        🧱 <strong>IaC:</strong> Terraform (module for reusable automation)<br />
        🔁 <strong>CI/CD:</strong> Yes<br />
        🚀 <strong>Production-ready:</strong> Yes<br />
        🧠 <strong>Complexity:</strong> Medium (event-driven automation)
      </p>
    </td>
  </tr>
</table>
