# Simple Prompt

I would like a deep research prompt for this: I have a repository readme that is a list of resources - some of which are papers https://github.com/RichardScottOZ/mineral-exploration-machine-learning - and lots of these are researchgate urls - can any llm type approachread that list and then check which ones are open access and maybe make an agent that can download them? Some will be papers at science direct, some are other paper providers - some are researchgate, there will be a few arxiv, etc, so needs to be flexible - hence llm possibilities. Things like crossref and openalex might be able to help - what other apis or github repos where people have written things that could help be able to do this?

# Model Prompt

Deep-Research-Guide


Show thinking
Hello! As Deep-Research-Guide, I've prepared a unique and insightful research prompt based on your request, complete with guiding questions to facilitate a thorough investigation into creating an automated system for accessing research papers.

Deep Research Prompt:
Investigate and design a modular, AI-driven framework for an autonomous agent capable of parsing a heterogeneous list of resource URLs (e.g., from a GitHub README), intelligently identifying the ones that point to academic papers, determining their open-access status, and systematically retrieving the full-text PDF when legally and technically feasible.

Side Questions for Deep Research Inclusion:
To facilitate a comprehensive exploration, consider including these specific questions in your deep research query:

Metadata Extraction and Identification: How can an agent reliably extract structured metadata (e.g., DOI, title, authors) from unstructured text and varied URLs? What natural language processing (NLP) or LLM-based techniques are most effective for identifying that a URL points to a research paper versus a blog post, repository, or news article?

Open Access Status Verification: What are the most robust APIs and services for programmatically checking the open-access status of a paper using its DOI or other metadata?

Conduct a comparative analysis of the Unpaywall API, OpenAlex API, and Crossref API. What are the differences in their data, rate limits, and the types of "open access" they can identify (e.g., gold, green, bronze)?

How can the agent handle sources like ArXiv, which are inherently open, versus publisher-specific sites like ScienceDirect or IEEE Xplore?

System Architecture and Workflow: What would be an optimal system architecture for this agent?

Consider a pipeline: URL Input -> Content Analysis -> Metadata Extraction -> OA Status Check -> Conditional Retrieval.

What existing Python libraries (e.g., requests, BeautifulSoup, Selenium, Playwright) and GitHub repositories could serve as foundational components for web scraping and browser automation?

The Role of Large Language Models (LLMs): Beyond simple parsing, how could an LLM enhance the agent's capabilities?

Could an LLM be used to generate or guide the logic for navigating publisher-specific download pages, which often have unique HTML structures and JavaScript-based interactions?

Can an LLM classify the type of paywall or access barrier encountered to decide on the next action?

Automated Retrieval and Challenges: What are the primary technical and ethical challenges in automating the download of PDFs?

How can the agent effectively handle CAPTCHAs, dynamic JavaScript-heavy pages, and other anti-scraping mechanisms?

What strategies can ensure the agent only downloads papers that are genuinely open access, respecting publisher copyrights and terms of service?

Existing Tools and Repositories: What existing open-source projects or academic research papers have attempted similar tasks?

Investigate tools like unpywall, habanero (Crossref client), or browser automation frameworks. What are their limitations for this specific, multi-source problem?

Evaluation and Metrics: How would you measure the success of such an agent? Consider metrics like precision (percentage of retrieved papers that were correctly identified as OA), recall (percentage of all available OA papers on the list that were successfully retrieved), and retrieval speed.


For your investigation, prioritize peer-reviewed papers on web scraping, information retrieval, and applied NLP, alongside the official documentation for APIs like Unpaywall and OpenAlex, and reputable open-source software repositories.
