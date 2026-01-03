Problem Statement : Convert short doctor dictations to text and structure into SOAP fields.
Solution Discription : 
This project delivers an automated pipeline that converts short doctor voice dictations into structured SOAP clinical notes with minimal manual effort. 
The system is designed for speed, accuracy, and consistency—ideal for real-world clinical documentation workflows.
Audio recordings are batch-processed (20–50 clips) using Whisper / faster-whisper to generate high-quality medical transcriptions. 
These transcripts are then routed through a LangChain-powered LLM workflow, which understands clinical context and intelligently structures the content into Subjective, Objective, Assessment, and Plan sections.
A strict Pydantic schema validates and enforces the SOAP format, ensuring every output is a clean, reliable JSON object ready for EHR integration, analytics, or downstream automation. 
The pipeline supports batch processing, error handling, and scalable execution using Python.
Overall, the solution transforms unstructured clinical speech into standardized, machine-readable medical notes—reducing documentation burden, improving data quality, and enabling faster clinical workflows
