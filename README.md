## TU CASA: Accommodation Renting Platform v2

YO Timi Here

### Overview
Tu Casa is an online accommodation platform aimed at simplifying the hostel rental process.
Unlike traditional agent-led models, Tu Casa assigns specific employees to manage the rental
process from property inspection to tenant onboarding, ensuring that both landlords and
renters experience a stress-free transaction.

### Objective
Our objective is to streamline the rental experience for both landlords and renters by eliminating
the need for intermediaries, reducing agent fees, and providing personalized support throughout
the process. Tu Casa ensures the right fit for hostels by adhering to each landlord's rules and 
helping renters settle into their hostels with care.

### Problem Solved
- **High Agent Fees**: Renters often overpay due to inflated agent fees.
- **Lack of Transparency**: Limited information on available properties creates stress for renters.
- **Tenant Screening**: Landlords struggle to find tenants who meet their rules and expectations.

### Solution
Tu Casa provides a structured and transparent approach to the accommodation process by:
- Verifying renters through their National Identification Number (NIN).
- Managing the entire rental process.
- Providing full rental journey support including property inspections and onboarding.

### Core Features
1. **Profile Creation and Verification**:
   - Landlords can list their properties and outline hostel rules.
   - Renters create verified profiles using their NIN for secure identity verification.

2. **Property Inspection and Listings**:
   - Tu Casa employees inspect properties and upload high-quality images.

3. **Search and Filter Options**:
   - Renters can search properties based on location, price, and hostel type.

4. **Real-Time Communication**:
   - Messaging between renters and Tu Casa employees.
   - Automated notifications for key actions (booking, payments).

5. **Payment Process**:
   - Renters pay via the platform, with Tu Casa collecting a 20% commission.
   - A 2-day inspection window allows renters to review the property.

6. **Onboarding and Inspection**:
   - After payment, renters are contacted by Tu Casa personnel to schedule an inspection.

7. **Renewal and Eviction Policies**:
   - Renters have a 7-day grace period to renew rent before eviction processes start.

### Tech Stack
- **Backend**: Django (Python), MySQL
- **Frontend**: Next.js (React), Tailwind CSS
- **Tools**: Docker, Swagger (API Documentation), Git

### How to Run Locally

#### Backend Setup (Django)
1. Clone the repository and navigate to the backend folder:
   ```bash
   git clone https://github.com/your-repo/tu-casa.git
   cd tu-casa/backend

