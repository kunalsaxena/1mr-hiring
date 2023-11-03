# 1MillionResume - Intern Assignment: Resume Web Application

> Submission Deadline - Nov-06 (Monday)

## Frontend (React App) Tasks

1. Create a React application that simulates a resume in an A4-sized frame or div.
2. Display two sections: "Work Experience" and "Education" on the resume. Default order: Education before Work Experience.
3. Implement the ability to rearrange the order of resume sections using drag-and-drop functionality.
4. Add a color input with three color choices: lightgrey, lightblue, and white. The default color should be white. Allow users to select a color, and apply it as the background color of the "Work Experience" section.

## Backend (Java) Tasks

1. Create a backend application using Java/MySQL (you can use any RDBMS).
2. Programatically import sample data from a JSON file into a database. The data should include work experience and education information. A sample data JSON file is provided below.
3. Create required Classes/Objects to facilitate data import and API operations.
4. Expose this data via a REST API, ensuring that the data is sorted in reverse chronological order, from most recent to oldest. Create API endpoints to retrieve both work experience and education data.

## Requirements

- The frontend and backend should communicate using RESTful API endpoints.
- Use a database of your choice (e.g., MySQL or H2 or any other) to store and retrieve the resume data.
- Create database, tables and connection as per resume json provided.
- Make the application user-friendly and responsive.
- Implement thorough error handling and validation on frontend and backend.
- Provide clear documentation on how to run both the frontend and backend applications.

## Submission

You should submit the following:

- The complete React app code and backend app code with proper organization and comments.
- A README file with steps to run the frontend and backend application, including database setup.
- Screenshots displaying each of the following steps:
  1. React and backend applications running without errors.
  2. REST API providing sample data in response (You can use Postman to call APIs).
  3. Resume UI showing Education and Work Experience populated with data from the API in reverse chronological order.
  4. Change the section order (Work Experience first and Education second).
  5. Show a change in Work Experience background color to light blue if the user selects light blue from the input.

- Create a zip of frontend, backend, screenshots, and your resume, and share it. Follow a suggested folder structure to maintain organization.
- How to share - upload it to your google drive and generate a shareable link. Email the link to contact@1millionresume.com 

```
Your Full Name as Parent Folder

│
└───Backend
└───Frontend
└───Screenshots
└───Resume.docx or Resume.pdf
│ README.md
```

## Additional Notes

- You are encouraged to use popular libraries and frameworks to assist you in developing this application.
- Ensure that the frontend and backend applications work seamlessly together.

This assignment is designed to test your skills in React development, backend development, data storage, and API design. Good luck with your internship project!

## Sample Resume Data

```json
{
    "resume": {
      "sections": [
        {
          "title": "Work Experience",
          "items": [
            {
                "position": "Intern",
                "company": "XYZ Corporation",
                "location": "San Francisco, USA",
                "startDate": "May 2019",
                "endDate": "Aug 2019",
                "description": "Assisted with frontend development and bug fixing."
            },
            {
              "position": "Software Developer",
              "company": "ABC Tech",
              "location": "New York, USA",
              "startDate": "Jan 2020",
              "endDate": "Present",
              "description": "Developed web applications using React and Node.js."
            }
          ]
        },
        {
          "title": "Education",
          "items": [
            {
              "degree": "Bachelor of Science in Computer Science",
              "college": "University of ABC",
              "location": "Chicago, USA",
              "graduationDate": "May 2019"
            },
            {
              "degree": "High School Diploma",
              "college": "High School XYZ",
              "location": "Los Angeles, USA",
              "graduationDate": "Jun 2015"
            }
          ]
        }
      ]
    }
}
```
---
## About 1millionresume

Check out https://1millionresume.com, the ultimate AI-powered resume builder.

With 1millionresume, you can create a professional resume in just 30 minutes or less. No more wasting time on formatting, editing, or optimizing your resume. Just answer a few questions, choose a template, and let our AI do the rest.

Our resume builder will help you showcase your skills, achievements, and personality in the best possible way. It will also ensure that your resume is ATS-friendly, meaning that it will pass the automated screening systems used by most employers.

Don’t let your resume hold you back from your dream job. Try https://1millionresume.com today and see the difference it makes in your job search.

---
[logo]: https://1millionresume.com/_ipx/w_640,q_75/%2Fimages%2Fsite%2F1MR_logo_black.webp?url=%2Fimages%2Fsite%2F1MR_logo_black.webp&w=640&q=75 "1MillionResume"

### Contact
[1MillionResume](https://1millionresume.com)

Email - contact@1millionresume.com

Follow on LinkedIn for Updates - https://www.linkedin.com/company/1millionresume

