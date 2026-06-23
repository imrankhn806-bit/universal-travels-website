# Architecture Diagram

```mermaid
flowchart TD

A[Visitor] --> B[Website Frontend]

B --> C[Homepage]
B --> D[Travel Packages]
B --> E[Services]
B --> F[Contact Us]

F --> G[Inquiry Form]

G --> H[PHP Backend]

H --> I[MySQL Database]

J[WordPress CMS] --> H

H --> K[Travel Packages]
H --> L[Customer Inquiries]
H --> M[Travel Services Content]

B --> N[Responsive Design]
B --> O[SEO Optimization]

```
