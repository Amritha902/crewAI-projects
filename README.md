# Enhanced CrewAI Job Application Automation System

This project is the final submission for the **CrewAI course**. It implements a multi-agent AI system to automate the job application process. The system simulates a team of specialized agents working together to analyze job postings, optimize resumes, and generate personalized cover letters.

The project helped in understanding and applying core concepts of multi-agent collaboration, modular AI workflows, robust file handling, and real-world automation design.

## Key Features

- **Multi-Agent Orchestration**  
  Simulates agents for job research, company analysis, skills gap detection, resume optimization, and cover letter writing.

- **Job Analysis**  
  Extracts and summarizes key requirements, qualifications, and company culture from job descriptions.

- **Company Research**  
  Gathers relevant information about the company to tailor the application.

- **Skills Gap Analysis**  
  Compares the resume against job requirements to identify strengths and missing skills.

- **Resume Optimization**  
  Generates an ATS-friendly resume aligned with each specific job.

- **Cover Letter Generation**  
  Produces a tailored cover letter for each job and company.

- **Output Management**  
  Saves all generated files with timestamps in the `job_application_output/` directory:
  - Optimized resume  
  - Personalized cover letter  
  - Job and resume analysis report  
  - Metadata file

- **File and Encoding Handling**  
  Ensures safe reading/writing of files across systems using encoding detection (`chardet`).

- **Mock and Real Modes**  
  Supports both test (mock) data and real CrewAI agents (with API setup).

- **Error Handling and Logging**  
  Logs system operations and handles failures gracefully. Compatible with Windows systems.

## Project Reflection

This project was built as part of the CrewAI course and demonstrates how multi-agent systems can be used for real-world automation tasks. The course provided a solid foundation in designing and structuring collaborative AI agents, and the final project helped solidify those concepts in a practical setting.

## Author

**Amritha S**  
📧 amritha16112005@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/amritha-s-0a2002263)

## License

This project is licensed under the MIT License.
