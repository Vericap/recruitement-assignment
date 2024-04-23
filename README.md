<img src = "https://i.postimg.cc/15ZnnGrT/favicon-256x256.png" width="80" height="80">

# _Vericap_
Vericap is revolutionizing the world of sustainable finance. As a financing and data infrastructure platform, Vericap specializes in de-risking investments in early-stage carbon projects. Our mission is to bridge the gap between investors and developers in the sustainability space by providing innovative financial solutions that accelerate the transition to a low-carbon economy.

---

# Junior Backend Engineer Assignment
---

## Setup Instructions:

1. Fork the repository.
2. Clone It into the system.
3. Navigate to the `assignment/junior-backend-engineer` branch.
4. You are good to go.

---

## Assignment: Project Questionnaire API

### Objective:

The objective of this project is to create APIs that facilitate the submission of new questionnaires based on selected project types. These APIs should allow users to select a project type, retrieve questions specific to that type, and submit their responses, including text and file uploads.

## Requirements:

### API Endpoints:
1. **POST** create new project
2. **GET** endpoint to retrieve questions for the selected project type.
3. **POST** endpoint to save the user's questionnaire responses (text and file uploads).

### API Guide:
1. Create a schema for projects, having the following fields
   - `project_name` as string
   - `project_city` as string
   - `project_type` as ENUM (JEE, NEET, CET)
2. Create a schema for questions, refer the Sample Quesitonary for fields
3. Map questiona schema with projects (many-to-one)
4. While creating a project, by default add 3-4 questions for that project

### Sample Questionary
[Please refer this google sheet](https://docs.google.com/spreadsheets/d/1hhu5uDFwhGLTbrSSFd-XFcFLJ444r7qsklgX5CL95qs/edit?usp=sharing)

### Data Handling:

User responses must be saved and associated with the project type and questionnaire.

### Error Handling and Validation:

1. Implement robust error handling and input validation for all API endpoints.
2. Provide clear error messages to facilitate debugging and troubleshooting.

### Few Screen References:
<img src ="https://i.postimg.cc/cLK4H68C/image.png" width="564">
<img src ="https://i.postimg.cc/3xPrD7gB/image-1.png" width="564">
<img src ="https://i.postimg.cc/fyTMhbNw/image-2.png" width="564">
<img src ="https://i.postimg.cc/bJPz3TVS/image-3.png" width="564">
<img src ="https://i.postimg.cc/sXJ38hb6/image-4.png" width="564">

### Deliverables:

1. Source code for the backend APIs, including Strapi integration.
2. Detailed API documentation outlining endpoints, expected inputs, and responses (can use Natspec).
3. `README` file with setup and testing instructions to expedite the candidate's onboarding process.
4. At last, submit your public repository with us.

### Testing Instructions:

1. Utilize tools like Postman or Curl to send requests to the defined endpoints.
2. Test each endpoint with valid and invalid inputs to ensure proper functionality.
3. Verify error messages and response formats.

---

If you have any questions or encounter issues during the setup process, please refer to the provided documentation or feel free to reach out to us at [backend@vericap.io](mailto:backend@vericap.io)

Best of luck with the assignment! We look forward to reviewing your submission.

**Team Vericap!**
